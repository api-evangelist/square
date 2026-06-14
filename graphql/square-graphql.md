# Square GraphQL Schema

## Overview

This conceptual GraphQL schema models the Square payments and commerce platform. Square provides APIs for payment processing, point of sale, catalog management, inventory, customer relationship management, loyalty programs, bookings, subscriptions, invoicing, team management, and terminal device operations.

The schema is derived from Square's REST API surface documented at https://developer.squareup.com/reference/square/ and covers the core domain objects across all major Square API verticals.

## Schema Source

- **Provider**: Square, Inc.
- **Base REST API**: https://developer.squareup.com/reference/square/
- **GitHub**: https://github.com/square
- **Developer Portal**: https://developer.squareup.com/us/en
- **Schema File**: square-schema.graphql
- **Type**: Conceptual GraphQL schema (not an officially published Square GraphQL endpoint)

## Domain Coverage

### Payments and Refunds
Core payment processing types covering card payments, digital wallets, ACH bank transfers, buy now pay later, cash, and external payment methods. Includes the full lifecycle from payment creation through refund and dispute management.

Types: `Payment`, `PaymentMethod`, `CardDetails`, `Card`, `BankAccount`, `WalletDetails`, `BuyNowPayLater`, `CashDetails`, `ExternalDetails`, `Refund`, `Dispute`, `DisputeEvidence`, `Money`

### Orders and Fulfillment
Order management covering line items, fulfillment options (pickup and shipment), order returns, price modifications, and order-level financial totals.

Types: `Order`, `OrderLineItem`, `OrderFulfillment`, `FulfillmentPickup`, `FulfillmentShipment`, `OrderReturn`, `ReturnLineItem`, `OrderPriceModification`, `OrderAmounts`

### Checkout and Invoices
Hosted checkout pages and invoice-based payment collection with scheduling support.

Types: `Checkout`, `CheckoutOrder`, `Invoice`, `InvoiceLineItem`, `InvoiceSchedule`

### Subscriptions
Recurring revenue management with configurable plan phases and subscription lifecycle events.

Types: `Subscription`, `SubscriptionPhase`, `SubscriptionEvent`, `Plan`, `PlanPhase`

### Customers and CRM
Customer profile management including address data, group membership, smart segments, and attribute-based filtering.

Types: `Customer`, `CustomerAddress`, `CustomerGroup`, `CustomerSegment`, `CustomerFilter`

### Catalog
Product and service catalog with items, variations, modifiers, categories, discounts, taxes, pricing rules, and availability scheduling.

Types: `Catalog`, `CatalogItem`, `CatalogItemVariation`, `CatalogModifier`, `CatalogCategory`, `CatalogDiscount`, `CatalogTax`, `CatalogPricingRule`, `CatalogAvailabilityPeriod`

### Inventory
Stock level tracking and inventory movement transfers across locations.

Types: `Inventory`, `InventoryTransfer`

### Locations and Merchants
Business location management and merchant organization hierarchy.

Types: `Location`, `Merchant`

### Team and Labor
Team member roster management, job configuration, shift tracking, break recording, and labor cost reporting.

Types: `Employee`, `Team`, `Labor`, `Shift`, `Break`, `TeamMember`

### Loyalty
Loyalty program setup, account enrollment, points accrual, reward redemption, and event history.

Types: `Loyalty`, `LoyaltyAccount`, `LoyaltyReward`, `LoyaltyEvent`

### Bookings
Appointment and service booking with team member and service availability management.

Types: `Booking`, `BookingService`, `BookingTeam`

### Terminal and Devices
In-person payment terminal integration and device pairing via device codes.

Types: `Terminal`, `TerminalCheckout`, `DeviceCode`

### Webhooks and Events
Programmatic webhook subscription management and event notification delivery.

Types: `Webhook`, `WebhookEvent`

### Authentication
OAuth 2.0 access token management for third-party application authorization.

Types: `OAuth`, `OAuthToken`

### Gift Cards
Digital and physical gift card lifecycle management including activation, loading, and redemption activities.

Types: `GiftCard`, `GiftCardActivity`

### Payouts
Bank deposit and withdrawal visibility for seller payout tracking.

Types: `Payout`, `PayoutEntry`

### Vendors
Supplier and vendor management for inventory procurement workflows.

Types: `Vendor`, `VendorContact`

### Custom Attributes
Extensible metadata attached to core Square resources via custom attribute definitions.

Types: `CustomAttribute`, `CustomAttributeDefinition`

## Root Operations

### Query
- `payment(id: ID!)`: Retrieve a single payment by ID
- `payments(locationId: ID, cursor: String, limit: Int)`: List payments with pagination
- `order(id: ID!)`: Retrieve a single order
- `orders(locationIds: [ID!], cursor: String)`: List orders
- `customer(id: ID!)`: Retrieve a customer profile
- `customers(cursor: String, limit: Int, filter: CustomerFilter)`: Search customers
- `catalogItem(id: ID!)`: Retrieve a catalog item
- `catalog(cursor: String, types: [String])`: List catalog objects
- `location(id: ID!)`: Retrieve a location
- `locations`: List all locations for a merchant
- `invoice(id: ID!)`: Retrieve an invoice
- `invoices(locationId: ID!, cursor: String)`: List invoices
- `subscription(id: ID!)`: Retrieve a subscription
- `booking(id: ID!)`: Retrieve a booking
- `shift(id: ID!)`: Retrieve a labor shift
- `loyaltyAccount(id: ID!)`: Retrieve a loyalty account
- `dispute(id: ID!)`: Retrieve a dispute
- `refund(id: ID!)`: Retrieve a refund
- `terminalCheckout(id: ID!)`: Retrieve a terminal checkout
- `giftCard(id: ID!)`: Retrieve a gift card
- `webhook(id: ID!)`: Retrieve a webhook subscription
- `payout(id: ID!)`: Retrieve a payout
- `vendor(id: ID!)`: Retrieve a vendor
- `teamMember(id: ID!)`: Retrieve a team member

### Mutation
- `createPayment(input: CreatePaymentInput!)`: Create a new payment
- `cancelPayment(id: ID!)`: Cancel a payment
- `completePayment(id: ID!)`: Complete a delayed-capture payment
- `createRefund(input: CreateRefundInput!)`: Refund a payment
- `createOrder(input: CreateOrderInput!)`: Create a new order
- `updateOrder(id: ID!, input: UpdateOrderInput!)`: Update an order
- `createCustomer(input: CreateCustomerInput!)`: Create a customer profile
- `updateCustomer(id: ID!, input: UpdateCustomerInput!)`: Update a customer
- `deleteCustomer(id: ID!)`: Delete a customer
- `upsertCatalogObject(input: UpsertCatalogInput!)`: Create or update a catalog object
- `deleteCatalogObject(id: ID!)`: Delete a catalog object
- `createInvoice(input: CreateInvoiceInput!)`: Create an invoice
- `publishInvoice(id: ID!, version: Int!)`: Publish an invoice
- `createSubscription(input: CreateSubscriptionInput!)`: Create a subscription
- `cancelSubscription(id: ID!)`: Cancel a subscription
- `createBooking(input: CreateBookingInput!)`: Create a booking
- `cancelBooking(id: ID!)`: Cancel a booking
- `createShift(input: CreateShiftInput!)`: Create a labor shift
- `deleteShift(id: ID!)`: Delete a shift
- `createLoyaltyAccount(input: CreateLoyaltyAccountInput!)`: Enroll a customer in loyalty
- `accumulateLoyaltyPoints(accountId: ID!, input: AccumulatePointsInput!)`: Add loyalty points
- `createLoyaltyReward(input: CreateLoyaltyRewardInput!)`: Create a loyalty reward
- `redeemLoyaltyReward(rewardId: ID!, checkoutId: ID!)`: Redeem a loyalty reward
- `createTerminalCheckout(input: CreateTerminalCheckoutInput!)`: Initiate terminal checkout
- `createWebhookSubscription(input: CreateWebhookInput!)`: Create webhook subscription
- `deleteWebhookSubscription(id: ID!)`: Delete a webhook subscription
- `createGiftCard(input: CreateGiftCardInput!)`: Create a gift card
- `createVendor(input: CreateVendorInput!)`: Create a vendor

## Type Count

This schema defines 78 named types covering the full Square commerce platform domain.
