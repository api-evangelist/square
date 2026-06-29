# Programmatic API Onboarding — Square

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Square: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`square-api-auth.mjs`](square-api-auth.mjs)
- Run `node square-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/09/04/square-oauth-dance-dashboard-app/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
