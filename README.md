# Apache ORC (apache-orc)
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
