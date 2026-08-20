### Knowledge Map

```
Backend Engineering
│
├── Fundamentals
│   ├── Computer Networking
│   ├── Computer Systems
│   └── Distributed Systems
│
├── Software
│   ├── Software Engineering
│   │   └── CI/CD
│   │
│   ├── Java
│   ├── JVM
│   ├── Spring
│   │
│   └── Data
│       ├── Database
│       ├── ORM
│       ├── Cache
│       ├── Messaging / Streaming
│       └── Search
│
├── Production
│   ├── Security
│   └── Observability
│
└── Infrastructure
    ├── AWS
    └── Kubernetes
```

### Information Sources

- 📘 Learn: 한 번 체계적으로 공부할 가치가 큼
- 📖 Reference: 필요할 때 찾아보는 것으로 충분
- 📜 Spec: 정확한 의미가 필요할 때 내려가는 source of truth
- 📄 Deep Dive: 관심/문제가 생겼을 때
- 🎓 Course: 강의가 책보다 적합

| Category           | Topic                       | Information Source                                                | Type              | 우선도              |
| ------------------ | --------------------------- | ----------------------------------------------------------------- | ----------------- | ---------------- |
| **Fundamentals**   | **Computer Networking**     | **Kurose & Ross — Computer Networking: A Top-Down Approach**      | 📘 Learn          | **Core**         |
|                    |                             | **MDN Web Docs**                                                  | 📖 Reference      | Core             |
|                    |                             | **RFC 9110 / 9111 / 9112**                                        | 📜 Spec           | 필요 시             |
|                    | **Computer Systems**        | **CSAPP — Computer Systems: A Programmer's Perspective**          | 📘 Learn          | **Core**         |
|                    | **Distributed Systems**     | **DDIA — Designing Data-Intensive Applications**                  | 📘 Learn          | **Core**         |
|                    |                             | **Raft / Dynamo / Spanner papers**                                | 📄 Deep Dive      | 필요 시             |
| **Software**       | **Software Engineering**    | **A Philosophy of Software Design**                               | 📘 Learn          | **Core**         |
|                    |                             | **Refactoring — Martin Fowler**                                   | 📘 Learn / Ref    | 추천               |
|                    |                             | **Continuous Delivery — Humble & Farley**                         | 📘 Learn          | 선택               |
|                    |                             | **Martin Fowler — Software Delivery / CI articles**               | 📖 Reference      | 추천               |
|                    | **Java**                    | **Effective Java**                                                | 📘 Learn          | **Core**         |
|                    |                             | **JLS — Java Language Specification**                             | 📜 Spec           | 필요 시             |
|                    | **JVM**                     | **Java Performance — Scott Oaks**                                 | 📘 Learn          | 추천               |
|                    |                             | **JVMS — Java Virtual Machine Specification**                     | 📜 Spec           | 필요 시             |
|                    |                             | **OpenJDK Documentation**                                         | 📖 Reference      | 필요 시             |
|                    | **Spring**                  | **Spring Start Here**                                             | 📘 Learn          | **Core**         |
|                    |                             | **Spring Framework / Boot Docs**                                  | 📖 Reference      | **Core**         |
|                    | **Data**                    | **DDIA**                                                          | 📘 Learn          | **Core**         |
|                    | ↳ **Database**              | 사용하는 DB의 **Official Documentation**                               | 📖 Reference      | **Core**         |
|                    |                             | PostgreSQL이라면 transaction / MVCC / locking / indexes / EXPLAIN 중심 | 📖 Reference      | 추천               |
|                    | ↳ **ORM**                   | **Hibernate Introduction / ORM User Guide**                       | 📘 Learn + 📖 Ref | **Core**         |
|                    |                             | **Jakarta Persistence Specification**                             | 📜 Spec           | 필요 시             |
|                    |                             | **Spring Data JPA Docs**                                          | 📖 Reference      | **Core**         |
|                    |                             | **High-Performance Java Persistence**                             | 📘 Deep Learn     | 선택               |
|                    | ↳ **Cache**                 | **Redis Docs**                                                    | 📖 Reference      | 충분               |
|                    | ↳ **Messaging / Streaming** | **Kafka Docs**                                                    | 📖 Reference      | **Core if used** |
|                    | ↳ **Search**                | **OpenSearch / Elasticsearch Docs**                               | 📖 Reference      | 충분               |
| **Production**     | **Security**                | **OWASP Top 10**                                                  | 📘 Overview       | **Core**         |
|                    |                             | **OWASP Cheat Sheet Series**                                      | 📖 Reference      | **Core**         |
|                    |                             | **OWASP ASVS**                                                    | 📜 Standard       | 필요 시             |
|                    | **Observability**           | **Google SRE Book**                                               | 📘 Learn          | **Core**         |
|                    |                             | **OpenTelemetry Docs**                                            | 📖 Reference      | **Core**         |
| **Infrastructure** | **AWS**                     | **Adrian Cantrill SAA → SAP**                                     | 🎓 Learn          | **Core**         |
|                    |                             | **AWS Documentation**                                             | 📖 Reference      | **Core**         |
|                    |                             | **AWS Well-Architected Framework**                                | 📘 Architecture   | 추천               |
|                    |                             | **Amazon Builders' Library**                                      | 📄 Deep Dive      | 추천               |
|                    | **Kubernetes**              | **Kubernetes Basics + Concepts**                                  | 📘 Learn          | **Core**         |
|                    |                             | **Kubernetes Tasks / Reference / API Docs**                       | 📖 Reference      | **Core**         |


### primary learning track

```
Fundamentals
├─ Networking             → Kurose & Ross
├─ Computer Systems       → CSAPP
└─ Distributed Systems    → DDIA

Software
├─ Software Engineering   → A Philosophy of Software Design
├─ Java                   → Effective Java
├─ JVM                    → 
├─ Spring                 → Spring Start Here
└─ Data
   └─ ORM                 → Hibernate Introduction

Production
├─ Security               → OWASP Top 10
└─ Observability          → 

Infrastructure
├─ AWS                    → Cantrill SAA → SAP
└─ Kubernetes             → Kubernetes Basics → Concepts
```
