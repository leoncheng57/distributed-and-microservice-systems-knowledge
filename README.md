# Distributed and Microservice Systems Knowledge

A personal collection of distributed and microservice systems concepts, patterns, and study notes.

## GitHub Pages

This repository is configured for GitHub Pages using the workflow in `.github/workflows/pages.yml`.
GitHub Pages is configured with **Source: GitHub Actions**, so pushes to `main` deploy the static site.
The public site will be available at:

https://leoncheng.dev/distributed-and-microservice-systems-knowledge/

## Topics

- **[Kafka vs SQS vs RabbitMQ (+ Kinesis, NATS, Pulsar, Redis Streams)](kafka-vs-sqs-rabbitmq.html)** — Senior SWE-level deep dive covering architecture internals, failure semantics, replication, backpressure, delivery guarantees, and production trade-offs. Includes SVG diagrams.
- **[Database Partitioning & Sharding Deep Dive](database-partitioning-and-sharding.html)** — Senior SWE-level practical guide to partitioning vs sharding, shard key strategies, rebalancing and online migrations, interview cheat sheet, and anonymized war stories.
- **[Consensus Deep Dive (Raft, Paxos, ZAB, BFT)](consensus-raft-paxos.html)** — Senior SWE-level guide to distributed consensus covering leader election, log replication, quorums, safety/liveness, FLP & CAP, interview cheat sheet, and production gotchas. Includes SVG diagrams.
