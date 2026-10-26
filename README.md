# Scalekit (scalekit)

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
