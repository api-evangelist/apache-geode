# Apache Geode (apache-geode)
Apache Geode is an in-memory data management platform that provides real-time, consistent access to data-intensive applications throughout widely distributed cloud architectures. It pools memory, CPU, network resources, and local disk storage across multiple processes, offering a REST API for data access, OQL queries, function execution, and cluster management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Caching, Data Grid, Distributed Systems, In-Memory, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Geode REST API
REST API for accessing and managing data in Apache Geode in-memory data grid, including region operations, OQL queries, function execution, and cluster monitoring.

**Human URL:** [https://geode.apache.org/docs/guide/latest/rest_apps/chapter_overview.html](https://geode.apache.org/docs/guide/latest/rest_apps/chapter_overview.html)

#### Tags:

 - Cache, Data Grid, In-Memory, OQL, REST

#### Properties

- [Documentation](https://geode.apache.org/docs/guide/latest/rest_apps/chapter_overview.html)
- [OpenAPI](openapi/apache-geode-rest-openapi.yml)
- [JSONSchema](json-schema/geode-rest-region-info-schema.json)
- [JSON-LD](json-ld/apache-geode-rest-context.jsonld)

### Apache Geode Java Client API
Java API for cache operations, continuous queries, function execution, and data serialization in Apache Geode clusters.

**Human URL:** [https://geode.apache.org/docs/guide/latest/developing/book_intro.html](https://geode.apache.org/docs/guide/latest/developing/book_intro.html)

#### Tags:

 - Java, SDK, Cache, Continuous Query

#### Properties

- [Documentation](https://geode.apache.org/docs/guide/latest/developing/book_intro.html)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.geode/geode-core)

## Common Properties

- [Documentation](https://geode.apache.org/docs/)
- [GettingStarted](https://geode.apache.org/docs/guide/latest/getting_started/book_intro.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/geode)
- [Blog](https://geode.apache.org/blog/)

## Features

| Name | Description |
|------|-------------|
| In-Memory Data Grid | Pool memory across distributed nodes for consistent sub-millisecond data access at scale. |
| REST Data API | HTTP REST API for language-agnostic CRUD operations on Geode regions using JSON. |
| OQL Query Language | SQL-like Object Query Language for executing complex queries against in-memory data. |
| Continuous Queries | Register interest in data changes meeting OQL criteria for real-time event notification. |
| Server-Side Functions | Deploy and execute Java functions on the cluster nodes to co-locate compute with data. |
| ACID Transactions | Full ACID transaction support for consistent multi-region data operations. |
| WAN Replication | Asynchronous and synchronous WAN gateway replication for geo-distributed data consistency. |
| Eviction and Expiration | Configurable eviction policies (LRU, heap, disk) and TTL-based entry expiration. |
| Persistence | Disk persistence option for data recovery after restart without network re-loading. |
| Native Clients | High-performance C++ and .NET native client libraries for non-JVM applications. |

## Use Cases

| Name | Description |
|------|-------------|
| Session Caching | Replace Redis or Memcached with Geode for distributed session caching with ACID guarantees. |
| Real-Time Analytics | Perform OQL queries on in-flight event data for real-time analytical processing. |
| Financial Transaction Processing | Low-latency transaction processing with ACID guarantees for financial trading and payments. |
| Microservices Shared State | Share state between microservices with consistent in-memory data across distributed nodes. |
| IoT Data Aggregation | Aggregate and query high-velocity IoT telemetry data in memory for real-time responses. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Geode-Spark connector for using Geode regions as Spark RDD/DataFrame data sources. |
| Spring Data Geode | Spring Data integration for repository-based data access and caching annotations. |
| Kubernetes | Kubernetes operator for deploying and managing Geode clusters on Kubernetes. |
| Pivotal Cloud Foundry | Cloud Foundry service broker for provisioning Geode instances as managed services. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Geode REST API](openapi/apache-geode-rest-openapi.yml)

### JSON Schema

- 10 schema files in [json-schema/](json-schema/)

### JSON Structure

- 10 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Geode REST Context](json-ld/apache-geode-rest-context.jsonld)

### Examples

- 10 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Geode REST API](capabilities/shared/geode-rest.yaml) — 5 operations for data and cluster management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Geode Data Management](capabilities/geode-data-management.yaml) | geode-rest | 4 | Application Developer, Platform Engineer |

## Vocabulary

- [Apache Geode Vocabulary](vocabulary/apache-geode-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Geode Spectral Rules](rules/apache-geode-spectral-rules.yml) — 9 rules across 5 categories enforcing Apache Geode API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
