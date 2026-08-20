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
│   │   ├── Testing
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

| Type             | 의미                    |
| ---------------- | --------------------- |
| 📘 **Learn**     | 처음부터 체계적으로 학습할 자료     |
| 📖 **Reference** | 필요할 때 찾아보는 공식 문서/레퍼런스 |
| 📜 **Spec**      | 표준, 명세, specification |
| 📄 **Deep Dive** | 기본 학습 이후 더 깊게 파고들 자료  |
| 🎓 **Course**    | 강의 기반 학습 자료           |

| Priority        | 의미                  |
| --------------- | ------------------- |
| **Core**        | 백엔드 엔지니어라면 우선적으로 학습 |
| **Recommended** | Core 이후 학습하면 좋은 자료  |
| **As needed**   | 실제 필요가 생겼을 때 참고     |
| **Optional**    | 관심/상황에 따라 선택        |

| Category           | Topic                       | Resource                                                                         | Type         | Priority    |
| ------------------ | --------------------------- | -------------------------------------------------------------------------------- | ------------ | ----------- |
| **Fundamentals**   | **Computer Networking**     | **Computer Networking: A Top-Down Approach — Kurose & Ross**                     | 📘 Learn     | **Core**    |
|                    |                             | **MDN Web Docs — HTTP**                                                          | 📖 Reference | **Core**    |
|                    |                             | **RFC 9110 / 9111 / 9112**                                                       | 📜 Spec      | As needed   |
|                    | **Computer Systems**        | **Computer Systems: A Programmer's Perspective (CSAPP)**                         | 📘 Learn     | **Core**    |
|                    | **Distributed Systems**     | **Designing Data-Intensive Applications (DDIA)**                                 | 📘 Learn     | **Core**    |
|                    |                             | **Raft / Dynamo / Spanner Papers**                                               | 📄 Deep Dive | As needed   |
| **Software**       | **Software Engineering**    | **A Philosophy of Software Design**                                              | 📘 Learn     | **Core**    |
|                    |                             | **Refactoring — Martin Fowler**                                                  | 📘 Learn     | Recommended |
|                    | ↳ **Testing**               | **Martin Fowler — Testing**                                                      | 📘 Learn     | **Core**    |
|                    |                             | **JUnit User Guide**                                                             | 📖 Reference | **Core**    |
|                    |                             | **Testcontainers Documentation**                                                 | 📖 Reference | Recommended |
|                    |                             | **Mockito Documentation**                                                        | 📖 Reference | As needed   |
|                    | ↳ **CI/CD**                 | **Continuous Delivery — Humble & Farley**                                        | 📘 Learn     | Recommended |
|                    |                             | **Martin Fowler — Continuous Integration / Delivery**                            | 📖 Reference | Recommended |
|                    | **Java**                    | **Effective Java**                                                               | 📘 Learn     | **Core**    |
|                    |                             | **Java Language Specification (JLS)**                                            | 📜 Spec      | As needed   |
|                    | **JVM**                     | **Java Performance — Scott Oaks**                                                | 📘 Learn     | Recommended |
|                    |                             | **Java Virtual Machine Specification (JVMS)**                                    | 📜 Spec      | As needed   |
|                    |                             | **OpenJDK Documentation**                                                        | 📖 Reference | As needed   |
|                    | **Spring**                  | **Spring Start Here**                                                            | 📘 Learn     | **Core**    |
|                    |                             | **Spring Framework / Spring Boot Documentation**                                 | 📖 Reference | **Core**    |
|                    | **Data**                    | **Designing Data-Intensive Applications (DDIA)**                                 | 📘 Learn     | **Core**    |
|                    | ↳ **Database**              | **Database Official Documentation**                                              | 📖 Reference | **Core**    |
|                    |                             | **PostgreSQL Documentation — Transactions / MVCC / Locking / Indexes / EXPLAIN** | 📖 Reference | Recommended |
|                    | ↳ **ORM**                   | **Hibernate ORM User Guide**                                                     | 📖 Reference | **Core**    |
|                    |                             | **Jakarta Persistence Specification**                                            | 📜 Spec      | As needed   |
|                    |                             | **Spring Data JPA Documentation**                                                | 📖 Reference | **Core**    |
|                    |                             | **High-Performance Java Persistence**                                            | 📄 Deep Dive | Optional    |
|                    | ↳ **Cache**                 | **Redis Documentation**                                                          | 📖 Reference | As needed   |
|                    | ↳ **Messaging / Streaming** | **Apache Kafka Documentation**                                                   | 📖 Reference | As needed   |
|                    | ↳ **Search**                | **OpenSearch / Elasticsearch Documentation**                                     | 📖 Reference | As needed   |
| **Production**     | **Security**                | **OWASP Top 10**                                                                 | 📘 Learn     | **Core**    |
|                    |                             | **OWASP Cheat Sheet Series**                                                     | 📖 Reference | **Core**    |
|                    |                             | **OWASP ASVS**                                                                   | 📜 Spec      | As needed   |
|                    | **Observability**           | **Site Reliability Engineering — Google**                                        | 📘 Learn     | **Core**    |
|                    |                             | **OpenTelemetry Documentation**                                                  | 📖 Reference | **Core**    |
| **Infrastructure** | **AWS**                     | **Adrian Cantrill — AWS SAA → SAP**                                              | 🎓 Course    | **Core**    |
|                    |                             | **AWS Documentation**                                                            | 📖 Reference | **Core**    |
|                    |                             | **AWS Well-Architected Framework**                                               | 📖 Reference | Recommended |
|                    |                             | **Amazon Builders' Library**                                                     | 📄 Deep Dive | Recommended |
|                    | **Kubernetes**              | **Kubernetes Basics / Concepts**                                                 | 📘 Learn     | **Core**    |
|                    |                             | **Kubernetes Tasks / Reference / API Documentation**                             | 📖 Reference | **Core**    |


### Primary Learning Track

```
Fundamentals
├─ Networking             → Kurose & Ross
├─ Computer Systems       → CSAPP
└─ Distributed Systems    → DDIA

Software
├─ Software Engineering   → A Philosophy of Software Design
├─ Java                   → Effective Java
├─ JVM                    
├─ Spring                 → Spring Start Here
└─ Data
   └─ ORM                 → Hibernate Introduction

Production
├─ Security               → OWASP Top 10
└─ Observability           

Infrastructure
├─ AWS                    → Cantrill SAA → SAP
└─ Kubernetes             → Kubernetes Basics → Concepts
```
