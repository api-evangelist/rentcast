# RentCast

RentCast provides a real estate data API with instant access to over 140 million property records, automated valuation models (AVM) for home value and rent estimates, active and historical sale and rental listings, and aggregate real estate market statistics for US zip codes. The API enables real estate investors, property managers, landlords, and proptech applications to programmatically access comprehensive residential and commercial property data across all 50 US states.

**Human URL:** [https://www.rentcast.io/api](https://www.rentcast.io/api)

**Developer Portal:** [https://developers.rentcast.io](https://developers.rentcast.io)

---

## APIs

### RentCast API

The RentCast API (v1.0) serves all US property data at `https://api.rentcast.io/v1`. Authentication uses the `X-Api-Key` header. All endpoints are read-only GET requests:

| Method | Path | Description |
|---|---|---|
| GET | /properties | Search property records |
| GET | /properties/{id} | Get property record by ID |
| GET | /avm/rent/long-term | Rent estimate with comparables |
| GET | /avm/value | Home value estimate with comparables |
| GET | /listings/sale | Sale listings search |
| GET | /listings/sale/{id} | Sale listing by ID |
| GET | /listings/rental/long-term | Rental listings search |
| GET | /listings/rental/long-term/{id} | Rental listing by ID |
| GET | /markets | Market statistics by zip code |

- **Documentation:** [https://developers.rentcast.io/reference/introduction](https://developers.rentcast.io/reference/introduction)
- **OpenAPI Spec:** [openapi/rentcast-openapi.json](openapi/rentcast-openapi.json)
- **Rules:** [rules/rentcast-rules.yml](rules/rentcast-rules.yml)
- **Capabilities:** [capabilities/property-research.yaml](capabilities/property-research.yaml)

---

## Artifacts

### OpenAPI

| File | Description |
|---|---|
| [openapi/rentcast-openapi.json](openapi/rentcast-openapi.json) | RentCast API v1.0 — 10 endpoints |

### Rules

| File | Description |
|---|---|
| [rules/rentcast-rules.yml](rules/rentcast-rules.yml) | Spectral ruleset for RentCast API conventions |

### Capabilities

| File | Description |
|---|---|
| [capabilities/property-research.yaml](capabilities/property-research.yaml) | Property research and market analysis workflow — 7 MCP tools |
| [capabilities/shared/rentcast-api.yaml](capabilities/shared/rentcast-api.yaml) | Shared RentCast API consumed definition |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/rentcast-property-schema.json](json-schema/rentcast-property-schema.json) | JSON Schema for US property record |
| [json-schema/rentcast-estimate-schema.json](json-schema/rentcast-estimate-schema.json) | JSON Schema for property valuation estimate |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/rentcast-property-structure.json](json-structure/rentcast-property-structure.json) | Structural documentation for property record |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/rentcast-context.jsonld](json-ld/rentcast-context.jsonld) | JSON-LD context mapping RentCast to schema.org |

### Examples

| File | Description |
|---|---|
| [examples/rentcast-property-search-example.json](examples/rentcast-property-search-example.json) | Search properties by location |
| [examples/rentcast-rent-estimate-example.json](examples/rentcast-rent-estimate-example.json) | Get an AVM rent estimate with comparables |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/rentcast-vocabulary.yml](vocabulary/rentcast-vocabulary.yml) | Real estate domain vocabulary |

---

## Common Properties

| Property | URL |
|---|---|
| Website | [https://www.rentcast.io](https://www.rentcast.io) |
| Developer Portal | [https://developers.rentcast.io](https://developers.rentcast.io) |
| API Dashboard | [https://app.rentcast.io/app/api](https://app.rentcast.io/app/api) |
| Help Center | [https://help.rentcast.io](https://help.rentcast.io) |
| Blog | [https://www.rentcast.io/blog](https://www.rentcast.io/blog) |
| GitHub | [https://github.com/RentCast](https://github.com/RentCast) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
