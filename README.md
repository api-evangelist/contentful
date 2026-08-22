# Contentful (contentful)

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

Contentful is a content management platform that allows businesses to create, manage, and deliver digital content across various channels and devices. By using Contentful, companies can streamline their content creation process, collaborate with team members, and ensure a consistent and cohesive brand message.

**APIs.json:** [https://raw.githubusercontent.com/apis-json/artisanal/main/apis/contentful.yml](https://raw.githubusercontent.com/apis-json/artisanal/main/apis/contentful.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- CMS
- Content

## Timestamps

- **Created:** 2023/11/20
- **Modified:** 2026-05-30

## APIs

### Contentful Content Delivery API

The Content Delivery API (CDA), available at cdn.contentful.com, is a read-only API for delivering content from Contentful to apps, websites and other media. Content is delivered as JSON data, and images, videos and other media as files.

- **Human URL:** [https://www.contentful.com/developers/docs/references/content-delivery-api/](https://www.contentful.com/developers/docs/references/content-delivery-api/)
- **Base URL:** `https://cdn.contentful.com`

#### Tags

- CMS
- Content

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/content-delivery-api/)
- [OpenAPI](openapi/contentful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful Content Management API

Contentful's Content Management API (CMA) helps you manage content in your spaces. To learn more about how to model your content, read our modeling guide.

- **Human URL:** [https://www.contentful.com/developers/docs/references/content-management-api/](https://www.contentful.com/developers/docs/references/content-management-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/content-management-api/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful Preview API

In addition to the Content Delivery API (CDA) for published content, is the Preview API for previewing both published and unpublished content. It maintains the same behaviour and parameters as the CDA, but delivers the latest drafts for entries and assets. The Content Preview API is used to display the latest version of an entry.

- **Human URL:** [https://www.contentful.com/developers/docs/references/content-preview-api/](https://www.contentful.com/developers/docs/references/content-preview-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content
- Preview

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/content-preview-api/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful Images API

The Contentful Images API allows the retrieval and manipulation of image files referenced from assets.

- **Human URL:** [https://www.contentful.com/developers/docs/references/images-api/](https://www.contentful.com/developers/docs/references/images-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content
- Images

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/images-api/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful GraphQL Content API

The GraphQL Content API provides a GraphQL API interface to the content from Contentful. Each Contentful space comes with a GraphQL schema based on its content model. This GraphQL schema is generated at request time and is always up-to-date with the current status of the space.

- **Human URL:** [https://www.contentful.com/developers/docs/references/graphql/](https://www.contentful.com/developers/docs/references/graphql/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content
- GraphQL

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/graphql/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful User Management API

Contentful's User Management API helps organizations programmatically manage their organizations, organization memberships, teams, space memberships and more.

- **Human URL:** [https://www.contentful.com/developers/docs/references/user-management-api/](https://www.contentful.com/developers/docs/references/user-management-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content
- Users

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/user-management-api/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful SCIM API

System for Cross-domain Identity Management, or SCIM, is an API specification created to facilitate the management of people and groups of people in cloud-based applications and services.

- **Human URL:** [https://www.contentful.com/developers/docs/references/scim-api/](https://www.contentful.com/developers/docs/references/scim-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- CMS
- Content
- SCIM

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/references/scim-api/)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contentful Webhooks

Contentful webhooks are HTTP callbacks that notify subscriber endpoints when content events (ContentType, Entry, Asset, Task, Comment, Release, Workflow, Template Installation) and action events (Release Actions, Bulk Actions, Scheduled Actions) occur in a space. Requests are POSTed as application/vnd.contentful.management.v1+json and, when a 64-character signing secret is configured, signed with HMAC-SHA256 via the x-contentful-signature, x-contentful-signed-headers, and x-contentful-timestamp headers.

- **Human URL:** [https://www.contentful.com/developers/docs/webhooks/](https://www.contentful.com/developers/docs/webhooks/)

#### Tags

- CMS
- Content
- Webhooks
- Events

#### Properties

- [Documentation](https://www.contentful.com/developers/docs/webhooks/)
- [Documentation](https://www.contentful.com/developers/docs/webhooks/content-events/)
- [Documentation](https://www.contentful.com/developers/docs/webhooks/action-events/)
- [Documentation](https://www.contentful.com/developers/docs/webhooks/headers/)
- [Documentation](https://www.contentful.com/developers/docs/webhooks/request-verification/)
- [AsyncAPI](openapi/contentful-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/contentful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contentful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/contentful)
- [Portal](https://www.contentful.com/developers/)
- [Documentation](https://www.contentful.com/developers/docs/)
- [Changelog](https://www.contentful.com/developers/changelog/)
- [Blog](https://www.contentful.com/blog/category/guides/)
- [Plans](https://www.contentful.com/pricing/)
- [Sign Up](https://www.contentful.com/sign-up/#small)
- [Login](https://be.contentful.com/login)
- [Webhooks](https://www.contentful.com/faq/webhooks/)
- [Changelog](https://www.contentful.com/developers/changelog/)
- [Code of  Conduct](https://www.contentful.com/developers/code-of-conduct/)
- [Support](https://www.contentful.com/support/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/contentful?sort=newest)
- [Security](https://www.contentful.com/security/)
- [Privacy Policy](https://www.contentful.com/legal/privacy-at-contentful/privacy-notice/)
- [Website](https://www.contentful.com/)
- [GitHub Organization](https://github.com/contentful)
- [Authentication](https://www.contentful.com/developers/docs/references/authentication/)
- [Integrations](https://www.contentful.com/marketplace/)
- [M C P Server](https://github.com/contentful/contentful-mcp-server)
- [Agent Skill](https://github.com/contentful/skill-kit)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
