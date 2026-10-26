# Sail Biomedicines

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

Sail Biomedicines is a Cambridge, Massachusetts preclinical biotechnology company formed in
October 2023, when Flagship Pioneering merged **Laronde** (the legacy slug this repository is
filed under) and **Senda Biosciences**. It combines Laronde's Endless RNA (eRNA) circular-RNA
platform with Senda's programmable nanoparticle delivery chemistry and applies generative AI to
the combined dataset, targeting in vivo CAR-T for autoimmune disease. In July 2026 Johnson &
Johnson committed $785M up front plus up to $140M in milestones and took an exclusive option to
acquire the company for a further $2.58B.

## No API surface

Sail Biomedicines sells therapeutics, not software. Probed 2026-08-23, it publishes no API, no
SDK, no developer portal and no machine-readable specification:

- `www.sail.bio` is a 14-page WordPress marketing site on WP Engine. Every contract-discovery path
  — `/openapi.json`, `/openapi.yaml`, `/swagger.json`, `/v1/openapi.json`, `/api-docs`, `/docs`,
  `/redoc`, `/graphql`, `/llms.txt` — returns 404, as does every `/.well-known/` path including
  `agent-card.json` and `agent.json`. A random control path under `/.well-known/` returns the same
  404, so the host is not a soft-200 catch-all.
- `api.`, `docs.`, `dev.`, `developer.`, `data.`, `platform.`, `mcp.`, `app.`, `portal.`, `ir.` and
  `investors.sail.bio` are all NXDOMAIN.
- No first-party package exists on npm, PyPI, RubyGems or crates.io, and no GitHub organization
  was tied to the company.
- The one machine-readable surface on the domain is the stock WordPress core REST API at
  `/wp-json/` — the CMS behind a marketing site, not a product API, and not catalogued as a
  contract here.

Two neighbouring domains are recorded but excluded: `laronde.bio` (the pre-merger domain — still
resolves, but the TLS handshake fails) and `laronde.com` (a French-language site belonging to an
unrelated business).

## Artifacts

| Path | What it holds |
|---|---|
| `apis.yml` | APIs.json profile — identity, tags, links, coverage |
| `well-known/laronde-well-known.yml` | `/.well-known/` probe record (all misses) |
| `security/laronde-domain-security.yml` | TLS / HSTS / DNSSEC / CAA / SPF / DMARC probe |
| `packages/laronde-packages.yml` | Registry search — no first-party packages |
| `plans/laronde-plans-pricing.yml` | No API plans published |
| `rate-limits/laronde-rate-limits.yml` | No API rate limits published |
| `llms/laronde-llms.txt` | Generated `llms.txt` profile (not published by the company) |

- Website: https://www.sail.bio/
- Flagship Pioneering profile: https://www.flagshippioneering.com/companies/sail-biomedicines
- Secondary-market listing this entry was harvested from: https://forgeglobal.com/laronde_stock/
