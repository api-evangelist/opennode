# OpenNode

OpenNode is a Bitcoin and Lightning Network payment processor providing a REST API for businesses and developers to accept Bitcoin payments, create payment charges, manage Lightning Network invoices, process on-chain transactions, handle webhooks for real-time payment notifications, initiate Bitcoin withdrawals and payouts, and access payment analytics.

**Website:** [https://opennode.com](https://opennode.com)  
**Developer Docs:** [https://developers.opennode.com](https://developers.opennode.com)  
**API Reference:** [https://developers.opennode.com/reference](https://developers.opennode.com/reference)  
**Status:** [https://status.opennode.com](https://status.opennode.com)

## APIs

- **Charges API** — Create and manage Bitcoin payment charges (on-chain and Lightning Network)
- **Withdrawals API** — Initiate Bitcoin withdrawals and payouts to on-chain addresses or Lightning invoices
- **Refunds API** — Create and manage refunds for processed charges
- **Exchanges API** — Initiate Bitcoin currency exchange operations
- **Account API** — Retrieve account balance, activity, and manage bank withdrawal schedules
- **Static Addresses API** — Create static on-chain addresses and Lightning addresses via LNURL-Pay
- **Rates and Currencies API** — Retrieve real-time Bitcoin exchange rates and supported currencies

## Authentication

API key authentication via the `Authorization` header. Keys are managed at [app.opennode.com/developers/integrations](https://app.opennode.com/developers/integrations). Separate keys required for development (testnet) and production.

## Base URLs

- **Production:** `https://api.opennode.com`
- **Development:** `https://app.dev.opennode.com`

## Resources

- [plans/opennode-plans-pricing.yml](plans/opennode-plans-pricing.yml)
- [rate-limits/opennode-rate-limits.yml](rate-limits/opennode-rate-limits.yml)
- [finops/opennode-finops.yml](finops/opennode-finops.yml)
