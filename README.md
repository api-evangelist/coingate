# CoinGate

CoinGate is a cryptocurrency payment gateway providing REST APIs for creating and
managing payment orders, processing crypto-to-fiat conversions, automating payouts,
managing merchant ledger accounts, and accessing billing and reporting data. Merchants
can accept 70+ cryptocurrencies and settle in fiat (EUR, USD, GBP) or crypto, with
integrations available via hosted checkout, plugins, and direct API.

## API

- **Base URL (Production):** https://api.coingate.com/v2
- **Base URL (Sandbox):** https://api-sandbox.coingate.com/v2
- **API Version:** v2
- **Developer Portal:** https://developer.coingate.com
- **API Reference:** https://developer.coingate.com/reference/cryptocurrency-payment-api
- **Changelog:** https://developer.coingate.com/changelog

## Authentication

All private API endpoints require a Bearer Token. Tokens are generated from the
CoinGate merchant dashboard at https://coingate.com. Sandbox environments require
separate credentials generated at https://sandbox.coingate.com.

Public endpoints (exchange rates, currencies, ping, IP addresses, platforms, supported
countries) do not require authentication.

## Key API Areas

- **Orders:** Create, retrieve, list, and checkout payment orders
- **Refunds:** Create and manage order refunds
- **Conversions:** Convert currencies directly from ledger accounts
- **Payouts / Send Requests:** Automate outbound fund transfers
- **Ledger:** Access merchant account and transaction history
- **Withdrawals:** Manage withdrawals to bank or crypto wallets
- **Billing:** Recurring billing, products, contacts
- **Payment Channels:** Crypto address management
- **Public:** Exchange rates, currencies, platform info

## SDKs

| Language | Repository |
|----------|-----------|
| Python   | https://github.com/coingate/coingate-python |
| PHP      | https://github.com/coingate/coingate-php |
| Node.js  | https://github.com/coingate/coingate-node |
| Ruby     | https://github.com/coingate/coingate-ruby |

## Pricing

- **Standard:** 1% per transaction, no monthly fee
- **Enterprise:** Custom volume-based rates

Full pricing details: https://coingate.com/pricing

## Links

- [Website](https://coingate.com)
- [Developer Portal](https://developer.coingate.com)
- [Pricing](https://coingate.com/pricing)
- [Blog](https://coingate.com/blog)
- [GitHub](https://github.com/coingate)
- [Help Center](https://support.coingate.com)
- [Sign Up](https://coingate.com/register)
