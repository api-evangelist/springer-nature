# Springer Nature

Springer Nature is a globally recognized leader in scientific, technical, and medical publishing, committed to advancing the research community by providing access to a wide array of scholarly and professional content. Their developer APIs empower developers to integrate high-quality research metadata, open access full-text content, and text mining capabilities into applications, platforms, and research tools.

**URL:** https://dev.springernature.com/

## Tags

Academic Publishing, Open Access, Research, Scholarly Content, Scientific Publishing

## APIs

### Springer Nature Meta API

The Meta API (versioned metadata) provides access to metadata for over 14 million scholarly documents including articles, books, and book chapters. Supports search by keyword, author, journal, ISSN, ISBN, DOI, subject, and date range.

**Human URL:** https://dev.springernature.com/docs/api-endpoints/meta-api/
**Base URL:** https://api.springernature.com/meta/v2

**Tags:** Bibliometrics, Metadata, Research, Search

**Properties:**
- [Documentation](https://dev.springernature.com/docs/api-endpoints/meta-api/)
- [Getting Started](https://dev.springernature.com/docs/introduction/)
- [OpenAPI](openapi/springer-nature-meta-openapi.yml)
- [JSON Schema](json-schema/springer-nature-publication-schema.json)
- [JSON Structure](json-structure/springer-nature-publication-structure.json)

### Springer Nature Open Access API

Provides free access to open access research articles and book chapters published by Springer Nature. Returns metadata and full-text content for open access publications.

**Human URL:** https://dev.springernature.com/docs/api-endpoints/open-access/
**Base URL:** https://api.springernature.com/openaccess

**Tags:** Full Text, Open Access, Research Content

**Properties:**
- [Documentation](https://dev.springernature.com/docs/api-endpoints/open-access/)
- [OpenAPI](openapi/springer-nature-openaccess-openapi.yml)

### Springer Nature Metadata API

The legacy Metadata API provides metadata retrieval for Springer publications. Returns article and book metadata via DOI, journal name, ISSN, or keyword.

**Human URL:** https://dev.springernature.com/docs/api-endpoints/metadata-api/

**Tags:** Books, Journals, Metadata, Publications

**Properties:**
- [Documentation](https://dev.springernature.com/docs/api-endpoints/metadata-api/)

### Springer Nature Full Text API

Premium full-text API providing content retrieval for licensed publications including text and data mining (TDM) capabilities. Requires institutional or premium API access.

**Human URL:** https://dev.springernature.com/docs/api-endpoints/fulltext-api/

**Tags:** Full Text, Premium, Text Mining

**Properties:**
- [Documentation](https://dev.springernature.com/docs/api-endpoints/fulltext-api/)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [springer-nature-meta-openapi.yml](openapi/springer-nature-meta-openapi.yml) | Springer Nature Meta API for metadata search |
| [springer-nature-openaccess-openapi.yml](openapi/springer-nature-openaccess-openapi.yml) | Springer Nature Open Access content API |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [springer-nature-publication-schema.json](json-schema/springer-nature-publication-schema.json) | Scholarly publication metadata record schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [springer-nature-publication-structure.json](json-structure/springer-nature-publication-structure.json) | Publication record and search response structure |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [springer-nature-context.jsonld](json-ld/springer-nature-context.jsonld) | Scholarly publishing linked data context (schema.org, bibo, DC) |

### Examples

| Example | Description |
|---------|-------------|
| [springer-nature-search-publications-example.json](examples/springer-nature-search-publications-example.json) | Search Springer Nature publications by title keyword |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [springer-nature-rules.yml](rules/springer-nature-rules.yml) | API design rules for Springer Nature API conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/scholarly-research.yaml](capabilities/scholarly-research.yaml) | Scholarly research discovery workflow (metadata search + open access) |
| [capabilities/shared/springer-nature-meta.yaml](capabilities/shared/springer-nature-meta.yaml) | Shared Springer Nature Meta API consumer definition |
| [capabilities/shared/springer-nature-openaccess.yaml](capabilities/shared/springer-nature-openaccess.yaml) | Shared Springer Nature Open Access consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [springer-nature-vocabulary.yml](vocabulary/springer-nature-vocabulary.yml) | Scholarly publishing and bibliometrics vocabulary |

## Common Properties

- [Portal](https://dev.springernature.com/)
- [Sign Up](https://dev.springernature.com/signup)
- [Website](https://www.springernature.com/)
- [API Playground](https://dev.springernature.com/docs/live-documentation/)
- [Rate Limits](https://dev.springernature.com/docs/rate-limit-details/rate-limits/)
- [Terms and Conditions](https://dev.springernature.com/terms-conditions/)
- [GitHub Organization](https://github.com/springernature)
- [Blog](https://www.springernature.com/gp/researchers/the-source)

## Maintainers

**Name:** Kin Lane  
**Email:** kin@apievangelist.com
