# CoinGate

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
