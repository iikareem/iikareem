# Kareem Ashraf

**Backend Software Engineer · Distributed Systems · Database Internals · Performance**

I build backend systems—and study them through deliberate learning and practice—to make how they behave under real conditions easy to reason about: architecture, failure modes, and performance. I care about clear design, explicit trade-offs, and measuring systems under load rather than assuming they work.

Most of my work uses **TypeScript, Node.js, and NestJS**, supported by the data and infrastructure tools that fit the problem. I write about what I learn on [Hashnode](https://kareemdev.hashnode.dev).

---

## Focus

- **Distributed systems:** event-driven design, Kafka, messaging, consistency, and fault tolerance
- **Data systems:** relational modeling, query execution, indexing, OLAP, analytical pipelines, and Neo4j/graph data
- **Backend performance:** caching, queues, concurrency, benchmarking, and load testing
- **Operability:** observability, failure drills, containers, and delivery automation

**Stack:** TypeScript · Node.js · NestJS · PostgreSQL · Redis · Kafka · DuckDB · Neo4j · Docker · Prometheus/Grafana

---

## Projects

Selected projects — newest first.

### [RideStream](https://github.com/iikareem/ride-stream)

A real-time ride-sharing GPS pipeline covering Kafka ingestion, stream processing, observability, and live client delivery.

**Technical highlight:** Built a three-broker KRaft cluster with Avro schema evolution, transactional ETA processing, ksqlDB anomaly detection, Prometheus/Grafana monitoring, and Redis GEO/Pub/Sub fan-out through Socket.IO.

### [Pitwall](https://github.com/iikareem/pitwall)

A Formula 1 OLAP engine that ingests real race data into a Parquet lake and serves analytics through NestJS and DuckDB.

**Technical highlight:** Modeled independent-grain facts with a Kimball-style star schema and built benchmarks that compare partition pruning and raw aggregation against materialized summaries.

### [GraphScholar](https://github.com/iikareem/GraphScholar)

A Graph RAG knowledge base that turns research papers into connected, queryable evidence for AI assistants.

**Technical highlight:** Built an end-to-end ArXiv ingestion pipeline for sections, citations, concepts, and embeddings, then exposed Neo4j graph and vector retrieval through five MCP tools over stdio and HTTP.

### [lite-q](https://github.com/iikareem/lite-q)

A persistent, zero-infrastructure task queue for Node.js, distributed as [`@km-dev/lite-q`](https://www.npmjs.com/package/@km-dev/lite-q).

**Technical highlight:** Implemented a SQLite WAL-backed job state machine with atomic claims, delayed and cron scheduling, exponential retries, Prometheus metrics, and separate concurrency paths for I/O handlers and worker-thread jobs.

### [Property Listings API](https://github.com/iikareem/property-listings-api)

A production-style NestJS API with advanced filtering, cursor pagination, Redis caching, containerized startup, and CI.

**Technical highlight:** Tested 100,000 seeded records with 50 concurrent k6 users, achieving 55.4 requests/second, 6.58 ms p95 latency, and a 0% error rate on a local development machine.

Also: [Competitive Programming](https://github.com/iikareem/Competitive-Programming) — Java and C++ solutions from [Codeforces](https://codeforces.com/profile/iikareem).

---

## Study notes

I keep structured notes on distributed systems, databases, AWS, backend engineering, and interview problems in [**my-study-notes**](https://github.com/iikareem/my-study-notes).

---

## Writing

On [Hashnode](https://kareemdev.hashnode.dev) I write about how I learn—lessons from production-grade work through my career, and from side projects, databases, networking, and the systems behind them.

Selected posts:

- [When One Database Is No Longer Enough: A Practical Guide to Distributed Transactions](https://kareemdev.hashnode.dev/when-one-database-is-no-longer-enough-a-practical-guide-to-distributed-transactions)
- [Latency, Throughput & the Laws That Govern Every System Under Load](https://kareemdev.hashnode.dev/latency-throughput-the-laws-that-govern-every-system-under-load)
- [What I Learned Building Real Observability Into an App](https://kareemdev.hashnode.dev/what-i-learned-building-real-observability-into-an-app)

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://kareem-dev-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kareem-ashraf-8934511b9/)
[![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://kareemdev.hashnode.dev)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kareem.ashraf.dev@gmail.com)

---

*Open to collaborating on distributed systems, database internals, backend infrastructure, and developer tooling.*
