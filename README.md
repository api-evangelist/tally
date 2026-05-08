# Tally (tally)

Tally is a Notion-style form and survey builder with unlimited forms and submissions on its Free plan. The Tally REST API is free across all plans, including Free.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Tally REST API** — `https://api.tally.so` — manage forms, fetch/delete submissions, webhooks. Bearer-token auth via API keys created from the dashboard. [Reference](https://developers.tally.so/api-reference/introduction).
- **Embed JS** — `https://tally.so/widgets/embed.js` — `Tally.openPopup`, `Tally.closePopup`, `Tally.loadEmbeds` plus event listeners.

## OpenAPI
Tally publishes interactive API reference at developers.tally.so but does not currently host a downloadable OpenAPI/Swagger document at a stable public URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
Forms, Surveys, No-Code, Free, Notion-style, Webhooks, MCP

## Common Properties
- [Website](https://tally.so/) · [Developer Docs](https://developers.tally.so/) · [Pricing](https://tally.so/pricing)
- [Plans](plans/tally-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/tally-rate-limits.yml) — partially reconciled (numeric per-second limit not public)
- [FinOps](finops/tally-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Free** — unlimited forms / submissions (fair use); core features.
- **Pro** — $24/mo; remove branding, custom domains, custom CSS, extended analytics.
- **Business** — $74/mo; data retention controls, email verification, 90-day version history.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
