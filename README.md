# Albertsons (albertsons)
Albertsons Companies is one of the largest food and drug retailers in the United States, operating supermarkets and pharmacies under banners including Albertsons, Safeway, Vons, Jewel-Osco, Acme, Shaw's, Star Market, and others. The company operates the Albertsons Media Collective, a retail media network that provides advertisers API access to near-real-time campaign performance data and audience targeting capabilities based on shopper purchase behavior across its banner network.

**URL:** [https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Grocery, Retail, Retail Media, Advertising, Campaigns, Analytics, Consumer Goods, Food, Pharmacy

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-04-19

## APIs

### Albertsons Media Collective API
The Albertsons Media Collective API enables advertisers to integrate with Albertsons retail media network for campaign management and performance analytics. The API provides near-real-time access to campaign performance data, allowing advertisers to bring data into their own measurement models for analysis. The developer portal, built on Microsoft Azure API Management, provides API documentation, code samples, and an interactive console for testing.

**Human URL:** [https://portal-prod.apim.azwestus.stratus.albertsons.com/](https://portal-prod.apim.azwestus.stratus.albertsons.com/)

#### Tags:

 - Advertising, Grocery, Retail, Retail Media, Campaigns, Analytics

#### Properties

- [Documentation](https://portal-prod.apim.azwestus.stratus.albertsons.com/)
- [OpenAPI](openapi/albertsons-retail-media-api-openapi.yml)
- [Campaign Schema](json-schema/retail-media-api-campaign-schema.json)
- [Performance Metric Schema](json-schema/retail-media-api-performance-metric-schema.json)
- [Audience Schema](json-schema/retail-media-api-audience-schema.json)
- [Report Request Schema](json-schema/retail-media-api-report-request-schema.json)
- [Report Response Schema](json-schema/retail-media-api-report-response-schema.json)

## Common Properties

- [Website](https://www.albertsons.com)
- [Portal](https://portal-prod.apim.azwestus.stratus.albertsons.com/)
- [TermsOfService](https://www.albertsons.com/terms-and-conditions/)
- [PrivacyPolicy](https://www.albertsons.com/privacy-policy/)

## Features

| Name | Description |
|------|-------------|
| Near-Real-Time Campaign Performance | Access advertising campaign performance data in near-real-time to bring metrics into custom dashboards and measurement models. |
| Audience Targeting | Target campaigns using audience segments derived from Albertsons shopper purchase behavior across grocery and pharmacy banners. |
| Campaign Management | Create, update, and manage advertising campaigns with budget controls, scheduling, and audience targeting configurations. |
| Custom Reporting | Generate configurable performance reports with custom dimensions and metrics for export to external analytics tools. |
| Azure API Management Portal | Interactive developer portal built on Microsoft Azure API Management with documentation, code samples, and an API testing console. |
| Multi-Banner Reach | Access to shopper audiences across Albertsons, Safeway, Vons, Jewel-Osco, Acme, and other banner networks. |

## Use Cases

| Name | Description |
|------|-------------|
| Campaign Performance Dashboards | Pull near-real-time campaign metrics into custom brand or agency dashboards for monitoring impressions, clicks, and ROAS. |
| Automated Budget Optimization | Integrate campaign performance data into automated bidding and budget allocation systems. |
| Third-Party Measurement Integration | Share campaign performance data with measurement partners like TransUnion for attribution and audience analysis. |
| Media Mix Modeling | Incorporate Albertsons retail media performance data into multi-channel media mix models. |
| Audience Insights | Analyze shopper audience segments to inform product marketing strategy and campaign targeting decisions. |

## Integrations

| Name | Description |
|------|-------------|
| TransUnion | Partnership integration for enhanced audience measurement and identity resolution using TransUnion data. |
| Microsoft Azure | Developer portal and API gateway infrastructure built on Microsoft Azure API Management. |
| Analytics Platforms | Export campaign data to third-party analytics dashboards and reporting tools via the Performance API. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Albertsons Media Collective API](openapi/albertsons-retail-media-api-openapi.yml)

### JSON Schema

- [Campaign](json-schema/retail-media-api-campaign-schema.json)
- [Campaign List Response](json-schema/retail-media-api-campaign-list-response-schema.json)
- [Create Campaign Request](json-schema/retail-media-api-create-campaign-request-schema.json)
- [Performance Metric](json-schema/retail-media-api-performance-metric-schema.json)
- [Performance Metrics Response](json-schema/retail-media-api-performance-metrics-response-schema.json)
- [Audience](json-schema/retail-media-api-audience-schema.json)
- [Audience List Response](json-schema/retail-media-api-audience-list-response-schema.json)
- [Report Request](json-schema/retail-media-api-report-request-schema.json)
- [Report Response](json-schema/retail-media-api-report-response-schema.json)
- [Error Response](json-schema/retail-media-api-error-response-schema.json)

### JSON Structure

- [Campaign](json-structure/retail-media-api-campaign-structure.json)
- [Campaign List Response](json-structure/retail-media-api-campaign-list-response-structure.json)
- [Create Campaign Request](json-structure/retail-media-api-create-campaign-request-structure.json)
- [Performance Metric](json-structure/retail-media-api-performance-metric-structure.json)
- [Performance Metrics Response](json-structure/retail-media-api-performance-metrics-response-structure.json)
- [Audience](json-structure/retail-media-api-audience-structure.json)
- [Audience List Response](json-structure/retail-media-api-audience-list-response-structure.json)
- [Report Request](json-structure/retail-media-api-report-request-structure.json)
- [Report Response](json-structure/retail-media-api-report-response-structure.json)
- [Error Response](json-structure/retail-media-api-error-response-structure.json)

### JSON-LD

- [Retail Media API Context](json-ld/albertsons-retail-media-api-context.jsonld)

### Examples

- [Campaign Example](examples/retail-media-api-campaign-example.json)
- [Performance Metric Example](examples/retail-media-api-performance-metric-example.json)
- [Audience Example](examples/retail-media-api-audience-example.json)
- [Report Request Example](examples/retail-media-api-report-request-example.json)
- [Report Response Example](examples/retail-media-api-report-response-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Retail Media API](capabilities/shared/retail-media-api.yaml) — 6 operations for campaign management, performance analytics, audience targeting, and reporting

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Retail Media Advertising](capabilities/retail-media-advertising.yaml) | Retail Media API | 6 | Brand Manager, Media Planner |

## Vocabulary

- [Albertsons Vocabulary](vocabulary/albertsons-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 4 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Albertsons Spectral Rules](rules/albertsons-spectral-rules.yml) — 38 rules across 12 categories enforcing Albertsons API conventions

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
