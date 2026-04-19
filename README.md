# 1Password (1password)
1Password is a password manager that helps individuals and businesses securely store and manage passwords, credentials, and sensitive information. The platform provides a Connect Server API for programmatic secrets management, an Events API for security monitoring and audit logging, and a Partnership API for managing partner billing accounts.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Password Manager, Passwords, Security, Secrets

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-04-19

## APIs

### 1Password Connect Server API
The 1Password Connect Server API provides secure access to 1Password items and vaults in your company's apps and cloud infrastructure through a private REST API. Connect Servers bridge the gap between 1Password and your infrastructure by enabling programmatic access to secrets stored in shared vaults.

**Human URL:** [https://developer.1password.com/docs/connect/api-reference/](https://developer.1password.com/docs/connect/api-reference/)

#### Tags:

 - Items, Passwords, Secrets, Vaults

#### Properties

- [Documentation](https://developer.1password.com/docs/connect/api-reference/)
- [OpenAPI](openapi/1password-connect-openapi.yml)
- [JSONSchema](json-schema/1password-connect-vault-schema.json)
- [JSONSchema](json-schema/1password-connect-item-schema.json)
- [JSON-LD](json-ld/1password-connect-context.jsonld)

### 1Password Events API
The 1Password Events API provides programmatic access to event data generated within a 1Password account. It enables security teams and administrators to retrieve sign-in attempts, item usage records, and audit events for monitoring, compliance, and security analysis.

**Human URL:** [https://developer.1password.com/docs/events-api/reference/](https://developer.1password.com/docs/events-api/reference/)

#### Tags:

 - Audit, Events, Monitoring, Security

#### Properties

- [Documentation](https://developer.1password.com/docs/events-api/reference/)
- [OpenAPI](openapi/1password-events-openapi.yml)
- [JSONSchema](json-schema/1password-events-sign-in-attempt-schema.json)
- [JSON-LD](json-ld/1password-events-context.jsonld)

### 1Password Partnership API
The 1Password Partnership API enables partners to manage provisioning and deprovisioning of third-party partner billing accounts for customers, supporting individual and family account types.

**Human URL:** [https://developer.1password.com/docs/partnership-api/reference/](https://developer.1password.com/docs/partnership-api/reference/)

#### Tags:

 - Billing, Partners, Passwords

#### Properties

- [Documentation](https://developer.1password.com/docs/partnership-api/reference/)
- [OpenAPI](openapi/1password-partnership-openapi.yml)
- [JSON-LD](json-ld/1password-partnership-context.jsonld)

## Common Properties

- [Website](https://1password.com/)
- [Portal](https://developer.1password.com/)
- [Documentation](https://developer.1password.com/docs/)
- [GettingStarted](https://developer.1password.com/docs/get-started/)
- [Authentication](https://developer.1password.com/docs/connect/connect-api-reference/#authentication)
- [SDK - Python SDK](https://pypi.org/project/onepassword-sdk/)
- [SDK - JavaScript SDK](https://www.npmjs.com/package/@1password/sdk)
- [SDK - Go SDK](https://pkg.go.dev/github.com/1Password/onepassword-sdk-go)
- [SDK - Connect Python SDK](https://pypi.org/project/onepassword-connect-sdk/)
- [SDK - Connect Node.js SDK](https://www.npmjs.com/package/@1password/connect)
- [SDK - Connect Go SDK](https://pkg.go.dev/github.com/1Password/connect-sdk-go)
- [CLI](https://developer.1password.com/docs/cli/)
- [Blog](https://blog.1password.com/)
- [Support](https://support.1password.com/)
- [PrivacyPolicy](https://1password.com/legal/privacy/)
- [TermsOfService](https://1password.com/legal/terms-of-service/)
- [SignUp](https://start.1password.com/sign-up/)
- [ChangeLog](https://developer.1password.com/docs/events-api/changelog/)
- [GitHubOrganization](https://github.com/1Password)

## Features

| Name | Description |
|------|-------------|
| Secrets Management | Programmatic access to 1Password vaults and items via Connect Server API |
| Security Monitoring | Real-time audit log streaming of sign-in events, item usage, and audit trails |
| Partner Billing Management | Provision and deprovision 1Password accounts for partner customers |
| SDKs | Official SDKs for Python, JavaScript/TypeScript, Go, and Connect-specific clients |
| CLI | 1Password CLI for command-line secrets management and automation |
| Kubernetes Integration | Kubernetes operator and secrets injector for cloud-native deployments |
| Terraform Provider | Terraform provider to manage 1Password vault items as infrastructure |
| GitHub Actions | Load secrets from 1Password directly into GitHub Actions CI/CD pipelines |

## Use Cases

| Name | Description |
|------|-------------|
| Secrets Injection | Inject secrets from 1Password into applications and containers at runtime |
| Security Audit | Stream and analyze sign-in events and item usage for security incident response |
| Compliance Reporting | Export audit trails for SOC2, GDPR, and other compliance frameworks |
| CI/CD Secrets | Securely provide secrets to CI/CD pipelines without hardcoding credentials |
| Infrastructure as Code | Manage secrets as part of Terraform or Ansible automation workflows |
| Partner Account Provisioning | Automate provisioning of 1Password accounts for partner customer bases |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Native integration via operator and secrets injector for Kubernetes deployments |
| Terraform | Terraform provider for managing 1Password items as infrastructure resources |
| Ansible | Ansible collection for 1Password Connect integration |
| GitHub Actions | GitHub Actions to load and install 1Password secrets in CI/CD workflows |
| Splunk | Events API Splunk integration for security event streaming |
| HashiCorp Vault | Vault plugin for 1Password Connect secrets retrieval |
| Helm Charts | Official Helm charts for deploying 1Password Connect on Kubernetes |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [1Password Connect Server API](openapi/1password-connect-openapi.yml)
- [1Password Events API](openapi/1password-events-openapi.yml)
- [1Password Partnership API](openapi/1password-partnership-openapi.yml)

### JSON Schema

- 27 schema files across Connect, Events, and Partnership APIs

### JSON Structure

- 27 JSON Structure files (json-structure.org format)

### JSON-LD

- [1Password Connect Context](json-ld/1password-connect-context.jsonld)
- [1Password Events Context](json-ld/1password-events-context.jsonld)
- [1Password Partnership Context](json-ld/1password-partnership-context.jsonld)

### Examples

- 29 example JSON files for all schemas

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [1Password Connect API](capabilities/shared/1password-connect.yaml) — 15 operations for vault and item management
- [1Password Events API](capabilities/shared/1password-events.yaml) — 4 operations for security event streaming
- [1Password Partnership API](capabilities/shared/1password-partnership.yaml) — 4 operations for partner account management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [1Password Secrets Management](capabilities/1password-secrets-management.yaml) | Connect, Events, Partnership | 11 | DevOps Engineer, Security Operations, 1Password Partner |

## Vocabulary

- [1Password Vocabulary](vocabulary/1password-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 7 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [1Password Spectral Rules](rules/1password-spectral-rules.yml) — 30 rules across 13 categories enforcing 1Password API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
