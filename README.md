# CloudAlly (cloudally)

CloudAlly (now part of OpenText Cybersecurity) is a SaaS backup and recovery service that protects business data in Microsoft 365, Google Workspace, Salesforce, Box, Dropbox, SharePoint, and OneDrive. The platform offers automated daily backups, point-in-time restore, cross-user restore, granular search, and partner-portal multitenancy features. Beyond the web console, CloudAlly exposes a REST API at api.cloudally.com that lets administrators and partners automate backup-task management, restore/download requests, user provisioning, partner-portal operations, and billing reporting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudally/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Backup
- Box
- Data Protection
- Disaster Recovery
- Dropbox
- Google Workspace
- Microsoft 365
- OpenText
- SaaS Backup
- Salesforce

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### CloudAlly API

The CloudAlly API is a JSON REST interface at api.cloudally.com. Partners authenticate by exchanging a Client ID and Client Secret at /auth/partner for an access token, while portal users sign in at /auth; the resulting token is presented as an Authorization Bearer header. Endpoints expose backup tasks, restore/download jobs, partner profile data, billing, resellers, and user management. The Partner Portal API today is read-oriented (GET), with administrative actions performed via the standard tenant endpoints.

- **Human URL:** [https://api.cloudally.com/documentation](https://api.cloudally.com/documentation)
- **Base URL:** `https://api.cloudally.com`

#### Tags

- Backup
- Data Protection
- Partner Portal
- Restore
- SaaS Backup

#### Properties

- [Documentation](https://api.cloudally.com/documentation)
- [Support](https://support.cloudally.com/)
- [OpenAPI](openapi/cloudally-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudally.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudally.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cloudally)
- [Website](https://www.cloudally.com)
- [Documentation](https://api.cloudally.com/documentation)
- [Support](https://support.cloudally.com/)
- [Terms of Service](https://www.cloudally.com/terms-of-service/)
- [Privacy Policy](https://www.cloudally.com/privacy-policy/)
- [Parent Company](https://cybersecurity.opentext.com/legacy/cloudally/)
- [OpenAPI](openapi/cloudally-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cloudally-backup-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/cloudally-context.jsonld)
- [Spectral Rules](rules/cloudally-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
