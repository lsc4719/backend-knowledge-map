### My Track

- [ ] Kurose&Ross
- [ ] dev.java
- [ ] Cantrill SAA

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
│   │   ├── API Design
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
│   ├── Reliability
│   ├── Observability
│   ├── Performance
│   ├── Security
│   └── Experimentation
│       └── A/B Testing
│
└── Infrastructure
    ├── AWS
    └── Kubernetes
```

### Resources

| Type             | Meaning                                                   |
| ---------------- | --------------------------------------------------------- |
| 📘 **Learn**     | Material for systematic, start-to-finish learning        |
| 📖 **Reference** | Official documentation or references to consult as needed |
| 📜 **Spec**      | Standards and specifications                              |
| 📄 **Deep Dive** | Material for deeper study after the fundamentals          |
| 🎓 **Course**    | Instructor-led or lecture-based learning material         |

| Priority        | Meaning                                             |
| --------------- | --------------------------------------------------- |
| **Core**        | Prioritize for backend engineering fundamentals    |
| **Recommended** | Worth studying after Core resources                 |
| **As needed**   | Consult when a practical need arises                |
| **Optional**    | Study depending on interest or context              |

| Category           | Topic                       | Resource                                                                                  | Type         | Priority    |
| ------------------ | --------------------------- | ----------------------------------------------------------------------------------------- | ------------ | ----------- |
| **Fundamentals**   | **Computer Networking**     | **Computer Networking: A Top-Down Approach, 9th Edition — Kurose & Ross**                  | 📘 Learn     | **Core**    |
|                    |                             | **MDN Web Docs — HTTP**                                                                   | 📖 Reference | **Core**    |
|                    |                             | **RFC 9110 / 9111 / 9112**                                                                | 📜 Spec      | As needed   |
|                    | **Computer Systems**        | **Computer Systems: A Programmer's Perspective (CSAPP), 3rd Edition**                      | 📘 Learn     | **Core**    |
|                    | **Distributed Systems**     | **Designing Data-Intensive Applications (DDIA), 2nd Edition — Kleppmann & Riccomini**      | 📘 Learn     | **Core**    |
|                    |                             | **Raft / Dynamo / Spanner Papers**                                                        | 📄 Deep Dive | As needed   |
| **Software**       | **Software Engineering**    | **A Philosophy of Software Design, 2nd Edition**                                           | 📘 Learn     | **Core**    |
|                    |                             | **Refactoring: Improving the Design of Existing Code, 2nd Edition — Martin Fowler**        | 📘 Learn     | Recommended |
|                    | ↳ **API Design**            | **API Design Patterns — JJ Geewax**                                                       | 📘 Learn     | **Core**    |
|                    | ↳ **Testing**               | **Martin Fowler — Testing Articles**                                                      | 📄 Deep Dive | Recommended |
|                    |                             | **JUnit User Guide**                                                                      | 📖 Reference | **Core**    |
|                    |                             | **Testcontainers Documentation**                                                          | 📖 Reference | Recommended |
|                    |                             | **Mockito Documentation**                                                                 | 📖 Reference | As needed   |
|                    | ↳ **CI/CD**                 | **Continuous Delivery — Humble & Farley**                                                 | 📘 Learn     | Recommended |
|                    |                             | **Martin Fowler — Continuous Integration / Delivery**                                     | 📖 Reference | Recommended |
|                    |                             | **LaunchDarkly Documentation — Feature Flags / Progressive Delivery**                     | 📖 Reference | Recommended |
|                    | **Java**                    | **Effective Java, 3rd Edition**                                                           | 📘 Learn     | **Core**    |
|                    |                             | **dev.java — Learn Java**                                                                 | 📖 Reference | **Core**    |
|                    |                             | **Java Language Specification (JLS)**                                                     | 📜 Spec      | As needed   |
|                    | **JVM**                     | **Java Performance, 2nd Edition — Scott Oaks**                                            | 📘 Learn     | Recommended |
|                    |                             | **Java Virtual Machine Specification (JVMS)**                                             | 📜 Spec      | As needed   |
|                    |                             | **OpenJDK Documentation**                                                                 | 📖 Reference | As needed   |
|                    | **Spring**                  | **Spring Start Here — Laurentiu Spilca**                                                  | 📘 Learn     | **Core**    |
|                    |                             | **Spring Framework / Spring Boot Documentation**                                          | 📖 Reference | **Core**    |
|                    |                             | **Spring MVC Documentation**                                                              | 📖 Reference | **Core**    |
|                    |                             | **Spring WebFlux Documentation**                                                          | 📖 Reference | As needed   |
|                    |                             | **Project Reactor Reference Guide**                                                       | 📖 Reference | As needed   |
|                    |                             | **Apache Tomcat Documentation**                                                           | 📖 Reference | As needed   |
|                    |                             | **Netty Documentation**                                                                   | 📖 Reference | As needed   |
|                    | **Data**                    | **Designing Data-Intensive Applications (DDIA), 2nd Edition — Kleppmann & Riccomini**      | 📘 Learn     | **Core**    |
|                    | ↳ **Database**              | **Database Official Documentation**                                                       | 📖 Reference | **Core**    |
|                    |                             | **PostgreSQL Documentation — Transactions / MVCC / Locking / Indexes / EXPLAIN**          | 📖 Reference | Recommended |
|                    |                             | **HikariCP Documentation**                                                                | 📖 Reference | Recommended |
|                    | ↳ **ORM**                   | **Hibernate ORM User Guide**                                                              | 📖 Reference | **Core**    |
|                    |                             | **Jakarta Persistence Specification**                                                     | 📜 Spec      | As needed   |
|                    |                             | **Spring Data JPA Documentation**                                                         | 📖 Reference | **Core**    |
|                    |                             | **High-Performance Java Persistence**                                                     | 📄 Deep Dive | Optional    |
|                    | ↳ **Cache**                 | **Redis Documentation**                                                                   | 📖 Reference | As needed   |
|                    | ↳ **Messaging / Streaming** | **Apache Kafka Documentation**                                                            | 📖 Reference | As needed   |
|                    | ↳ **Search**                | **OpenSearch / Elasticsearch Documentation**                                              | 📖 Reference | As needed   |
| **Production**     | **Reliability**             | **Site Reliability Engineering — Google**                                                 | 📘 Learn     | Recommended |
|                    | **Observability**           | **Observability Engineering, 2nd Edition — Majors, Fong-Jones & Miranda**                  | 📘 Learn     | Recommended |
|                    |                             | **OpenTelemetry Documentation**                                                           | 📖 Reference | **Core**    |
|                    | **Performance**             | **Systems Performance: Enterprise and the Cloud, 2nd Edition — Brendan Gregg**             | 📘 Learn     | Recommended |
|                    | **Security**                | **OWASP Top 10:2025**                                                                     | 📘 Learn     | **Core**    |
|                    |                             | **OWASP Cheat Sheet Series**                                                              | 📖 Reference | **Core**    |
|                    |                             | **OWASP ASVS**                                                                            | 📜 Spec      | As needed   |
|                    | **Experimentation**         | **Trustworthy Online Controlled Experiments — Kohavi, Tang & Xu**                         | 📘 Learn     | Recommended |
| **Infrastructure** | **AWS**                     | **Adrian Cantrill — AWS SAA → SAP**                                                       | 🎓 Course    | **Core**    |
|                    |                             | **AWS Documentation**                                                                     | 📖 Reference | **Core**    |
|                    |                             | **AWS Well-Architected Framework**                                                        | 📖 Reference | Recommended |
|                    |                             | **Amazon Builders' Library**                                                              | 📄 Deep Dive | Recommended |
|                    | **Kubernetes**              | **Kubernetes Basics / Concepts**                                                          | 📘 Learn     | **Core**    |
|                    |                             | **Kubernetes Tasks / Reference / API Documentation**                                      | 📖 Reference | **Core**    |

### Primary Learning Track

Knowledge Map annotated with a small set of primary learning resources. Topics without a mapped resource remain part of the track.

```
Fundamentals
├─ Computer Networking       → Kurose & Ross, 9th Edition
├─ Computer Systems          → CSAPP, 3rd Edition
└─ Distributed Systems       → DDIA, 2nd Edition

Software
├─ Software Engineering      → A Philosophy of Software Design, 2nd Edition
│  ├─ API Design             → API Design Patterns
│  ├─ Testing
│  └─ CI/CD
├─ Java                      → Effective Java, 3rd Edition
├─ JVM
├─ Spring                    → Spring Start Here
└─ Data                      → DDIA, 2nd Edition
   ├─ Database
   ├─ ORM
   ├─ Cache
   ├─ Messaging / Streaming
   └─ Search

Production
├─ Reliability
├─ Observability
├─ Performance
├─ Security                  → OWASP Top 10:2025
└─ Experimentation
   └─ A/B Testing

Infrastructure
├─ AWS                       → Cantrill SAA → SAP
└─ Kubernetes                → Kubernetes Basics → Concepts
```
