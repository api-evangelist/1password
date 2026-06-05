# 1Password (1password)

1Password is a password manager that helps individuals and businesses securely store and manage passwords, credentials, and sensitive information. The platform provides a Connect Server API for programmatic secrets management, an Events API for security monitoring and audit logging, and a Partnership API for managing partner billing accounts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Password Manager
- Passwords
- Security
- Secrets

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### 1Password Connect Server API

The 1Password Connect Server API provides secure access to 1Password items and vaults in your company's apps and cloud infrastructure through a private REST API. Connect Servers bridge the gap between 1Password and your infrastructure by enabling programmatic access to secrets stored in shared vaults. You can create, read, update, and delete items, manage vaults, and retrieve files attached to items.

- **Human URL:** [https://developer.1password.com/docs/connect/api-reference/](https://developer.1password.com/docs/connect/api-reference/)
- **Base URL:** `http://localhost:8080`

#### Tags

- Items
- Passwords
- Secrets
- Vaults

#### Properties

- [Documentation](https://developer.1password.com/docs/connect/api-reference/)
- [OpenAPI](openapi/1password-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/1password-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/1password-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/1password-connect-vault-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/1password-connect-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/1password-connect-full-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/1password-connect-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### 1Password Events API

The 1Password Events API provides programmatic access to event data generated within a 1Password account. It enables security teams and administrators to retrieve sign-in attempts, item usage records, and audit events for monitoring, compliance, and security analysis. The API uses cursor-based pagination with POST requests to efficiently stream large volumes of event data.

- **Human URL:** [https://developer.1password.com/docs/events-api/reference/](https://developer.1password.com/docs/events-api/reference/)
- **Base URL:** `https://events.1password.com`

#### Tags

- Audit
- Events
- Monitoring
- Security

#### Properties

- [Documentation](https://developer.1password.com/docs/events-api/reference/)
- [OpenAPI](openapi/1password-events-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/1password-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/1password-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/1password-events-sign-in-attempt-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/1password-events-item-usage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/1password-events-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### 1Password Partnership API

You can use the 1Password Partnership API to manage the provisioning and deprovisioning of third-party partner billing accounts for your customers. The API supports partner billing accounts for 1Password individual and family accounts. The Partnership API does not support 1Password team or business accounts.

- **Human URL:** [https://developer.1password.com/docs/partnership-api/reference/](https://developer.1password.com/docs/partnership-api/reference/)
- **Base URL:** `https://billing.b5test.eu/api/v1`

#### Tags

- Billing
- Partners
- Passwords

#### Properties

- [Documentation](https://developer.1password.com/docs/partnership-api/reference/)
- [OpenAPI](openapi/1password-partnership-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/1password-partnership.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/1password-partnership.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/1password-partnership-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/1password)
- [Website](https://1password.com/)
- [Portal](https://developer.1password.com/)
- [Documentation](https://developer.1password.com/docs/)
- [Getting Started](https://developer.1password.com/docs/get-started/)
- [Authentication](https://developer.1password.com/docs/connect/connect-api-reference/#authentication)
- [SDK](https://developer.1password.com/docs/sdks/)
- [SDK](https://pypi.org/project/onepassword-sdk/)
- [SDK](https://www.npmjs.com/package/@1password/sdk)
- [SDK](https://pkg.go.dev/github.com/1Password/onepassword-sdk-go)
- [SDK](https://pypi.org/project/onepassword-connect-sdk/)
- [SDK](https://www.npmjs.com/package/@1password/connect)
- [SDK](https://pkg.go.dev/github.com/1Password/connect-sdk-go)
- [C L I](https://developer.1password.com/docs/cli/)
- [Blog](https://blog.1password.com/)
- [Support](https://support.1password.com/)
- [Privacy Policy](https://1password.com/legal/privacy/)
- [Terms of Service](https://1password.com/legal/terms-of-service/)
- [Sign Up](https://start.1password.com/sign-up/)
- [Changelog](https://developer.1password.com/docs/events-api/changelog/)
- [GitHub Organization](https://github.com/1Password)
- [Spectral Rules](rules/1password-spectral-rules.yml)
- [Vocabulary](vocabulary/1password-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
