# US Department of Commerce

The US Department of Commerce is responsible for promoting economic growth and job creation in the United States. It oversees various programs and initiatives aimed at supporting businesses, industries, and communities across the country. The department works to ensure fair trade practices, protect intellectual property, and promote innovation and entrepreneurship. It also collects and analyzes economic data to inform policy decisions and help businesses make informed decisions. The Commerce Department houses bureaus including the Census Bureau, Bureau of Economic Analysis, International Trade Administration, NOAA, and NIST, each offering public APIs for their respective data domains.

**URL:** [https://www.commerce.gov](https://www.commerce.gov)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

`Commerce` `Federal Government` `Open Data` `Trade` `Economic Data` `Climate` `Standards`

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

## APIs

| API | Description |
|-----|-------------|
| [Commerce.gov API](https://www.commerce.gov/data-and-reports/developer-resources/commercegov-api) | Content API for news, blog posts, and images on Commerce.gov |
| [US Census Bureau Data API](https://www.census.gov/data/developers/data-sets.html) | Demographic, economic, and geographic datasets |
| [Bureau of Economic Analysis API](https://apps.bea.gov/API/signup/) | GDP, national accounts, and economic statistics |
| [International Trade Administration API](https://developer.trade.gov/) | Trade data, screening lists, and export information |
| [NOAA Climate and Weather API](https://www.ncdc.noaa.gov/cdo-web/webservices/v2) | Climate and weather data from NOAA/NCEI |
| [NIST Data Discovery API](https://data.nist.gov/pdr/lps/) | NIST research datasets and standards |
| [Commerce Data Hub Open Data Portal API](https://data.commerce.gov/open-data-portal-odp-api-version-23) | Commerce Department open data catalog |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [Commerce.gov API](openapi/commerce-gov-api-openapi.yml) | OpenAPI 3.0 spec for news, blogs, and images |

## Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [Commerce.gov API Rules](rules/commerce-gov-api-rules.yml) | Spectral rules enforcing Commerce.gov API conventions |

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [Commerce Content](capabilities/commerce-content.yaml) | Monitor Commerce Department news and blog content |

### Shared API Definitions

| Shared Definition | Description |
|-------------------|-------------|
| [Commerce.gov API](capabilities/shared/commerce-gov-api.yaml) | Shared definition for Commerce.gov content API |

## JSON Schema

| Schema | Description |
|--------|-------------|
| [News Article](json-schema/commerce-gov-news-article-schema.json) | Schema for Commerce.gov news articles |

## JSON Structure

| Structure | Description |
|-----------|-------------|
| [News Article Structure](json-structure/commerce-gov-news-article-structure.json) | Field documentation for news articles |

## JSON-LD

| Context | Description |
|---------|-------------|
| [Commerce Context](json-ld/us-department-of-commerce-context.jsonld) | Linked data context mapping Commerce terms to schema.org |

## Examples

| Example | Description |
|---------|-------------|
| [List News Example](examples/commerce-gov-list-news-example.json) | Example response for listing news articles |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Commerce Vocabulary](vocabulary/us-department-of-commerce-vocabulary.yml) | Domain vocabulary for Commerce Department data |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
