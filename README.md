# Amazon HealthLake (amazon-healthlake)
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
