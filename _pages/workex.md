---
layout: default
title: work experience
permalink: /work-experience/
nav: true
nav_order: 3
---

## JPMorgan Chase & Co.

### Software Engineer II

_January 2025 - July 2026_

- Owned the end-to-end technical design and implementation of a new Spark-based data platform replacing legacy processing systems, from architecture through production rollout.
- Redesigned platform execution to eliminate Databricks-DynamoDB state synchronization, removing a fragile distributed dependency and improving throughput by up to 80%.
- Reduced runtime of a complex ~60-operation Spark DAG processing 1-10M records from ~10 minutes to ~1.5 minutes through logical-plan optimization and data-dependent DAG construction.
- Redesigned partitioning and tuned parallelism to mitigate shuffle bottlenecks, reducing cluster compute costs by ~40% without performance degradation.
- Optimized table partitioning using Spark execution plans and Databricks query profiles, increasing data skipping from 65% to 98% and reducing dashboard refresh latency from ~5 minutes to ~10 seconds.

I held full technical design and implementation ownership. My manager provided domain expertise, while our PM/QA counterpart handled project coordination, regression testing, and data reconciliation.

### Software Engineer I

_July 2023 - December 2024_

- Profiled memory growth of a Polars-based transformation in AWS Lambda; introduced lazy evaluation and explicit object lifecycle control, reducing peak memory allocation by 60% and stabilizing execution latency.
- Brought up a multi-node ingestion system on Kubernetes (EKS + NiFi), implemented Airflow orchestration for distributed workflows, and operated cross-service data movement pipelines in production.
- Earned accelerated promotion to Software Engineer II for ownership of distributed data infrastructure and production performance engineering.

### Software Engineer Intern

_January 2023 - June 2023_

- Implemented a schema-driven validation tool generating record-level checks from external specifications, eliminating iterative reprocessing and reducing failure diagnosis time by 95%.

## Teaching

### DevOps Workshop, Vidhyavardhaka College of Engineering, Mysuru

_September 2023_

Designed and delivered a five-day hands-on workshop for faculty covering containerization, CI/CD, and deployment workflows.
