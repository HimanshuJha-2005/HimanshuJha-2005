# Himanshu Jha

Backend Engineer specializing in concurrent Java systems, transactional architectures, and resilient distributed data pipelines.

[LinkedIn](https://www.linkedin.com/in/himanshu-jha-728834337/) • [Email](mailto:07himanshuraj@gmail.com)

---

### Core Engineering Focus

- **Systems & Concurrency:** Java 21 Virtual Threads, non-blocking I/O, custom protocol probes, thread-safe state machines.
- **Transactional Consistency:** PostgreSQL row-level pessimistic locking (`SELECT ... FOR UPDATE`), distributed idempotency keys, ACID integrity.
- **Data & AI Infrastructure:** Property graph persistence (FalkorDB over Redis protocol with GraphBLAS), explainable retrieval, FastAPI services.
- **Reliability & Delivery:** CI-gated testing (JUnit, pytest), containerized setups (Docker Compose), static analysis (SpotBugs zero-defect standards), SARIF output formatting.

---

### Selected Projects

| System | Architecture & Core Capabilities | Verification & Benchmarks |
| :--- | :--- | :--- |
| **[VulnScan](https://github.com/HimanshuJha-2005/vulnscan)** | Multithreaded network vulnerability scanner in Java 21 on virtual threads. Features 13-probe service fingerprinting (HTTP, SSH, DBs), SPI plugin engine with 10 protocol checks, SQLite scan resume, and SARIF/JSON reporting. | 52+ unit tests, zero SpotBugs findings, GitHub Actions CI |
| **[Continuum](https://github.com/HimanshuJha-2005/continuum)** | Cross-agent graph memory engine built for WeMakeDevs × FalkorDB Graph Hacks. Anchors multi-agent context to a shared FalkorDB property graph with live Cypher traces and React/Cytoscape visualization. | Hackathon project, Docker Compose, AWS EC2 deployable |
| **[ForgeCommerce](https://github.com/HimanshuJha-2005/ForgeCommerce)** | Commerce engine with Spring Boot, PostgreSQL, and React. Prevents overselling via single-transaction pessimistic locking, enforces client idempotency keys, and manages strict order state transitions. | 27 integration tests, Docker Compose, CI-tested |
| **[Sigma Rule Contribution](https://github.com/HimanshuJha-2005/sigma-rule-contribution)** | Upstream detection engineering for Kubernetes ephemeral-container abuse ([SigmaHQ PR #6499](https://github.com/SigmaHQ/sigma/pull/6499)). | `sigma check` clean, Splunk & Elastic rule compilation |

---

### Technical Toolbelt

- **Languages:** Java, Python, JavaScript, SQL, Bash
- **Frameworks & Runtimes:** Spring Boot, FastAPI, Node.js, Express.js
- **Databases & Caching:** PostgreSQL, FalkorDB, Redis, MongoDB, SQLite
- **Engineering Practices:** Docker & Docker Compose, GitHub Actions, SpotBugs, Maven, JUnit, Postman, Git
