---
id: roadmap.md
title: Milvus Roadmap
---
# Milvus Roadmap

#### Milvus 2.0 - Release Candidate of distributed vector database
- Highly available with fully managed failure recovery and service discovery
- Support for scalar filtering and point query
- Provides highly abstract ORM-style APIs
- Offers four levels of tunable consistency: strong, bounded staleness, session, consistent prefix



#### Milvus 2.1 - Full-fledged version including complete set of DML functions
- Supports delete and update operations
- Supports string and varbinary data types
- Vector similarity search by distance
- Segment compaction that saves disk space and optimizes query performance
- Implements load balancing for Milvus Cluster
- Kubernetes deployment ready to optimize resource allocation
- Expands the Milvus ecosystem with support for mainstream extensions such as Apache Spark and Flink connector



#### Milvus 2.2 - A cloud-native vector database
- Adds access control to ensure data security in multi-tenant scenarios
- Support for query node isolation for exclusive access
- Supports bulk insert to improve efficiency
- A cluster protection mechanism featuring traffic control and back pressure
- Improves observability for failover and failback through distributed tracing and log aggregation
- Embedded Milvus that runs on laptops and feature out-of-the-box deployment in cloud production environments
- Integrates stream and batch processing through Kafka/Pulsar connector
- Multi-machine, multi-site deployment and multi-cloud integration
- Supports memory replicas for higher availability and optimized computing performance 

#### Long-term Milvus features
- Federated queries across operational databases, data warehouses, and data lakes
- Supports time travel to any specified point in time
- Separates hot data storage from cold data storage for more efficient resource allocation
- Adopts incremental backup to save time and disk space
- Adopts cost-based query optimization algorithm to improve query efficiency
- Supports on-disk vector indexing
- Supports change data capture to facilitate data integration
- Offers embedding-as-service through data importer/transformer
