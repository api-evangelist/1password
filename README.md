# 1Password (1password)
1Password is a password manager that helps individuals and businesses securely store and manage passwords, credentials, and sensitive information. The 1Password developer platform provides APIs for programmatic access to secrets, event monitoring, and partner billing management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Passwords, Password Manager, Security

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-03-24

## APIs

### 1Password Connect Server API
The 1Password Connect Server API provides secure access to 1Password items and vaults in your company's apps and cloud infrastructure through a private REST API. Connect Servers bridge the gap between 1Password and your infrastructure by enabling programmatic access to secrets stored in shared vaults. You can create, read, update, and delete items, manage vaults, and retrieve files attached to items.

**Human URL:** [https://developer.1password.com/docs/connect/api-reference/](https://developer.1password.com/docs/connect/api-reference/)


#### Tags:

 - Passwords, Secrets, Vaults, Items

#### Properties

- [Documentation](https://developer.1password.com/docs/connect/api-reference/)
- [OpenAPI](openapi/1password-connect-openapi.yml)

### 1Password Events API
The 1Password Events API provides programmatic access to event data generated within a 1Password account. It enables security teams and administrators to retrieve sign-in attempts, item usage records, and audit events for monitoring, compliance, and security analysis. The API uses cursor-based pagination with POST requests to efficiently stream large volumes of event data.

**Human URL:** [https://developer.1password.com/docs/events-api/reference/](https://developer.1password.com/docs/events-api/reference/)


#### Tags:

 - Events, Security, Audit, Monitoring

#### Properties

- [Documentation](https://developer.1password.com/docs/events-api/reference/)
- [OpenAPI](openapi/1password-events-openapi.yml)

### 1Password Partnership API
You can use the 1Password Partnership API to manage the provisioning and deprovisioning of third-party partner billing accounts for your customers. The API supports partner billing accounts for 1Password individual and family accounts. The Partnership API does not support 1Password team or business accounts.

**Human URL:** [https://developer.1password.com/docs/partnership-api/reference/](https://developer.1password.com/docs/partnership-api/reference/)


#### Tags:

 - Passwords, Billing, Partners

#### Properties

- [Documentation](https://developer.1password.com/docs/partnership-api/reference/)
- [OpenAPI](openapi/1password-partnership-openapi.yml)

## Common Properties

- [Website](https://1password.com/)
- [Portal](https://developer.1password.com/)
- [Documentation](https://developer.1password.com/docs/)
- [Getting Started](https://developer.1password.com/docs/get-started/)
- [Authentication](https://developer.1password.com/docs/connect/connect-api-reference/#authentication)
- [SDKs](https://developer.1password.com/docs/sdks/)
- [Blog](https://blog.1password.com/)
- [Support](https://support.1password.com/)
- [Privacy Policy](https://1password.com/legal/privacy/)
- [Terms of Service](https://1password.com/legal/terms-of-service/)
- [Sign Up](https://start.1password.com/sign-up/)
- [Login](https://my.1password.com/)
- [JSON-LD](json-ld/1password-context.jsonld)
- [JSONSchema](json-schema/1password-item-schema.json)
- [JSONSchema](json-schema/1password-event-schema.json)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
