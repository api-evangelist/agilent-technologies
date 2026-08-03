# Agilent Technologies (agilent-technologies)

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

Agilent Technologies is a global leader in life sciences, diagnostics, and applied chemical markets, providing instruments, software, services, and consumables for laboratory workflows. Agilent offers APIs for laboratory operations management including iLab for core facility billing and scheduling, SLIMS for laboratory information management, CrossLab Asset Manager for instrument management, and VWorks for laboratory automation.

**URL:** [https://www.agilent.com/en](https://www.agilent.com/en)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Life Sciences, Diagnostics, Laboratory, Scientific Instruments, LIMS, Laboratory Automation

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-04-19

## APIs

### Agilent iLab Operations API
The iLab API enables customers to seamlessly integrate outside applications with iLab's billing and reporting modules. It leverages a RESTful application architecture with HATEOAS (Hypermedia as the Engine of Application State) and OAuth2 for secure access. The API supports integrations with institutional financial systems such as SAP, Oracle/PeopleSoft, Lawson, and Banner, as well as identity management systems and LIMS.

**Human URL:** [https://help.ilab.agilent.com/ilab-api](https://help.ilab.agilent.com/ilab-api)

#### Tags:

 - Laboratory Operations, Billing, Core Facilities, Scheduling

#### Properties

- [Documentation](https://help.ilab.agilent.com/ilab-api)
- [Authentication](https://help.ilab.agilent.com/ilab-api)
- [OpenAPI](openapi/agilent-ilab-operations-api.yaml)
- [Core Schema](json-schema/ilab-operations-api-core-schema.json)
- [Service Schema](json-schema/ilab-operations-api-service-schema.json)
- [Service Request Schema](json-schema/ilab-operations-api-service-request-schema.json)
- [Reservation Schema](json-schema/ilab-operations-api-reservation-schema.json)
- [Invoice Schema](json-schema/ilab-operations-api-invoice-schema.json)
- [Member Schema](json-schema/ilab-operations-api-member-schema.json)
- [Project Schema](json-schema/ilab-operations-api-project-schema.json)
- [Core Structure](json-structure/ilab-operations-api-core-structure.json)
- [Service Request Structure](json-structure/ilab-operations-api-service-request-structure.json)
- [JSON-LD](json-ld/agilent-ilab-operations-api-context.jsonld)

### Agilent SLIMS REST API
The SLIMS (Smart Laboratory Information Management System) REST API provides programmatic access to Agilent SLIMS laboratory data management platform. SLIMS features three APIs — REST, Java, and Python — enabling integration with analytical instruments, NGS workflows, biobanks, and R&D labs. The REST API is auto-documented within each SLIMS instance.

**Human URL:** [https://slims-python-api.readthedocs.io/](https://slims-python-api.readthedocs.io/)

#### Tags:

 - LIMS, Laboratory Information Management, NGS, Biobank

#### Properties

- [SLIMS Development Manual v6.9](https://community.agilent.com/cfs-file/__key/docpreview-s/00-00-02-00-89/slims_5F00_development_5F00_manual_2D00_6.9.29.pdf)
- [Python SDK](https://github.com/genohm/slims-python-api)
- [Plugin API](https://github.com/genohm/slims-api)

### Agilent CrossLab Asset Manager API
The CrossLab Asset Manager API provides programmatic access to Agilent's CrossLab instrument services platform, enabling management of laboratory assets, instrument service records, maintenance scheduling, and compliance tracking across laboratory environments.

**Human URL:** [https://crosslab-api.agilent.com/](https://crosslab-api.agilent.com/)

#### Tags:

 - Asset Management, Instrument Services, CrossLab, Maintenance

#### Properties

- [Documentation](https://crosslab-api.agilent.com/)

### Agilent VWorks Automation API
The VWorks API provides a Component Object Model (COM) application programming interface for VWorks laboratory automation software (version 14.0 and later). It enables programmatic control of laboratory workstations, automated liquid handling robots, and integrated automation systems.

**Human URL:** [https://www.agilent.com/cs/library/usermanuals/public/D0008025_VWorks_API_Reference_Agilent.pdf](https://www.agilent.com/cs/library/usermanuals/public/D0008025_VWorks_API_Reference_Agilent.pdf)

#### Tags:

 - Laboratory Automation, Robotics, Liquid Handling, Workstation

#### Properties

- [VWorks API Reference Guide v14.0](https://www.agilent.com/cs/library/usermanuals/public/D0008025_VWorks_API_Reference_Agilent.pdf)

## Common Properties

- [Website](https://www.agilent.com/en)
- [Support](https://www.agilent.com/en/support)
- [Community](https://community.agilent.com)
- [GitHub Organization](https://github.com/Agilent)
- [Terms of Service](https://www.agilent.com/en/legal)
- [Privacy Policy](https://www.agilent.com/en/privacy-statement)

## Features

| Name | Description |
|------|-------------|
| RESTful Architecture | iLab and CrossLab APIs leverage RESTful architecture with HATEOAS for discoverable resource navigation. |
| OAuth2 Authentication | Secure access to APIs via OAuth2 with client ID and API token-based authentication. |
| Financial System Integration | Pre-built integration support for SAP, Oracle/PeopleSoft, Lawson, and Banner financial systems. |
| LIMS Integration | Integration with laboratory information management systems for sample tracking and results management. |
| Instrument Data Import | Ability to import usage logs and data directly from connected laboratory instruments. |
| Plugin Architecture | SLIMS supports custom plugin development via Java and Python APIs for workflow extension. |
| Auto-Generated API Documentation | SLIMS REST API documentation is automatically generated from each deployed instance. |

## Use Cases

| Name | Description |
|------|-------------|
| Core Facility Billing Automation | Automate billing workflows between iLab core facilities and institutional financial systems such as SAP or Oracle. |
| Laboratory Scheduling Integration | Integrate external scheduling applications with iLab's equipment reservation and usage tracking. |
| Sample Lifecycle Management | Use the SLIMS API to track samples from receipt through analysis and reporting across NGS, biobank, and R&D workflows. |
| Instrument Asset Tracking | Manage laboratory instrument service records, calibration schedules, and compliance documentation via CrossLab Asset Manager API. |
| Automation Workflow Control | Programmatically control VWorks-driven liquid handling robots and integrated workstations for high-throughput workflows. |
| LIMS Data Reporting | Extract and aggregate laboratory data from SLIMS for custom reporting and business intelligence integrations. |

## Integrations

| Name | Description |
|------|-------------|
| SAP | Financial system integration for billing and cost accounting via iLab API. |
| Oracle PeopleSoft | ERP integration for institutional billing and financial reporting. |
| Lawson | Financial management system integration for laboratory billing workflows. |
| Banner | Higher education ERP integration for core facility cost center management. |
| LabWare LIMS | Integration between Agilent instruments and LabWare LIMS for data transfer and workflow coordination. |
| Identity Management Systems | Integration with institutional identity providers for single sign-on and user provisioning. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Agilent iLab Operations API](openapi/agilent-ilab-operations-api.yaml)

### JSON Schema

- [Core Schema](json-schema/ilab-operations-api-core-schema.json)
- [Cores List Response Schema](json-schema/ilab-operations-api-cores-list-response-schema.json)
- [Service Schema](json-schema/ilab-operations-api-service-schema.json)
- [Services List Response Schema](json-schema/ilab-operations-api-services-list-response-schema.json)
- [Price Schema](json-schema/ilab-operations-api-price-schema.json)
- [Price Update Request Schema](json-schema/ilab-operations-api-price-update-request-schema.json)
- [Service Request Schema](json-schema/ilab-operations-api-service-request-schema.json)
- [Reservation Schema](json-schema/ilab-operations-api-reservation-schema.json)
- [Invoice Schema](json-schema/ilab-operations-api-invoice-schema.json)
- [Member Schema](json-schema/ilab-operations-api-member-schema.json)
- [Project Schema](json-schema/ilab-operations-api-project-schema.json)
- [Error Response Schema](json-schema/ilab-operations-api-error-response-schema.json)

### JSON Structure

- [Core Structure](json-structure/ilab-operations-api-core-structure.json)
- [Service Structure](json-structure/ilab-operations-api-service-structure.json)
- [Service Request Structure](json-structure/ilab-operations-api-service-request-structure.json)
- [Reservation Structure](json-structure/ilab-operations-api-reservation-structure.json)
- [Invoice Structure](json-structure/ilab-operations-api-invoice-structure.json)
- [Member Structure](json-structure/ilab-operations-api-member-structure.json)
- [Project Structure](json-structure/ilab-operations-api-project-structure.json)

### JSON-LD

- [Agilent iLab Operations API Context](json-ld/agilent-ilab-operations-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Agilent iLab Operations API](capabilities/shared/ilab-operations-api.yaml) — 10 operations for core facility billing, scheduling, and reporting

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Laboratory Operations](capabilities/laboratory-operations.yaml) | iLab Operations API | 11 | Core Facility Manager, Research Administrator, Principal Investigator |

## Vocabulary

- [Agilent Technologies Vocabulary](vocabulary/agilent-technologies-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 4 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Agilent Technologies Spectral Rules](rules/agilent-technologies-spectral-rules.yml) — 37 rules across 13 categories enforcing Agilent Technologies API conventions
