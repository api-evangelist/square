# Square (square)
Square provides APIs for payment processing, point of sale, and business management solutions enabling developers to build custom commerce applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/square/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Scope

- **Type:** Index 
- **Position:** Consumer 
- **Access:** 3rd-Party 

## Tags:

 - Restaurant, Bookings, Catalog, Checkout, Customers, Disputes, Ecommerce, Financial Technology, Gift Cards, Inventory, Invoicing, Labor, Locations, Loyalty, Merchants, Orders, Payments, Point of Sale, Refunds, Retail, Subscriptions, Team, Terminal, Webhooks

## Timestamps

- **Created:** 2025-02-08 
- **Modified:** 2026-06-03 

## APIs

### Square Payments API
The Payments API lets applications take and manage payments by charging payment methods supported by the Web Payments SDK or In-App Payments SDK, including credit cards, gift cards, digital wallets, and ACH bank transfers. It can also record cash or external payments received outside of Square.

**Human URL:** [https://developer.squareup.com/docs/payments-overview](https://developer.squareup.com/docs/payments-overview)

#### Tags:

 - Commerce, Financial Technology, Payments, Point of Sale

#### Properties

- [Documentation](https://developer.squareup.com/docs/payments-overview)
- [APIReference](https://developer.squareup.com/reference/square/payments-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-mobileauthorization.yaml)
- [NaftikoCapability](capabilities/square-payments.yaml)

### Square Orders API
The Orders API lets applications itemize payments using custom line items or catalog objects, send orders to physical Point of Sale devices for fulfillment, attach customers to payments, and search through all of a seller's past sales with itemization data.

**Human URL:** [https://developer.squareup.com/docs/orders-api/what-it-does](https://developer.squareup.com/docs/orders-api/what-it-does)

#### Tags:

 - Commerce, Orders, Point of Sale

#### Properties

- [Documentation](https://developer.squareup.com/docs/orders-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/orders-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-orders.yaml)
- [NaftikoCapability](capabilities/square-transactions.yaml)
- [NaftikoCapability](capabilities/square-v1transactions.yaml)

### Square Catalog API
The Catalog API programmatically catalogs a Square seller's products for sale and services for hire, enabling applications to create, update, and manage catalog items, categories, variations, and pricing.

**Human URL:** [https://developer.squareup.com/docs/catalog-api/what-it-does](https://developer.squareup.com/docs/catalog-api/what-it-does)

#### Tags:

 - Catalog, Commerce, Products

#### Properties

- [Documentation](https://developer.squareup.com/docs/catalog-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/catalog-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-catalog.yaml)

### Square Inventory API
The Inventory API programmatically manages a Square seller's inventory of catalog items, including updating and tracking inventory changes and retrieving inventory counts.

**Human URL:** [https://developer.squareup.com/docs/inventory-api/what-it-does](https://developer.squareup.com/docs/inventory-api/what-it-does)

#### Tags:

 - Commerce, Inventory, Retail

#### Properties

- [Documentation](https://developer.squareup.com/docs/inventory-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/inventory-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-inventory.yaml)

### Square Customers API
The Customers API lets applications create and manage customer profiles to streamline bookings, build loyalty programs, sell gift cards, and offer discounts. It enables syncing CRM systems with Square.

**Human URL:** [https://developer.squareup.com/docs/customers](https://developer.squareup.com/docs/customers)

#### Tags:

 - Commerce, CRM, Customers

#### Properties

- [Documentation](https://developer.squareup.com/docs/customers)
- [APIReference](https://developer.squareup.com/reference/square/customers-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-customers.yaml)

### Square Locations API
The Locations API lets applications create and manage the locations of a seller's business, including retrieving location details and managing location settings.

**Human URL:** [https://developer.squareup.com/docs/locations-api](https://developer.squareup.com/docs/locations-api)

#### Tags:

 - Business Management, Commerce, Locations

#### Properties

- [Documentation](https://developer.squareup.com/docs/locations-api)
- [APIReference](https://developer.squareup.com/reference/square/locations-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-locations.yaml)

### Square Team API
The Team API lets applications create and manage a roster of team members, configure jobs, and synchronize team member data with external platforms including accounting and payroll systems.

**Human URL:** [https://developer.squareup.com/docs/team/overview](https://developer.squareup.com/docs/team/overview)

#### Tags:

 - Business Management, Employees, Team

#### Properties

- [Documentation](https://developer.squareup.com/docs/team/overview)
- [APIReference](https://developer.squareup.com/reference/square/team-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-employees.yaml)
- [NaftikoCapability](capabilities/square-team.yaml)

### Square Labor API
The Labor API is the timekeeping component of Square's team management APIs, enabling applications to manage time tracking and scheduling for team members, record hours worked, and handle breaks, wages, and declared cash tips for labor cost reporting and payroll.

**Human URL:** [https://developer.squareup.com/docs/labor-api/what-it-does](https://developer.squareup.com/docs/labor-api/what-it-does)

#### Tags:

 - Business Management, Labor, Time Tracking

#### Properties

- [Documentation](https://developer.squareup.com/docs/labor-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/labor-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-labor.yaml)

### Square Bookings API
The Bookings API enables creating reservations of services provided by a seller's staff for customers at particular locations and times. Applications can create, update, cancel, and search for available bookings.

**Human URL:** [https://developer.squareup.com/docs/bookings-api/what-it-is](https://developer.squareup.com/docs/bookings-api/what-it-is)

#### Tags:

 - Appointments, Bookings, Scheduling

#### Properties

- [Documentation](https://developer.squareup.com/docs/bookings-api/what-it-is)
- [APIReference](https://developer.squareup.com/reference/square/bookings-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-bookings.yaml)

### Square Loyalty API
The Loyalty API allows applications to set up and manage loyalty programs, enroll buyers, accrue points, and redeem rewards. It works with the Orders API to manage loyalty accounts and rewards at participating locations.

**Human URL:** [https://developer.squareup.com/docs/loyalty-api/overview](https://developer.squareup.com/docs/loyalty-api/overview)

#### Tags:

 - Customer Engagement, Loyalty, Rewards

#### Properties

- [Documentation](https://developer.squareup.com/docs/loyalty-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/loyalty-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-loyalty.yaml)

### Square Gift Cards API
The Gift Cards API enables sellers to launch a gifting program with digital and physical gift cards. Applications can create, retrieve, link, and unlink gift cards, and manage gift card activities such as activating, loading, and redeeming.

**Human URL:** [https://developer.squareup.com/docs/gift-cards/using-gift-cards-api](https://developer.squareup.com/docs/gift-cards/using-gift-cards-api)

#### Tags:

 - Commerce, Customer Engagement, Gift Cards

#### Properties

- [Documentation](https://developer.squareup.com/docs/gift-cards/using-gift-cards-api)
- [APIReference](https://developer.squareup.com/reference/square/gift-cards-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-giftcards.yaml)

### Square Invoices API
The Invoices API lets applications request or automatically collect payments from customers for orders created using the Orders API. It supports creating, updating, publishing, and managing invoices with multiple payment schedules and methods.

**Human URL:** [https://developer.squareup.com/docs/invoices-api/overview](https://developer.squareup.com/docs/invoices-api/overview)

#### Tags:

 - Billing, Invoices, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/invoices-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/invoices-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-invoices.yaml)

### Square Subscriptions API
The Subscriptions API enables sellers to generate recurring revenue by offering scheduled fulfillment of products or services. Applications can create and manage subscription plans with configurable billing periods, pricing, and discounts.

**Human URL:** [https://developer.squareup.com/docs/subscriptions-api/overview](https://developer.squareup.com/docs/subscriptions-api/overview)

#### Tags:

 - Commerce, Recurring Payments, Subscriptions

#### Properties

- [Documentation](https://developer.squareup.com/docs/subscriptions-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/subscriptions-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-subscriptions.yaml)

### Square Checkout API
The Checkout API creates Square-hosted checkout pages for collecting payments. Applications can generate payment links with a simple API call, supporting credit cards, debit cards, Google Pay, Apple Pay, Afterpay, and Cash App.

**Human URL:** [https://developer.squareup.com/docs/checkout-api](https://developer.squareup.com/docs/checkout-api)

#### Tags:

 - Checkout, Commerce, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/checkout-api)
- [APIReference](https://developer.squareup.com/reference/square/checkout-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-checkout.yaml)

### Square Terminal API
The Terminal API lets developers integrate Square in-person payments so custom POS applications can use Square Terminal for card chip and NFC payments, with EMV certification and PCI compliance built in.

**Human URL:** [https://developer.squareup.com/docs/terminal-api/overview](https://developer.squareup.com/docs/terminal-api/overview)

#### Tags:

 - In-Person Payments, Point of Sale, Terminal

#### Properties

- [Documentation](https://developer.squareup.com/docs/terminal-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/terminal-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-terminal.yaml)

### Square Refunds API
The Refunds API lets applications refund the entire payment amount or a portion of it for card payments, and record refunds of cash or external payments.

**Human URL:** [https://developer.squareup.com/docs/payments-refunds](https://developer.squareup.com/docs/payments-refunds)

#### Tags:

 - Commerce, Payments, Refunds

#### Properties

- [Documentation](https://developer.squareup.com/docs/payments-refunds)
- [APIReference](https://developer.squareup.com/reference/square/refunds-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-refunds.yaml)

### Square Disputes API
The Disputes API manages payment disputes and chargebacks, allowing applications to list disputes, retrieve dispute details, challenge disputes by submitting evidence, and accept disputes.

**Human URL:** [https://developer.squareup.com/docs/disputes-api/overview](https://developer.squareup.com/docs/disputes-api/overview)

#### Tags:

 - Chargebacks, Disputes, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/disputes-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/disputes-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-disputes.yaml)

### Square Merchants API
The Merchants API groups individual seller locations into larger organizations, with each merchant representing one organization or business that sells with Square.

**Human URL:** [https://developer.squareup.com/docs/merchants-api](https://developer.squareup.com/docs/merchants-api)

#### Tags:

 - Business Management, Commerce, Merchants

#### Properties

- [Documentation](https://developer.squareup.com/docs/merchants-api)
- [APIReference](https://developer.squareup.com/reference/square/merchants-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-merchants.yaml)

### Square Cards API
The Cards API lets applications save a credit or debit card on file for a customer, enabling faster future payments without re-entering card details.

**Human URL:** [https://developer.squareup.com/docs/cards-api/overview](https://developer.squareup.com/docs/cards-api/overview)

#### Tags:

 - Cards, Commerce, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/cards-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/cards-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-cards.yaml)

### Square Vendors API
The Vendors API lets applications manage vendors and suppliers for a seller, enabling creation, retrieval, and updating of vendor information.

**Human URL:** [https://developer.squareup.com/docs/vendors-api/manage-vendors-in-apps](https://developer.squareup.com/docs/vendors-api/manage-vendors-in-apps)

#### Tags:

 - Inventory, Suppliers, Vendors

#### Properties

- [Documentation](https://developer.squareup.com/docs/vendors-api/manage-vendors-in-apps)
- [APIReference](https://developer.squareup.com/reference/square/vendors-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-vendors.yaml)

### Square Cash Drawers API
The Cash Drawers API is a reporting API for businesses that use a cash drawer with their Square Point of Sale terminals, providing filtered and paged lists of cash drawer shift data for a given location.

**Human URL:** [https://developer.squareup.com/docs/cashdrawershift-api/reporting](https://developer.squareup.com/docs/cashdrawershift-api/reporting)

#### Tags:

 - Cash Drawers, Point of Sale, Reporting

#### Properties

- [Documentation](https://developer.squareup.com/docs/cashdrawershift-api/reporting)
- [APIReference](https://developer.squareup.com/reference/square/cash-drawers-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-cashdrawers.yaml)

### Square Bank Accounts API
The Bank Accounts API lets applications retrieve a list of a seller's bank accounts and get details about specific bank accounts linked to a Square account.

**Human URL:** [https://developer.squareup.com/docs/bank-accounts-api](https://developer.squareup.com/docs/bank-accounts-api)

#### Tags:

 - Bank Accounts, Financial Technology, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/bank-accounts-api)
- [APIReference](https://developer.squareup.com/reference/square/bank-accounts-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-bankaccounts.yaml)

### Square Payouts API
The Payouts API lets applications get a list of deposits and withdrawals from a seller's bank accounts, providing visibility into funds movement.

**Human URL:** [https://developer.squareup.com/docs/payouts-api/overview](https://developer.squareup.com/docs/payouts-api/overview)

#### Tags:

 - Financial Technology, Payments, Payouts

#### Properties

- [Documentation](https://developer.squareup.com/docs/payouts-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/payouts-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-payouts.yaml)

### Square Apple Pay API
The Apple Pay API provides an easy way for platform developers to bulk activate Web Apple Pay with Square for merchants using their platform.

**Human URL:** [https://developer.squareup.com/docs/web-payments/apple-pay](https://developer.squareup.com/docs/web-payments/apple-pay)

#### Tags:

 - Apple Pay, Digital Wallets, Payments

#### Properties

- [Documentation](https://developer.squareup.com/docs/web-payments/apple-pay)
- [APIReference](https://developer.squareup.com/reference/square/apple-pay-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-applepay.yaml)

### Square Sites API
The Sites API lets applications retrieve basic details about Square Online sites belonging to a seller, such as site ID, title, and domain. It is used in combination with the Snippets API.

**Human URL:** [https://developer.squareup.com/docs/sites-api/overview](https://developer.squareup.com/docs/sites-api/overview)

#### Tags:

 - Ecommerce, Sites, Square Online

#### Properties

- [Documentation](https://developer.squareup.com/docs/sites-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/sites-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-sites.yaml)

### Square Snippets API
The Snippets API lets applications add custom scripts to a Square Online site. Snippets can run as modals, pop ups, or background jobs, offering a range of functionality to extend Square Online features.

**Human URL:** [https://developer.squareup.com/docs/snippets-api/overview](https://developer.squareup.com/docs/snippets-api/overview)

#### Tags:

 - Ecommerce, Snippets, Square Online

#### Properties

- [Documentation](https://developer.squareup.com/docs/snippets-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/snippets-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-snippets.yaml)

### Square OAuth API
The OAuth API lets applications obtain and manage access tokens that grant scoped, permissioned access to a seller's Square account, supporting the authorization code grant flow, token refresh, and token revocation for connecting third-party apps.

**Human URL:** [https://developer.squareup.com/docs/oauth-api/overview](https://developer.squareup.com/docs/oauth-api/overview)

#### Tags:

 - Authentication, OAuth, Security

#### Properties

- [Documentation](https://developer.squareup.com/docs/oauth-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/oauth-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-oauth.yaml)

### Square Webhook Subscriptions API
The Webhook Subscriptions API lets applications programmatically create and manage webhook subscriptions to receive real-time event notifications for changes to payments, orders, customers, inventory, and other Square resources.

**Human URL:** [https://developer.squareup.com/docs/webhooks/overview](https://developer.squareup.com/docs/webhooks/overview)

#### Tags:

 - Events, Notifications, Webhooks

#### Properties

- [Documentation](https://developer.squareup.com/docs/webhooks/overview)
- [APIReference](https://developer.squareup.com/reference/square/webhook-subscriptions-api)
- [OpenAPI](openapi/square-openapi.yml)
- [AsyncAPI](asyncapi/square-webhooks-asyncapi.yml)
- [NaftikoCapability](capabilities/square-webhooksubscriptions.yaml)

### Square Events API
The Events API lets applications search and retrieve the history of events that have occurred in a seller's Square account, providing an audit trail and the ability to replay or backfill webhook-style event data.

**Human URL:** [https://developer.squareup.com/docs/events-api/overview](https://developer.squareup.com/docs/events-api/overview)

#### Tags:

 - Audit, Events, Webhooks

#### Properties

- [Documentation](https://developer.squareup.com/docs/events-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/events-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-events.yaml)

### Square Devices API
The Devices API lets applications create device codes to pair Square hardware such as Square Terminal and Square Register, and retrieve device details for managing point-of-sale devices.

**Human URL:** [https://developer.squareup.com/docs/devices-api/overview](https://developer.squareup.com/docs/devices-api/overview)

#### Tags:

 - Devices, Point of Sale, Terminal

#### Properties

- [Documentation](https://developer.squareup.com/docs/devices-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/devices-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-devices.yaml)

### Square Customer Groups API
The Customer Groups API lets applications create and manage groups of customers, enabling segmentation for targeted marketing, pricing rules, and loyalty programs.

**Human URL:** [https://developer.squareup.com/docs/customer-groups-api/what-it-does](https://developer.squareup.com/docs/customer-groups-api/what-it-does)

#### Tags:

 - CRM, Customer Groups, Customers

#### Properties

- [Documentation](https://developer.squareup.com/docs/customer-groups-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/customer-groups-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-customergroups.yaml)

### Square Customer Segments API
The Customer Segments API lets applications retrieve the smart, automatically maintained customer segments defined in a seller's Square Customer Directory, supporting targeted engagement based on buyer behavior.

**Human URL:** [https://developer.squareup.com/docs/customer-segments-api/what-it-does](https://developer.squareup.com/docs/customer-segments-api/what-it-does)

#### Tags:

 - CRM, Customer Segments, Customers

#### Properties

- [Documentation](https://developer.squareup.com/docs/customer-segments-api/what-it-does)
- [APIReference](https://developer.squareup.com/reference/square/customer-segments-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-customersegments.yaml)

### Square Gift Card Activities API
The Gift Card Activities API lets applications create and list gift card activities such as activating, loading, redeeming, adjusting, and refunding balances, providing a full ledger of gift card transactions.

**Human URL:** [https://developer.squareup.com/docs/gift-cards/using-gift-card-activities-api](https://developer.squareup.com/docs/gift-cards/using-gift-card-activities-api)

#### Tags:

 - Customer Engagement, Gift Cards, Transactions

#### Properties

- [Documentation](https://developer.squareup.com/docs/gift-cards/using-gift-card-activities-api)
- [APIReference](https://developer.squareup.com/reference/square/gift-card-activities-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-giftcardactivities.yaml)

### Square Custom Attributes API
The Custom Attributes APIs let applications define and attach custom metadata to core Square resources, including customers, orders, bookings, merchants, and locations, enabling tailored data models and integrations on top of the Square platform.

**Human URL:** [https://developer.squareup.com/docs/customer-custom-attributes-api/overview](https://developer.squareup.com/docs/customer-custom-attributes-api/overview)

#### Tags:

 - Custom Attributes, Extensibility, Metadata

#### Properties

- [Documentation](https://developer.squareup.com/docs/customer-custom-attributes-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/customer-custom-attributes-api)
- [OpenAPI](openapi/square-openapi.yml)
- [NaftikoCapability](capabilities/square-bookingcustomattributes.yaml)
- [NaftikoCapability](capabilities/square-customercustomattributes.yaml)
- [NaftikoCapability](capabilities/square-locationcustomattributes.yaml)
- [NaftikoCapability](capabilities/square-merchantcustomattributes.yaml)
- [NaftikoCapability](capabilities/square-ordercustomattributes.yaml)

### Square Reporting API
The Reporting API (Beta) provides a new way to access all of a business's data to build custom reports and integrations, surfacing sales, payments, and operational metrics across a seller's Square account.

**Human URL:** [https://developer.squareup.com/docs/reporting-api](https://developer.squareup.com/docs/reporting-api)

#### Tags:

 - Analytics, Business Intelligence, Reporting

#### Properties

- [Documentation](https://developer.squareup.com/docs/reporting-api)
- [APIReference](https://developer.squareup.com/reference/square/reporting-api)

### Square Channels API
The Channels API lets applications represent and manage the sales channels through which a seller transacts, enabling attribution of orders and payments to specific online or in-person channels.

**Human URL:** [https://developer.squareup.com/docs/channels-api/overview](https://developer.squareup.com/docs/channels-api/overview)

#### Tags:

 - Commerce, Omnichannel, Sales Channels

#### Properties

- [Documentation](https://developer.squareup.com/docs/channels-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/channels-api)

### Square Transfer Orders API
The Transfer Orders API lets applications create and manage transfers of inventory stock between a seller's locations, supporting multi-location retail and restaurant operations.

**Human URL:** [https://developer.squareup.com/docs/transfer-orders-api/overview](https://developer.squareup.com/docs/transfer-orders-api/overview)

#### Tags:

 - Commerce, Inventory, Transfer Orders

#### Properties

- [Documentation](https://developer.squareup.com/docs/transfer-orders-api/overview)
- [APIReference](https://developer.squareup.com/reference/square/transfer-orders-api)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/joinsquare)
- [Portal](https://developer.squareup.com/us/en)
- [Documentation](https://developer.squareup.com/docs)
- [APIReference](https://developer.squareup.com/reference/square)
- [GettingStarted](https://developer.squareup.com/docs/square-get-started)
- [Authentication](https://developer.squareup.com/docs/oauth-api/overview)
- [ChangeLog](https://developer.squareup.com/docs/changelog/connect)
- [SDKs](https://developer.squareup.com/docs/sdks)
- [SDK](https://developer.squareup.com/docs/devtools/postman)
- [Webhooks](https://developer.squareup.com/docs/webhooks/webhook-subscriptions-api)
- [AsyncAPI](asyncapi/square-webhooks-asyncapi.yml)
- [Sandbox](https://developer.squareup.com/docs/devtools/sandbox/overview)
- [RateLimits](https://developer.squareup.com/docs/build-basics/api-rate-limits)
- [Documentation](https://developer.squareup.com/docs/build-basics/api-lifecycle)
- [GettingStarted](https://developer.squareup.com/docs/buildbasics)
- [Documentation](https://developer.squareup.com/docs/development-essentials)
- [Console](https://developer.squareup.com/explorer/square)
- [Console](https://developer.squareup.com/docs/devtools/developer-dashboard)
- [SignUp](https://developer.squareup.com/apps)
- [Blog](https://developer.squareup.com/blog/)
- [Support](https://developer.squareup.com/forums/)
- [Pricing](https://squareup.com/us/en/pricing)
- [TermsOfService](https://squareup.com/us/en/legal/general/ua)
- [PrivacyPolicy](https://squareup.com/us/en/legal/general/privacy)
- [Support](https://squareup.com/help/us/en)
- [Partners](https://squareup.com/us/en/partnerships)
- [StatusPage](https://www.issquareup.com/)
- [GitHubOrganization](https://github.com/square)
- [OpenAPI](https://github.com/square/connect-api-specification)
- [StackOverflow](https://stackoverflow.com/questions/tagged/square-connect)
- [X](https://x.com/SquareDev)
- [Support](https://discord.com/invite/squaredev)
- [JSONSchema](json-schema/payment.json)
- [JSONSchema](json-schema/money.json)
- [JSONSchema](json-schema/order.json)
- [JSONSchema](json-schema/catalog-item.json)
- [JSONSchema](json-schema/customer.json)
- [JSONSchema](json-schema/location.json)
- [JSONSchema](json-schema/subscription.json)
- [JSONLD](json-ld/square-context.jsonld)
- [Square Python SDK (SDK)](https://github.com/square/square-python-sdk)
- [Square Node.js SDK (SDK)](https://github.com/square/square-nodejs-sdk)
- [Square Java SDK (SDK)](https://github.com/square/square-java-sdk)
- [Square .NET SDK (SDK)](https://github.com/square/square-dotnet-sdk)
- [Square Ruby SDK (SDK)](https://github.com/square/square-ruby-sdk)
- [Square PHP SDK (SDK)](https://github.com/square/square-php-sdk)
- [Square Go SDK (SDK)](https://github.com/square/square-go-sdk)
- [Square Web SDK (SDK)](https://github.com/square/web-sdk)
- [Square Web Payments SDK Quickstart (CodeExamples)](https://github.com/square/web-payments-quickstart)
- [Square Mobile Payments SDK (iOS) (SDK)](https://github.com/square/mobile-payments-sdk-ios)
- [Square Mobile Payments SDK (Android) (SDK)](https://github.com/square/mobile-payments-sdk-android)
- [Square Mobile Payments SDK (Flutter) (SDK)](https://github.com/square/mobile-payments-sdk-flutter)
- [Square Mobile Payments SDK (React Native) (SDK)](https://github.com/square/mobile-payments-sdk-react-native)
- [Square In-App Payments React Native Plugin (SDK)](https://github.com/square/in-app-payments-react-native-plugin)
- [Square In-App Payments Quickstart (iOS) (CodeExamples)](https://github.com/square/in-app-payments-ios-quickstart)
- [Square In-App Payments Quickstart (Android) (CodeExamples)](https://github.com/square/in-app-payments-android-quickstart)
- [Connect API Specification (OpenAPI)](https://github.com/square/connect-api-specification)
- [Rules](rules/square-spectral-rules.yml)
- [Vocabulary](vocabulary/square-vocabulary.yaml)
- [MCP Server (MCPServer)](https://github.com/square/square-mcp-server)
- [MCP Server (Tools)](https://github.com/square/square-mcp-server)
- [Remote MCP Server (Hosted) (Tools)](https://mcp.squareup.com/sse)
- [MCP Server Documentation (Documentation)](https://developer.squareup.com/docs/mcp)
- [MCP Server (npm) (SDK)](https://www.npmjs.com/package/square-mcp-server)
- [LLMsTxt](https://developer.squareup.com/llms.txt)
- [JSONStructure](json-structure/catalog-item-structure.json)
- [JSONStructure](json-structure/customer-structure.json)
- [JSONStructure](json-structure/location-structure.json)
- [JSONStructure](json-structure/money-structure.json)
- [JSONStructure](json-structure/order-structure.json)
- [JSONStructure](json-structure/payment-structure.json)
- [JSONStructure](json-structure/subscription-structure.json)
- [Example](examples/catalog-item-example.json)
- [Example](examples/customer-example.json)
- [Example](examples/location-example.json)
- [Example](examples/money-example.json)
- [Example](examples/order-example.json)
- [Example](examples/payment-example.json)
- [Example](examples/subscription-example.json)
- [Plans](plans/square-plans-pricing.yml)
- [RateLimits](rate-limits/square-rate-limits.yml)
- [FinOps](finops/square-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Tap/dip/swipe: 2.6%+15¢ Free, 2.5%+15¢ Plus, 2.4%+15¢ Premium |  |
| Online (Square site): 3.3%+30¢ Free, 2.9%+30¢ Plus/Premium |  |
| Online API: 2.9%+30¢ all plans |  |
| Manual entry/card on file: 3.5%+15¢ all plans |  |
| ACH (invoice): 1% $1 min ($10 cap on Plus/Premium) |  |
| ACH (API): 1% $1 min, $5 cap |  |
| Afterpay BNPL: 6%+30¢ |  |
| Cash/check: free |  |
| Bitcoin: 0% until 2027 |  |
| International cards: +1.50% on top |  |
| Square Payments, POS, Online, Invoices, Subscriptions APIs |  |
| Square Reader/Stand/Terminal/Register hardware |  |
| Webhooks for transactions, customers, orders |  |
| OAuth 2.0 + Personal access tokens |  |
| Catalog API for items, categories, taxes, modifiers |  |
| Customer Directory API |  |

## Use Cases

| Name | Description |
|------|-------------|
| Accept Payments Online |  |
| Build Custom POS Systems |  |
| Manage Product Catalogs |  |
| Track Inventory Across Locations |  |
| Create Loyalty and Rewards Programs |  |
| Send and Manage Invoices |  |
| Schedule Appointments and Bookings |  |
| Manage Team Members and Labor |  |
| Process Refunds and Disputes |  |
| Sell Gift Cards |  |
| Set Up Recurring Subscriptions |  |

## Integrations

| Name | Description |
|------|-------------|
| Apple Pay |  |
| Google Pay |  |
| Cash App Pay |  |
| Afterpay |  |
| QuickBooks |  |
| WooCommerce |  |
| Wix |  |
| BigCommerce |  |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [square-openapi.yml](openapi/square-openapi.yml)

### AsyncAPI

- [square-webhooks-asyncapi.yml](asyncapi/square-webhooks-asyncapi.yml)

### JSON Schema

- [catalog-item.json](json-schema/catalog-item.json)
- [customer.json](json-schema/customer.json)
- [location.json](json-schema/location.json)
- [money.json](json-schema/money.json)
- [order.json](json-schema/order.json)
- [payment.json](json-schema/payment.json)
- [subscription.json](json-schema/subscription.json)

### JSON Structure

- [catalog-item-structure.json](json-structure/catalog-item-structure.json)
- [customer-structure.json](json-structure/customer-structure.json)
- [location-structure.json](json-structure/location-structure.json)
- [money-structure.json](json-structure/money-structure.json)
- [order-structure.json](json-structure/order-structure.json)
- [payment-structure.json](json-structure/payment-structure.json)
- [subscription-structure.json](json-structure/subscription-structure.json)

### JSON-LD

- [square-context.jsonld](json-ld/square-context.jsonld)

### Examples

- [catalog-item-example.json](examples/catalog-item-example.json)
- [customer-example.json](examples/customer-example.json)
- [location-example.json](examples/location-example.json)
- [money-example.json](examples/money-example.json)
- [order-example.json](examples/order-example.json)
- [payment-example.json](examples/payment-example.json)
- [subscription-example.json](examples/subscription-example.json)

### Plans & Pricing

- [square-plans-pricing.yml](plans/square-plans-pricing.yml)

### Rate Limits

- [square-rate-limits.yml](rate-limits/square-rate-limits.yml)

### FinOps

- [square-finops.yml](finops/square-finops.yml)

## Naftiko Capabilities

Self-contained Naftiko capabilities, one per Square business surface (OpenAPI tag). Each file inlines its upstream consumes block plus REST and MCP exposers.

### Square Payments API

- [square-mobileauthorization.yaml](capabilities/square-mobileauthorization.yaml) — 1 operations
- [square-payments.yaml](capabilities/square-payments.yaml) — 7 operations

### Square Orders API

- [square-orders.yaml](capabilities/square-orders.yaml) — 8 operations
- [square-transactions.yaml](capabilities/square-transactions.yaml) — 4 operations
- [square-v1transactions.yaml](capabilities/square-v1transactions.yaml) — 3 operations

### Square Catalog API

- [square-catalog.yaml](capabilities/square-catalog.yaml) — 14 operations

### Square Inventory API

- [square-inventory.yaml](capabilities/square-inventory.yaml) — 13 operations

### Square Customers API

- [square-customers.yaml](capabilities/square-customers.yaml) — 14 operations

### Square Locations API

- [square-locations.yaml](capabilities/square-locations.yaml) — 4 operations

### Square Team API

- [square-employees.yaml](capabilities/square-employees.yaml) — 2 operations
- [square-team.yaml](capabilities/square-team.yaml) — 12 operations

### Square Labor API

- [square-labor.yaml](capabilities/square-labor.yaml) — 16 operations

### Square Bookings API

- [square-bookings.yaml](capabilities/square-bookings.yaml) — 13 operations

### Square Loyalty API

- [square-loyalty.yaml](capabilities/square-loyalty.yaml) — 18 operations

### Square Gift Cards API

- [square-giftcards.yaml](capabilities/square-giftcards.yaml) — 7 operations

### Square Invoices API

- [square-invoices.yaml](capabilities/square-invoices.yaml) — 10 operations

### Square Subscriptions API

- [square-subscriptions.yaml](capabilities/square-subscriptions.yaml) — 12 operations

### Square Checkout API

- [square-checkout.yaml](capabilities/square-checkout.yaml) — 10 operations

### Square Terminal API

- [square-terminal.yaml](capabilities/square-terminal.yaml) — 15 operations

### Square Refunds API

- [square-refunds.yaml](capabilities/square-refunds.yaml) — 3 operations

### Square Disputes API

- [square-disputes.yaml](capabilities/square-disputes.yaml) — 9 operations

### Square Merchants API

- [square-merchants.yaml](capabilities/square-merchants.yaml) — 2 operations

### Square Cards API

- [square-cards.yaml](capabilities/square-cards.yaml) — 4 operations

### Square Vendors API

- [square-vendors.yaml](capabilities/square-vendors.yaml) — 7 operations

### Square Cash Drawers API

- [square-cashdrawers.yaml](capabilities/square-cashdrawers.yaml) — 3 operations

### Square Bank Accounts API

- [square-bankaccounts.yaml](capabilities/square-bankaccounts.yaml) — 3 operations

### Square Payouts API

- [square-payouts.yaml](capabilities/square-payouts.yaml) — 3 operations

### Square Apple Pay API

- [square-applepay.yaml](capabilities/square-applepay.yaml) — 1 operations

### Square Sites API

- [square-sites.yaml](capabilities/square-sites.yaml) — 1 operations

### Square Snippets API

- [square-snippets.yaml](capabilities/square-snippets.yaml) — 3 operations

### Square OAuth API

- [square-oauth.yaml](capabilities/square-oauth.yaml) — 3 operations

### Square Webhook Subscriptions API

- [square-webhooksubscriptions.yaml](capabilities/square-webhooksubscriptions.yaml) — 8 operations

### Square Events API

- [square-events.yaml](capabilities/square-events.yaml) — 4 operations

### Square Devices API

- [square-devices.yaml](capabilities/square-devices.yaml) — 5 operations

### Square Customer Groups API

- [square-customergroups.yaml](capabilities/square-customergroups.yaml) — 5 operations

### Square Customer Segments API

- [square-customersegments.yaml](capabilities/square-customersegments.yaml) — 2 operations

### Square Gift Card Activities API

- [square-giftcardactivities.yaml](capabilities/square-giftcardactivities.yaml) — 2 operations

### Square Custom Attributes API

- [square-bookingcustomattributes.yaml](capabilities/square-bookingcustomattributes.yaml) — 11 operations
- [square-customercustomattributes.yaml](capabilities/square-customercustomattributes.yaml) — 10 operations
- [square-locationcustomattributes.yaml](capabilities/square-locationcustomattributes.yaml) — 11 operations
- [square-merchantcustomattributes.yaml](capabilities/square-merchantcustomattributes.yaml) — 11 operations
- [square-ordercustomattributes.yaml](capabilities/square-ordercustomattributes.yaml) — 11 operations

## Vocabulary

- [Square Vocabulary](vocabulary/square-vocabulary.yaml) — Unified taxonomy mapping 42 resources, 42 actions, 42 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Square Spectral Ruleset](rules/square-spectral-rules.yml) — 28 rules enforcing Square Connect API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
