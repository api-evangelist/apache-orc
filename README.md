# Apache ORC (apache-orc)

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

Apache ORC is a self-describing, type-aware columnar file format designed for Hadoop workloads. It provides high compression ratios and fast read performance for large-scale data processing with support for complex data types.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-orc/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Big Data, Columnar Storage, Compression, File Format, Hadoop, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache ORC
ORC provides Java and C++ APIs for reading and writing ORC columnar files, with support for predicate pushdown, column projection, compression codecs, and integration with Hive, Spark, Presto, and other query engines.

**Human URL:** [https://orc.apache.org/docs/](https://orc.apache.org/docs/)

#### Tags:

 - C++, Columnar Format, Java, Apache, Open Source, Big Data

#### Properties

- [Documentation](https://orc.apache.org/docs/)
- [OpenAPI](openapi/apache-orc-tools-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/orc)
- [Documentation](https://orc.apache.org/)
- [SpectralRules](rules/apache-orc-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-orc-vocabulary.yaml)
- [NaftikoCapability](capabilities/orc-workflow.yaml)
- [JSON-LD](json-ld/apache-orc-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Columnar Storage | Stores data by column for efficient compression and query performance |
| Predicate Pushdown | Skip reading data that does not match query predicates |
| Column Projection | Read only the columns needed for a query |
| ACID Support | Full ACID transactional support when used with Apache Hive |
| Schema Evolution | Add, rename, and remove columns while preserving backward compatibility |
| Compression | Supports ZLIB, Snappy, LZO, LZ4, and ZSTD compression codecs |

## Use Cases

| Name | Description |
|------|-------------|
| Hive Data Warehousing | Store Hive tables in highly efficient ORC format |
| Spark Analytics | Process large ORC datasets with Apache Spark SQL |
| Presto/Trino Queries | Fast analytical queries over ORC files with Presto or Trino |
| Data Lake Storage | Efficient columnar storage for data lake architectures |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hive | Native ORC support as default Hive storage format |
| Apache Spark | ORC data source support in Spark SQL |
| Presto/Trino | Fast ORC reading with native vectorized reader |
| Apache Flink | ORC file format support for batch and streaming |
| Apache Arrow | ORC to Arrow conversion for in-memory analytics |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache ORC Tools API](openapi/apache-orc-tools-api.yaml)

### JSON Schema

- [File Info](json-schema/apache-orc-file-info-schema.json)
- [ORC Schema](json-schema/apache-orc-orc-schema-schema.json)
- [Column Type](json-schema/apache-orc-column-type-schema.json)
- [File Metadata](json-schema/apache-orc-file-metadata-schema.json)
- [Column Statistics](json-schema/apache-orc-column-statistics-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache ORC JSON Structures](json-structure/)

### JSON-LD

- [Apache ORC Context](json-ld/apache-orc-context.jsonld)

### Examples

- [Apache ORC Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [ORC File Processing Workflow](capabilities/orc-workflow.yaml) | Apache ORC | 6 | Data Engineer, Data Analyst |

## Vocabulary

- [Apache ORC Vocabulary](vocabulary/apache-orc-vocabulary.yaml) — Unified taxonomy mapping ORC resources, actions, workflows, and personas

## Rules

- [Apache ORC Spectral Rules](rules/apache-orc-spectral-rules.yml) — Rules enforcing Apache ORC API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
