# Agilent Technologies (agilent-technologies)
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
