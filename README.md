# Hasura (hasura)

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
