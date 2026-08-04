# Department of Homeland Security (department-of-homeland-security)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The U.S. Department of Homeland Security (DHS) is a cabinet-level federal agency responsible for protecting the nation from terrorism, securing borders, enforcing immigration law, responding to disasters, and securing cyberspace. DHS exposes APIs across its operational components, including FEMA's OpenFEMA platform, USCIS's Developer Portal, the CISA Known Exploited Vulnerabilities catalog, the National Terrorism Advisory System (NTAS) feed, and the DHS Open Data Catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Public

## Tags

- CISA
- Cybersecurity
- Disaster
- Federal Government
- FEMA
- Homeland Security
- Immigration
- NTAS
- Open Data
- USCIS

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### OpenFEMA API

The OpenFEMA API is FEMA's public RESTful service that exposes more than 70 datasets including disaster declarations, public assistance funded projects, individual assistance grants, hazard mitigation, and housing assistance program data. The API is free, requires no API key, and supports OData-style query string parameters for filtering, sorting, pagination, and field selection. Default page size is 1,000 records up to a maximum of 10,000.

- **Human URL:** [https://www.fema.gov/about/openfema](https://www.fema.gov/about/openfema)
- **Base URL:** `https://www.fema.gov/api/open`

#### Tags

- Disaster
- FEMA
- Hazard Mitigation
- Public Assistance

#### Properties

- [Documentation](https://www.fema.gov/about/openfema/api)
- [Developer  Resources](https://www.fema.gov/about/openfema/developer-resources)
- [Datasets](https://www.fema.gov/about/openfema/data-sets)
- [Changelog](https://www.fema.gov/about/openfema/changelog)
- [OpenAPI](openapi/department-of-homeland-security-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USCIS Case Status API

The USCIS Case Status API provides programmatic access to the same Case Status Online lookup that immigration applicants use, allowing authorized partners to retrieve the current status and history of a USCIS case by receipt number. The API uses OAuth 2.0 client credentials and is published through the USCIS Developer Portal.

- **Human URL:** [https://developer.uscis.gov/api/case-status](https://developer.uscis.gov/api/case-status)
- **Base URL:** `https://api.uscis.gov`

#### Tags

- Case Status
- Immigration
- USCIS

#### Properties

- [Documentation](https://developer.uscis.gov/api/case-status)
- [Portal](https://developer.uscis.gov/)
- [Catalog](https://developer.uscis.gov/apis)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USCIS FOIA Request and Status API

The USCIS FOIA Request and Status API allows partners to submit Freedom of Information Act requests programmatically and check the status of submitted requests. It is published through the USCIS Developer Portal using OAuth 2.0.

- **Human URL:** [https://developer.uscis.gov/api/foia-request-and-status](https://developer.uscis.gov/api/foia-request-and-status)
- **Base URL:** `https://api.uscis.gov`

#### Tags

- FOIA
- Immigration
- USCIS

#### Properties

- [Documentation](https://developer.uscis.gov/api/foia-request-and-status)
- [Portal](https://developer.uscis.gov/)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CISA Known Exploited Vulnerabilities Catalog Feed

The CISA Known Exploited Vulnerabilities (KEV) catalog is a curated list of vulnerabilities that have been actively exploited in the wild. The catalog is published as a JSON and CSV feed by the Cybersecurity and Infrastructure Security Agency (CISA), and is mirrored on GitHub for easy programmatic access.

- **Human URL:** [https://www.cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- **Base URL:** `https://www.cisa.gov/sites/default/files/feeds`

#### Tags

- CISA
- CVE
- Cybersecurity
- KEV
- Vulnerabilities

#### Properties

- [Documentation](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [J S O N  Feed](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json)
- [K E V  Resources](https://www.cisa.gov/resources-tools/resources/kev-catalog)
- [Mirror](https://github.com/cisagov/kev-data)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### National Terrorism Advisory System Feed

The National Terrorism Advisory System (NTAS) feed publishes current terrorism alerts and bulletins issued by DHS as XML files. Developers can consume the feed to surface advisory content in their own applications and web pages.

- **Human URL:** [https://www.dhs.gov/ntas-api-documentation](https://www.dhs.gov/ntas-api-documentation)
- **Base URL:** `https://www.dhs.gov`

#### Tags

- Alerts
- NTAS
- Terrorism
- XML

#### Properties

- [Documentation](https://www.dhs.gov/ntas-api-documentation)
- [N T A S](https://www.dhs.gov/national-terrorism-advisory-system)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DHS Open Data Catalog

The DHS Open Data Catalog publishes datasets across the Department's mission areas (immigration, law enforcement, emergency management, cybersecurity, infrastructure protection, screening, and maritime). Datasets are also available via Data.gov's CKAN-compatible API.

- **Human URL:** [https://www.dhs.gov/data](https://www.dhs.gov/data)
- **Base URL:** `https://catalog.data.gov/api/3`

#### Tags

- CKAN
- Datasets
- Open Data

#### Properties

- [Documentation](https://www.dhs.gov/data)
- [O H S S](https://ohss.dhs.gov/)
- [Data.gov  D H S](https://catalog.data.gov/organization/dhs-gov)
- [C K A N  Reference](https://docs.ckan.org/en/2.8/api/)
- [Postman Collection](collections/department-of-homeland-security.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/department-of-homeland-security.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/us-department-of-homeland-security)
- [Website](https://www.dhs.gov)
- [Open  Data](https://www.dhs.gov/data)
- [Office of  Homeland  Security  Statistics](https://ohss.dhs.gov/)
- [F E M A](https://www.fema.gov)
- [U S C I S  Developer  Portal](https://developer.uscis.gov/)
- [C I S A](https://www.cisa.gov)
- [T S A](https://www.tsa.gov)
- [C B P](https://www.cbp.gov)
- [I C E](https://www.ice.gov)
- [Coast  Guard](https://www.uscg.mil)
- [Secret  Service](https://www.secretservice.gov)
- [Components](https://www.dhs.gov/operational-and-support-components)
- [Data.gov  D H S  Catalog](https://catalog.data.gov/organization/dhs-gov)
- [Privacy](https://www.dhs.gov/privacy-office)
- [Contact](https://www.dhs.gov/contact-us)
- [GitHub Organization](https://github.com/cisagov)
- [JSON-LD](json-ld/department-of-homeland-security-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/department-of-homeland-security-vocabulary.yml)
- [Capabilities](capabilities/department-of-homeland-security-capabilities.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
