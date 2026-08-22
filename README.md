# Tally (tally)

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

Tally is a Notion-style form and survey builder offering unlimited forms and submissions on its free plan. The Tally API exposes forms, submissions and webhooks programmatically and is free to use across all plans (including Free). Tally also publishes a JS embed library and an MCP server for AI integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tally/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tally/refs/heads/main/apis.yml)

## Tags

- Forms
- Surveys
- No-Code
- Free
- Notion-style
- Webhooks
- MCP

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Tally REST API

REST API for managing forms and fetching/deleting submissions. Bearer token auth using API keys created from the workspace dashboard. Free on every Tally plan including the Free tier.

- **Human URL:** [https://developers.tally.so/](https://developers.tally.so/)
- **Base URL:** `https://api.tally.so`

#### Tags

- REST
- Forms
- Submissions
- Webhooks

#### Properties

- [Documentation](https://developers.tally.so/)
- [API Reference](https://developers.tally.so/api-reference/introduction)
- [Authentication](https://developers.tally.so/api-reference/authentication)
- [Webhooks](https://tally.so/help/webhooks)
- [Postman Collection](collections/tally.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tally.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tally Embed JS

JavaScript embed library exposing Tally.openPopup, Tally.closePopup, Tally.loadEmbeds and event listeners for form load, page view, submission and popup close.

- **Human URL:** [https://tally.so/help/developer-resources](https://tally.so/help/developer-resources)
- **Base URL:** `https://tally.so/widgets/embed.js`

#### Tags

- SDK
- Embed
- JavaScript

#### Properties

- [Postman Collection](collections/tally.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tally.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/withtally)
- [LinkedIn](https://www.linkedin.com/company/meettally)
- [Website](https://tally.so/)
- [Documentation](https://developers.tally.so/)
- [Pricing](https://tally.so/pricing)
- [Help Center](https://tally.so/help)
- [Plans](plans/tally-plans-pricing.yml)
- [Rate Limits](rate-limits/tally-rate-limits.yml)
- [Fin Ops](finops/tally-finops.yml)
- [L L Ms Txt](https://tally.so/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
