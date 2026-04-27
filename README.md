# CloudAlly (cloudally)
CloudAlly (now part of OpenText Cybersecurity) is a SaaS backup and recovery service that protects business data in Microsoft 365, Google Workspace, Salesforce, Box, Dropbox, SharePoint, and OneDrive. Beyond the web console, CloudAlly exposes a REST API at api.cloudally.com that lets administrators and partners automate backup-task management, restore/download requests, user provisioning, partner-portal operations, and billing reporting.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Backup, Box, Data Protection, Disaster Recovery, Dropbox, Google Workspace, Microsoft 365, OpenText, SaaS Backup, Salesforce

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-27

## APIs

### CloudAlly API
The CloudAlly API is a JSON REST interface at api.cloudally.com. Partners authenticate by exchanging a Client ID and Client Secret at `/auth/partner` for an access token, while portal users sign in at `/auth`; the resulting token is presented as an `Authorization: Bearer` header. Endpoints expose backup tasks, restore/download jobs, partner profile data, billing, resellers, and user management. The Partner Portal API today is read-oriented (GET), with administrative actions performed via the standard tenant endpoints.

**Human URL:** [https://api.cloudally.com/documentation](https://api.cloudally.com/documentation)

**Base URL:** https://api.cloudally.com

#### Tags

- Backup, Data Protection, Partner Portal, Restore, SaaS Backup

#### Properties

- [Documentation](https://api.cloudally.com/documentation)
- [Support](https://support.cloudally.com/)
- [OpenAPI](openapi/cloudally-openapi.yml)

## Common Properties

- [Website](https://www.cloudally.com)
- [Documentation](https://api.cloudally.com/documentation)
- [Support](https://support.cloudally.com/)
- [Terms of Service](https://www.cloudally.com/terms-of-service/)
- [Privacy Policy](https://www.cloudally.com/privacy-policy/)
- [Parent Company - OpenText Cybersecurity](https://cybersecurity.opentext.com/legacy/cloudally/)
- [OpenAPI](openapi/cloudally-openapi.yml)
- [JSON Schema](json-schema/cloudally-backup-task-schema.json)
- [JSON-LD Context](json-ld/cloudally-context.jsonld)
- [Spectral Ruleset](rules/cloudally-rules.yml)
- [Naftiko Capabilities](capabilities/cloudally-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
