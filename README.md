# Hasura (hasura)

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

We've spent years perfecting products that make it effortless to access and use data.PromptQL for AIAccurate AI by continuously learning the unique context of your business.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hasura/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hasura/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Access
- GraphQL

## Timestamps

- **Created:** 2025-06-10T00:00:00.000Z
- **Modified:** 2026-05-29

## APIs

### Hasura GraphQL API

The Hasura GraphQL Engine v2 provides instant realtime GraphQL APIs on your data with fine-grained access control. Supports GraphQL queries, mutations, and subscriptions at the /v1/graphql endpoint, along with RESTified GraphQL endpoints, Relay API, metadata API, schema API, config API, health check API, PG dump API, and explain API.

- **Human URL:** [https://hasura.io/docs/2.0/api-reference/graphql-api/index/](https://hasura.io/docs/2.0/api-reference/graphql-api/index/)

#### Tags

- GraphQL
- Mutations
- Queries
- Realtime
- Subscriptions

#### Properties

- [Documentation](https://hasura.io/docs/2.0/api-reference/graphql-api/index/)
- [API Reference](https://hasura.io/docs/2.0/api-reference/overview/)
- [Documentation](https://hasura.io/docs/2.0/api-reference/restified/)
- [Getting Started](https://hasura.io/docs/2.0/getting-started/overview/)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/hasura/refs/heads/main/asyncapi/hasura-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/hasura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hasura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hasura Metadata API

The Hasura Metadata API allows programmatic management of Hasura GraphQL Engine configuration. All requests are POST requests to the /v1/metadata endpoint, supporting operations for managing data sources, tables, relationships, permissions, remote schemas, actions, event triggers, and RESTified endpoints.

- **Human URL:** [https://hasura.io/docs/2.0/api-reference/metadata-api/index/](https://hasura.io/docs/2.0/api-reference/metadata-api/index/)

#### Tags

- Configuration
- Metadata
- Schema

#### Properties

- [Documentation](https://hasura.io/docs/2.0/api-reference/metadata-api/index/)
- [API Reference](https://hasura.io/docs/2.0/api-reference/overview/)
- [Postman Collection](collections/hasura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hasura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hasura DDN GraphQL API

The Hasura Data Delivery Network (DDN) is a metadata-driven API platform that generates instant GraphQL APIs on any data source. It provides queries, mutations, and subscriptions as root-level fields, with support for global IDs, API versioning, Apollo Federation, filtering, sorting, aggregation, and joins across multiple data connectors including PostgreSQL, MongoDB, ClickHouse, MySQL, Snowflake, Elasticsearch, and SQL Server.

- **Human URL:** [https://hasura.io/docs/3.0/graphql-api/overview/](https://hasura.io/docs/3.0/graphql-api/overview/)

#### Tags

- Data Delivery Network
- DDN
- GraphQL
- Realtime
- Supergraph

#### Properties

- [Documentation](https://hasura.io/docs/3.0/graphql-api/overview/)
- [Documentation](https://hasura.io/docs/3.0/index/)
- [Documentation](https://hasura.io/docs/3.0/graphql-api/mutations/)
- [Documentation](https://hasura.io/docs/3.0/graphql-api/subscriptions/)
- [Getting Started](https://hasura.io/docs/3.0/basics/)
- [C L I](https://hasura.io/docs/3.0/reference/cli/)
- [Installation](https://hasura.io/docs/3.0/reference/cli/installation/)
- [API Reference](https://hasura.io/docs/3.0/reference/metadata-reference/graphql-config/)
- [Postman Collection](collections/hasura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hasura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hasura Cloud API

The Hasura Cloud API provides a GraphQL endpoint at https://data.pro.hasura.io/v1/graphql to programmatically create and manage Hasura Cloud projects, tenants, collaborators, and configurations. Authentication uses Personal Access Tokens via the Authorization header.

- **Human URL:** [https://hasura.io/docs/2.0/api-reference/cloud-api-reference/](https://hasura.io/docs/2.0/api-reference/cloud-api-reference/)

#### Tags

- Cloud
- Management
- Projects

#### Properties

- [Documentation](https://hasura.io/docs/2.0/api-reference/cloud-api-reference/)
- [Documentation](https://hasura.io/docs/2.0/hasura-cloud/projects/index/)
- [Postman Collection](collections/hasura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hasura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PromptQL Natural Language API

The PromptQL Natural Language API allows interaction with Hasura PromptQL to send natural language messages and receive AI-powered responses with streaming support. It enables accurate AI by continuously learning the unique context of your business data, composing tool calls and LLM tasks for high explainability, accuracy, and repeatability. Available in v1 and v2 with Python and JavaScript SDKs.

- **Human URL:** [https://promptql.io/docs/promptql-apis/natural-language-api/](https://promptql.io/docs/promptql-apis/natural-language-api/)

#### Tags

- AI
- LLM
- Natural Language
- PromptQL

#### Properties

- [Documentation](https://promptql.io/docs/promptql-apis/natural-language-api/)
- [Documentation](https://promptql.io/docs/promptql-apis/execute-program-api/)
- [Documentation](https://hasura.io/docs/promptql/index/)
- [Getting Started](https://hasura.io/docs/promptql/quickstart/)
- [Python S D K](https://github.com/hasura/promptql-python-sdk)
- [Node S D K](https://www.npmjs.com/package/@hasura/promptql)
- [Postman Collection](collections/hasura.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hasura.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/hasura)
- [Website](https://hasura.io/)
- [Plans](https://hasura.io/pricing)
- [Use Cases](https://hasura.io/docs/2.0/getting-started/use-case/overview/)
- [Authentication](https://hasura.io/docs/2.0/auth/overview/)
- [Getting Started](https://hasura.io/docs/2.0/getting-started/overview/)
- [Getting Started](https://hasura.io/docs/2.0/getting-started/overview/)
- [Security](https://hasura.io/docs/2.0/security/overview/)
- [C L I](https://hasura.io/docs/2.0/hasura-cli/overview/)
- [C I/ C D](https://hasura.io/docs/2.0/cloud-ci-cd/index/)
- [Support](https://hasura.io/docs/2.0/get-support/)
- [F A Q](https://hasura.io/docs/2.0/faq/index/)
- [Discord](https://discord.com/invite/hasura)
- [Glossary](https://hasura.io/docs/2.0/glossary/index/)
- [Blog](https://hasura.io/blog)
- [Pricing](https://hasura.io/pricing)
- [Customers](https://hasura.io/customers)
- [Webinars](https://hasura.io/events?category=Webinar#wall-section)
- [Hub](https://hasura.io/graphql/)
- [Events](https://hasura.io/events)
- [White Papers](https://hasura.io/resources)
- [Login](https://cloud.hasura.io/signup)
- [Sign Up](https://cloud.hasura.io/signup/new_user)
- [Terms of Service](https://hasura.io/legal/hasura-cloud-terms-of-service)
- [Integrations](https://hasura.io/connectors#connectors-list)
- [Tutorials](https://hasura.io/learn/)
- [F A Q](https://hasura.io/learn/#learn-faq)
- [Features](undefined)
- [Features](undefined)
- [About Page](https://hasura.io/about/)
- [Status Page](https://status.hasura.io/)
- [Changelog](https://hasura.io/changelog)
- [GitHub Repository](https://github.com/hasura/graphql-engine)
- [Git Hub Discussions](https://github.com/hasura/graphql-engine/discussions)
- [Git Hub Releases](https://github.com/hasura/graphql-engine/releases)
- [Twitter](https://twitter.com/hasurahq)
- [LinkedIn](https://www.linkedin.com/company/hasura/)
- [YouTube](https://www.youtube.com/channel/UCZo1ciR8pZvdD3Wxp9aSNhQ)
- [Reddit](https://www.reddit.com/r/Hasura/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/hasura)
- [Privacy Policy](https://hasura.io/legal/hasura-privacy-policy)
- [Terms Of Use](https://hasura.io/legal/website-terms-of-use)
- [Contact](https://hasura.io/contact-us)
- [Help](https://hasura.io/help/)
- [Community](https://hasura.io/community)
- [Product Page](https://hasura.io/ddn)
- [API Reference](https://hasura.io/docs/2.0/api-reference/overview/)
- [Documentation](https://hasura.io/docs/3.0/index/)
- [Case Studies](https://hasura.io/user-stories/)
- [Legal](https://hasura.io/legal)
- [Release Notes](https://hasura.io/docs/2.0/enterprise/release-notes/)
- [Product Page](https://hasura.io/learn-more)
- [M C P Server](https://github.com/hasura/promptql-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
