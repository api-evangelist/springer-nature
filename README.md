# Springer Nature (springer-nature)

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

Springer Nature is a globally recognized leader in scientific, technical, and medical publishing, providing access to a wide array of scholarly and professional content. Their developer APIs empower developers to integrate high-quality research metadata, open access full-text content, and text mining capabilities into applications, platforms, and research tools. The APIs cover metadata search, full-text retrieval, open access content, and rich scholarly publication data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/springer-nature/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Academic Publishing
- Open Access
- Research
- Scholarly Content
- Scientific Publishing

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Springer Nature Meta API

The Meta API (versioned metadata) provides access to metadata for over 14 million online documents including articles, books, and book chapters. Supports search by keyword, author, journal, ISBN, DOI, subject, and date range. Returns rich metadata including abstracts, author affiliations, funding, and links.

- **Human URL:** [https://dev.springernature.com/docs/api-endpoints/meta-api/](https://dev.springernature.com/docs/api-endpoints/meta-api/)
- **Base URL:** `https://api.springernature.com/meta/v2`

#### Tags

- Bibliometrics
- Metadata
- Research
- Search

#### Properties

- [Documentation](https://dev.springernature.com/docs/api-endpoints/meta-api/)
- [Getting Started](https://dev.springernature.com/docs/introduction/)
- [OpenAPI](openapi/springer-nature-meta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/springer-nature-meta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-meta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Springer Nature Open Access API

Provides free access to open access research articles and book chapters published by Springer Nature. Returns full-text content (where licensed), metadata, abstracts, and PDF links for open access publications.

- **Human URL:** [https://dev.springernature.com/docs/api-endpoints/open-access/](https://dev.springernature.com/docs/api-endpoints/open-access/)
- **Base URL:** `https://api.springernature.com/openaccess`

#### Tags

- Full Text
- Open Access
- Research Content

#### Properties

- [Documentation](https://dev.springernature.com/docs/api-endpoints/open-access/)
- [OpenAPI](openapi/springer-nature-openaccess-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/springer-nature-openaccess.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-openaccess.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Springer Nature Metadata API

The legacy Metadata API provides metadata retrieval for Springer publications. Returns article and book metadata via DOI, journal name, ISSN, or keyword. Predecessor to the Meta API with slightly different response structure.

- **Human URL:** [https://dev.springernature.com/docs/api-endpoints/metadata-api/](https://dev.springernature.com/docs/api-endpoints/metadata-api/)
- **Base URL:** `https://api.springernature.com`

#### Tags

- Books
- Journals
- Metadata
- Publications

#### Properties

- [Documentation](https://dev.springernature.com/docs/api-endpoints/metadata-api/)
- [Postman Collection](collections/springer-nature-meta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-meta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/springer-nature-openaccess.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-openaccess.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Springer Nature Full Text API

Premium full-text API providing content retrieval for licensed Springer Nature publications including text and data mining (TDM) capabilities. Requires institutional or premium API access. Returns XML and HTML article content.

- **Human URL:** [https://dev.springernature.com/docs/api-endpoints/fulltext-api/](https://dev.springernature.com/docs/api-endpoints/fulltext-api/)
- **Base URL:** `https://api.springernature.com`

#### Tags

- Full Text
- Premium
- Text Mining

#### Properties

- [Documentation](https://dev.springernature.com/docs/api-endpoints/fulltext-api/)
- [Postman Collection](collections/springer-nature-meta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-meta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/springer-nature-openaccess.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/springer-nature-openaccess.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/springernature)
- [Portal](https://dev.springernature.com/)
- [Sign Up](https://dev.springernature.com/signup)
- [Website](https://www.springernature.com/)
- [A P I  Playground](https://dev.springernature.com/docs/live-documentation/)
- [Rate Limits](https://dev.springernature.com/docs/rate-limit-details/rate-limits/)
- [Terms and  Conditions](https://dev.springernature.com/terms-conditions/)
- [GitHub Organization](https://github.com/springernature)
- [Blog](https://www.springernature.com/gp/researchers/the-source)
- [M C P Server](https://github.com/springernature/holmes-mcp-integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
