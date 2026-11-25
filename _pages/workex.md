---
layout: default
title: work experience
permalink: /work-experience/
nav: true
nav_order: 3
---

## Georgia Institute of Technology

### Graduate Research, Systems for AI Lab

_August 2026 - Present_

- Built gRPC speech recognition workers for MetaServe that support seven decoding configurations across FastConformer CTC, FastConformer RNN-T, and OpenAI Whisper.

## JPMorgan Chase & Co.

### Software Engineer II

_January 2025 - July 2026_

- Owned the design and production rollout of a distributed PySpark and Java platform that replaced a legacy stack that used a proprietary DSL on Hadoop alongside Informatica ETL.
- Redesigned platform execution to eliminate Databricks-DynamoDB state synchronization, removing a fragile distributed dependency and improving throughput by up to 80%.
- Built an application-layer generator that automatically produced workload-optimized DAGs for Spark to execute. For instance, on a sparse-correction workload with a ~60-operation DAG and up to 10 million records, it cut runtime by 85%, from about 10 minutes to 1.5 minutes.
- Redesigned partitioning and tuned parallelism to mitigate shuffle bottlenecks, reducing cluster compute costs by ~40% without performance degradation.
- Optimized table partitioning using Spark execution plans and Databricks query profiles, increasing data skipping from 65% to 98% and reducing dashboard refresh latency from ~5 minutes to ~10 seconds.

I held full technical design and implementation ownership. My manager provided domain expertise, while our PM/QA counterpart handled project coordination, regression testing, and data reconciliation.

### Software Engineer I

_January 2023 - December 2024_

- Profiled memory growth of a Polars-based transformation in AWS Lambda; introduced lazy evaluation and explicit object lifecycle control, reducing peak memory allocation by 60% and stabilizing execution latency.
- Brought up a multi-node ingestion system on Kubernetes (EKS + NiFi), implemented Airflow orchestration for distributed workflows, and operated cross-service data movement pipelines in production.
- Implemented a schema-driven validation tool generating record-level checks from external specifications, eliminating iterative reprocessing and reducing failure diagnosis time by 95%.
- Earned accelerated promotion to Software Engineer II for ownership of distributed data infrastructure and production performance engineering.

## Teaching

### Graduate Teaching Assistant, Georgia Institute of Technology

_August 2026 - Present_

- **Fall 2026** · CS 6200, Graduate Introduction to Operating Systems (OMSCS)

### DevOps Workshop, Vidhyavardhaka College of Engineering, Mysuru

_September 2023_

Designed and delivered a five-day hands-on workshop for faculty covering containerization, CI/CD, and deployment workflows.
