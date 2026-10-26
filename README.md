# CloudAlly (cloudally)

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
