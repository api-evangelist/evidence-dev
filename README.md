# Evidence (evidence-dev)

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
