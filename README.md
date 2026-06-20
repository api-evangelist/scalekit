# Scalekit (scalekit)

Scalekit is the authentication platform for B2B SaaS and AI agents. It provides drop-in enterprise Single Sign-On (SAML/OIDC), SCIM directory provisioning, social login, full-stack user management, machine-to-machine (M2M) auth, and agent / MCP authentication with connected accounts and tool execution - all exposed through a per-environment REST API secured with OAuth 2.0 client credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scalekit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scalekit/refs/heads/main/apis.yml)

## Tags

- Authentication
- SSO
- SCIM
- Identity
- B2B SaaS
- Agent Auth

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Scalekit SSO Connections API

Configure and manage enterprise Single Sign-On connections (SAML and OIDC) per organization, list connections, and retrieve connection status and configuration details.

- **Human URL:** [https://docs.scalekit.com/apis/](https://docs.scalekit.com/apis/)
- **Base URL:** `https://{environment}.scalekit.com`

#### Tags

- SSO
- SAML
- OIDC
- Connections

#### Properties

- [Documentation](https://docs.scalekit.com/sso/quickstart/)
- [API Reference](https://docs.scalekit.com/apis/)
- [OpenAPI](openapi/scalekit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalekit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalekit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalekit Organizations API

Create, read, update, and delete tenant organizations, toggle per-organization feature settings, and generate self-service admin portal links for SSO and SCIM configuration.

- **Human URL:** [https://docs.scalekit.com/apis/](https://docs.scalekit.com/apis/)
- **Base URL:** `https://{environment}.scalekit.com`

#### Tags

- Organizations
- Tenants
- Admin Portal

#### Properties

- [Documentation](https://docs.scalekit.com/m2m/quickstart/)
- [API Reference](https://docs.scalekit.com/apis/)
- [OpenAPI](openapi/scalekit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalekit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalekit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalekit Directory / SCIM API

List directories, fetch SCIM-provisioned directory users and groups on demand, and keep application user data in sync with the customer's upstream identity provider.

- **Human URL:** [https://docs.scalekit.com/directory/scim/quickstart/](https://docs.scalekit.com/directory/scim/quickstart/)
- **Base URL:** `https://{environment}.scalekit.com`

#### Tags

- SCIM
- Directory
- Provisioning

#### Properties

- [Documentation](https://docs.scalekit.com/directory/scim/quickstart/)
- [API Reference](https://docs.scalekit.com/apis/)
- [OpenAPI](openapi/scalekit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalekit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalekit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalekit Users & Memberships API

Manage the organization user membership lifecycle - add, update, and remove members, resend invitations, and create and list organization roles and permissions.

- **Human URL:** [https://docs.scalekit.com/apis/](https://docs.scalekit.com/apis/)
- **Base URL:** `https://{environment}.scalekit.com`

#### Tags

- Users
- Memberships
- Roles

#### Properties

- [Documentation](https://docs.scalekit.com/fsa/quickstart/)
- [API Reference](https://docs.scalekit.com/apis/)
- [OpenAPI](openapi/scalekit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalekit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalekit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalekit Agent / M2M Auth API

Authenticate AI agents and machine-to-machine clients via OAuth 2.0 client credentials, manage connected accounts for third-party connectors (OAuth/API key), generate authorization magic links, and execute tools on behalf of users for MCP and agent workflows.

- **Human URL:** [https://docs.scalekit.com/agent-auth/](https://docs.scalekit.com/agent-auth/)
- **Base URL:** `https://{environment}.scalekit.com`

#### Tags

- Agent Auth
- M2M
- MCP
- Connected Accounts

#### Properties

- [Documentation](https://docs.scalekit.com/agent-auth/)
- [API Reference](https://docs.scalekit.com/apis/)
- [OpenAPI](openapi/scalekit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalekit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalekit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/scalekit-inc)
- [LinkedIn](https://www.linkedin.com/company/scalekit)
- [Website](https://www.scalekit.com)
- [Documentation](https://docs.scalekit.com)
- [Plans](plans/scalekit-plans-pricing.yml)
- [Rate Limits](rate-limits/scalekit-rate-limits.yml)
- [Fin Ops](finops/scalekit-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
