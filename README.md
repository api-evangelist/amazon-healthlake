# Amazon HealthLake (amazon-healthlake)

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

Amazon HealthLake is a HIPAA-eligible service that gives healthcare providers, health insurance companies, and pharmaceutical companies the ability to store, transform, query, and analyze health data at scale in the cloud. It uses the Fast Healthcare Interoperability Resources (FHIR) standard.

**URL:** [https://aws.amazon.com/healthlake/](https://aws.amazon.com/healthlake/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, FHIR, Health Data, Healthcare, HIPAA, Cloud Computing

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon HealthLake API
The Amazon HealthLake API provides programmatic access to create and manage FHIR datastores, import and export health data, and run analytics on FHIR-formatted health records.

**Human URL:** [https://aws.amazon.com/healthlake/](https://aws.amazon.com/healthlake/)

#### Tags:

 - FHIR, Health Data, Healthcare, HIPAA, Datastores

#### Properties

- [Documentation](https://docs.aws.amazon.com/healthlake/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-healthlake-openapi.yaml)
- [GettingStarted](https://aws.amazon.com/healthlake/getting-started/)
- [Pricing](https://aws.amazon.com/healthlake/pricing/)
- [FAQ](https://aws.amazon.com/healthlake/faqs/)
- [APIReference](https://docs.aws.amazon.com/healthlake/latest/APIReference/Welcome.html)
- [Authentication](https://docs.aws.amazon.com/healthlake/latest/APIReference/CommonParameters.html)
- [JSONSchema](json-schema/healthlake-create-fhir-datastore-request-schema.json)
- [JSONLD](json-ld/amazon-healthlake-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/healthlake/)
- [Documentation](https://docs.aws.amazon.com/healthlake/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/industries/healthcare/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/healthlake/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SDK](https://aws.amazon.com/developer/tools/)
- [CLI](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/healthlake/index.html)

## Features

| Name | Description |
|------|-------------|
| FHIR Compliance | Fully compliant with the FHIR R4 standard for healthcare data interoperability. |
| HIPAA-Eligible | HIPAA-eligible service for storing and processing protected health information. |
| Integrated Data Import | Bulk import FHIR-formatted health data from Amazon S3 with automated validation. |
| Data Export | Export FHIR health data to Amazon S3 for analytics, archiving, or migration. |
| Integrated Search | Query FHIR resources using standard FHIR search operations for clinical workflows. |
| Automated De-identification | Built-in de-identification capabilities for removing PHI from health data. |
| Analytics Integration | Integrated analytics with Amazon Comprehend Medical and other AWS analytics services. |

## Use Cases

| Name | Description |
|------|-------------|
| Clinical Data Repository | Create a centralized FHIR-compliant repository for clinical data from multiple sources. |
| Health Data Exchange | Enable interoperable health data exchange between healthcare providers and payers. |
| Population Health Management | Analyze aggregated health data to identify trends and manage population health programs. |
| AI-Powered Clinical Insights | Apply machine learning to FHIR data to generate clinical insights and predictions. |
| Research Data Platform | Create de-identified research datasets from FHIR health records for clinical studies. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Import and export FHIR health data using S3 as the data source and destination. |
| AWS IAM | Control access to HealthLake resources using IAM roles and policies. |
| Amazon CloudWatch | Monitor HealthLake operations and performance metrics through CloudWatch. |
| Amazon Comprehend Medical | Extract medical entities from unstructured health data using Comprehend Medical. |
| Amazon SageMaker | Apply SageMaker ML models to FHIR data for predictive health analytics. |
| AWS Glue | Transform and catalog FHIR health data for analytics using AWS Glue. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon HealthLake OpenAPI](openapi/amazon-healthlake-openapi.yaml)

### JSON Schema

76 schema files in [json-schema/](json-schema/)

### JSON Structure

76 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon HealthLake Context](json-ld/amazon-healthlake-context.jsonld)

### Examples

76 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon HealthLake](capabilities/shared/amazon-healthlake.yaml) — 13 operations for FHIR health data management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon HealthLake Health Data Operations](capabilities/amazon-healthlake-health-data-operations.yaml) | Amazon HealthLake | 10 | Healthcare Developer, FHIR Data Engineer, HIPAA Compliance Officer |

## Vocabulary

- [Amazon HealthLake Vocabulary](vocabulary/amazon-healthlake-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 7 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon HealthLake Spectral Rules](rules/amazon-healthlake-spectral-rules.yml) — 8 rules across 4 categories enforcing Amazon HealthLake API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
