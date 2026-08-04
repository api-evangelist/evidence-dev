# Evidence (evidence-dev)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Evidence is an open-source (MIT) business-intelligence-as-code framework that turns SQL queries plus Markdown into fast, version-controlled static data apps and dashboards. It is built on Svelte/Vite, runs queries through a DuckDB-WASM "Universal SQL" engine, and is consumed as a framework/CLI rather than a hosted REST API. Evidence Cloud adds managed hosting, a managed query engine, scheduled data syncs, and AI authoring assistance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/evidence-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/evidence-dev/refs/heads/main/apis.yml)

## Tags

- Business Intelligence
- BI as Code
- SQL
- Markdown
- Data Apps
- Open Source

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

> Note: Evidence's "interface" is a framework/CLI plus SQL against your data sources. It is a build tool that compiles SQL + Markdown into a static data app - not a hosted REST API. The surfaces below are documented as framework/query-layer/product surfaces, not network endpoints.

### Evidence Framework (SQL + Markdown)

The open-source core. SQL statements embedded in Markdown files run against configured data sources and render charts and components into a static BI website (Svelte/Vite). The interface is a Node CLI (dev, build, preview, sources) plus authored Markdown - not a hosted REST API.

- **Human URL:** [https://docs.evidence.dev/](https://docs.evidence.dev/)

#### Tags

- Framework
- CLI
- SQL
- Markdown
- Static Site

#### Properties

- [Documentation](https://docs.evidence.dev/)
- [API Reference](https://docs.evidence.dev/reference/cli)
- [GitHub](https://github.com/evidence-dev/evidence)
- [OpenAPI](openapi/evidence-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evidence-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evidence-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evidence USQL / Query Layer

Universal SQL, the query engine built into Evidence core and powered by DuckDB's WebAssembly distribution. It extracts data sources to Parquet and lets you query across multiple sources with a single SQL dialect via an open data-source-adapter standard. Consumed in-process through SQL, not via a network REST endpoint.

- **Human URL:** [https://evidence.dev/universal-sql](https://evidence.dev/universal-sql)

#### Tags

- USQL
- DuckDB
- Query Engine
- Parquet

#### Properties

- [Documentation](https://evidence.dev/universal-sql)
- [API Reference](https://docs.evidence.dev/core-concepts/data-sources/duckdb)
- [GitHub](https://github.com/evidence-dev/evidence)
- [OpenAPI](openapi/evidence-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evidence-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evidence-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evidence Cloud

The managed hosting and deployment platform for Evidence projects. Adds a managed query engine, multi-level caching, row-level security, scheduled data syncs, a browser-based IDE, and AI authoring assistance. Surfaced as a managed product/control-plane, not a documented public REST API for end users.

- **Human URL:** [https://evidence.dev/cloud](https://evidence.dev/cloud)

#### Tags

- Cloud
- Managed Hosting
- Deployment
- AI

#### Properties

- [Documentation](https://docs.evidence.dev/deployment/evidence-cloud/)
- [API Reference](https://evidence.dev/pricing)
- [GitHub](https://github.com/evidence-dev)
- [OpenAPI](openapi/evidence-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evidence-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evidence-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/evidence-dev)
- [LinkedIn](https://www.linkedin.com/company/evidence-dev)
- [Website](https://evidence.dev/)
- [Documentation](https://docs.evidence.dev/)
- [Plans](plans/evidence-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/evidence-dev-rate-limits.yml)
- [Fin Ops](finops/evidence-dev-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
