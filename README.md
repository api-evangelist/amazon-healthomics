# Amazon HealthOmics (amazon-healthomics)
AWS HealthOmics is a purpose-built service for healthcare and life sciences organizations that helps store, query, and analyze genomic, transcriptomic, and other omics data to generate insights and accelerate scientific discoveries and improve healthcare.

**URL:** [https://aws.amazon.com/healthomics/](https://aws.amazon.com/healthomics/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Bioinformatics, Genomics, Healthcare, Life Sciences, Cloud Computing

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS HealthOmics API
The AWS HealthOmics API provides programmatic access to manage omics storage, workflows, run groups, annotation stores, and variant stores for genomics and other omics data analysis.

**Human URL:** [https://aws.amazon.com/healthomics/](https://aws.amazon.com/healthomics/)

#### Tags:

 - Genomics, Healthcare, Life Sciences, Bioinformatics, Workflows

#### Properties

- [Documentation](https://docs.aws.amazon.com/omics/latest/api/Welcome.html)
- [OpenAPI](openapi/amazon-healthomics-openapi.yaml)
- [GettingStarted](https://aws.amazon.com/healthomics/getting-started/)
- [Pricing](https://aws.amazon.com/healthomics/pricing/)
- [FAQ](https://aws.amazon.com/healthomics/faqs/)
- [APIReference](https://docs.aws.amazon.com/omics/latest/api/Welcome.html)
- [Authentication](https://docs.aws.amazon.com/omics/latest/api/CommonParameters.html)
- [JSONSchema](json-schema/healthomics-abort-multipart-read-set-upload-request-schema.json)
- [JSONLD](json-ld/amazon-healthomics-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/healthomics/)
- [Documentation](https://docs.aws.amazon.com/omics/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/industries/healthcare/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/omics/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SDK](https://aws.amazon.com/developer/tools/)
- [CLI](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/omics/index.html)

## Features

| Name | Description |
|------|-------------|
| Omics Storage | Purpose-built storage for genomic, transcriptomic, and other omics data with automatic optimization. |
| Bioinformatics Workflows | Run industry-standard bioinformatics tools and pipelines using WDL and Nextflow workflow definitions. |
| Annotation Stores | Store and query genomic annotation data from sources like ClinVar, Ensembl, and custom datasets. |
| Variant Stores | Store and query genomic variant data in VCF and other standard bioinformatics formats. |
| Sequence Stores | Efficiently store and retrieve genomic sequence read sets in FASTQ, BAM, and CRAM formats. |
| Reference Genomes | Store and access reference genome files for alignment and analysis workflows. |
| Managed Compute | Fully managed compute infrastructure for running bioinformatics workflows at scale. |

## Use Cases

| Name | Description |
|------|-------------|
| Whole Genome Sequencing | Store, analyze, and interpret whole genome sequencing data for research and clinical applications. |
| Variant Calling Pipelines | Run standard variant calling workflows on genomic data to identify genetic variants. |
| Pharmacogenomics Research | Analyze genomic data to understand drug response and develop personalized medicine approaches. |
| Population Genomics | Process and analyze large-scale genomic datasets across patient populations for research. |
| Clinical Genomics | Support clinical genomics workflows for diagnosis and treatment of genetic disorders. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Import and export omics data using S3 as the primary data source and destination. |
| AWS IAM | Control access to HealthOmics resources using IAM roles and policies. |
| Amazon CloudWatch | Monitor HealthOmics workflows and storage operations through CloudWatch metrics. |
| AWS Lake Formation | Govern and secure genomic data lake access using Lake Formation permissions. |
| Amazon Athena | Query genomic annotation and variant data stored in HealthOmics using Athena. |
| AWS Batch | Supplement HealthOmics workflows with custom compute jobs using AWS Batch. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS HealthOmics OpenAPI](openapi/amazon-healthomics-openapi.yaml)

### JSON Schema

459 schema files in [json-schema/](json-schema/)

### JSON Structure

459 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon HealthOmics Context](json-ld/amazon-healthomics-context.jsonld)

### Examples

459 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AWS HealthOmics](capabilities/shared/amazon-healthomics.yaml) — 20 operations for omics data management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon HealthOmics Genomics Operations](capabilities/amazon-healthomics-genomics-operations.yaml) | AWS HealthOmics | 12 | Bioinformatics Scientist, Genomics Data Engineer, Life Sciences Developer |

## Vocabulary

- [Amazon HealthOmics Vocabulary](vocabulary/amazon-healthomics-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon HealthOmics Spectral Rules](rules/amazon-healthomics-spectral-rules.yml) — 8 rules across 4 categories enforcing Amazon HealthOmics API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
