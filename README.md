# Awesome Enterprise Programming

A curated catalog of technologies, platforms, standards, and practices for building, integrating, operating, and governing enterprise software.

> This list intentionally focuses on enterprise concerns: longevity, integration, security, compliance, governance, reliability, transactionality, and operational scale. It is not a list of every popular developer tool.

The catalog is organized from foundational architecture and runtimes through integration, data, infrastructure, security, operations, and business domains. Vendor products are included alongside open standards and implementation practices; no single vendor or cloud should be treated as a default.

## Contents

- [Enterprise Architecture](#enterprise-architecture)
- [Languages and Runtimes](#languages-and-runtimes)
- [Java and Jakarta Enterprise](#java-and-jakarta-enterprise)
- [Enterprise Frameworks](#enterprise-frameworks)
- [Application Servers and Platforms](#application-servers-and-platforms)
- [API Management and Integration](#api-management-and-integration)
- [Messaging and Event Streaming](#messaging-and-event-streaming)
- [Databases and Data Platforms](#databases-and-data-platforms)
- [Cloud and Hybrid Infrastructure](#cloud-and-hybrid-infrastructure)
- [Containers and Platform Engineering](#containers-and-platform-engineering)
- [Identity, Security, and Secrets](#identity-security-and-secrets)
- [Observability and Operations](#observability-and-operations)
- [Data, Analytics, and AI](#data-analytics-and-ai)
- [Business Platforms](#business-platforms)
- [Delivery, Quality, and Governance](#delivery-quality-and-governance)
- [Enterprise Standards](#enterprise-standards)
- [Deep Enterprise Infrastructure](#deep-enterprise-infrastructure)
- [Mainframe and Transaction Processing](#mainframe-and-transaction-processing)
- [Enterprise Networking and Storage](#enterprise-networking-and-storage)
- [Specialized Enterprise Software](#specialized-enterprise-software)
- [Books and Reference Material](#books-and-reference-material)

## Enterprise Architecture

- **Architecture styles** — layered architecture, modular monoliths, service-oriented architecture (SOA), microservices, event-driven architecture, hexagonal architecture, clean architecture, domain-driven design (DDD), CQRS, event sourcing, and strangler-fig modernization.
- **Enterprise Architecture frameworks** — [TOGAF](https://www.opengroup.org/togaf), [ArchiMate](https://www.opengroup.org/archimate-forum/archimate-overview), [Zachman Framework](https://www.zachman.com/), and [FEAF](https://www.archives.gov/records-mgmt/policy/feaf).
- **Modeling and decision records** — [C4 model](https://c4model.com/), UML, BPMN, ArchiMate, ADRs, capability maps, value streams, and technology radar practices.
- **Enterprise concerns** — data ownership, service catalogs, portfolio management, disaster recovery, business continuity, RTO/RPO, technical debt, FinOps, and vendor management.

## Languages and Runtimes

### JVM

- **Java** — long-term enterprise platform with strong compatibility, tooling, and vendor support.
- **Kotlin** — JVM language for services, Android, and Spring applications.
- **Scala** — functional and distributed data systems, including Akka-based platforms.
- **Groovy** — Gradle, Jenkins, scripting, and legacy JVM applications.
- **Clojure** — functional JVM systems and data-oriented services.
- **Java runtimes** — [OpenJDK](https://openjdk.org/), Eclipse Temurin, Amazon Corretto, Azul Platform, Oracle JDK, GraalVM, and IBM Semeru.

### Microsoft and native platforms

- **C#/.NET** — enterprise APIs, Windows integration, Azure workloads, desktop systems, and high-throughput services.
- **F#** — domain-heavy and functional .NET applications.
- **C/C++** — high-performance systems, embedded enterprise appliances, databases, and trading infrastructure.
- **Rust** — secure systems services, infrastructure components, and performance-sensitive platforms.
- **D** and **Ada/SPARK** — specialized safety- and reliability-critical systems.

### Other enterprise languages

- **Go** — infrastructure, cloud control planes, networking, and operational services.
- **Python** — automation, data platforms, integration, and internal enterprise services.
- **JavaScript/TypeScript** — enterprise web applications, Node.js services, and platform tooling.
- **PHP** — established business applications and content platforms.
- **Ruby** — business applications and internal platforms.
- **COBOL** — mainframe and long-lived financial, government, and insurance systems.
- **PL/I, Fortran, RPG, ABAP, and PowerBuilder** — specialized legacy, ERP, scientific, and IBM i estates.

## Java and Jakarta Enterprise

- [Java SE](https://docs.oracle.com/en/java/javase/) — language and standard runtime.
- [Jakarta EE](https://jakarta.ee/) — enterprise APIs for web, persistence, messaging, transactions, security, and REST.
- [Eclipse MicroProfile](https://microprofile.io/) — specifications for Java microservices and cloud-native applications.
- [Spring](https://spring.io/) — Spring Framework, Spring Boot, Spring Security, Spring Data, Spring Integration, Spring Batch, Spring Cloud, and Spring Authorization Server.
- [Quarkus](https://quarkus.io/) — Kubernetes-native Java with fast startup and native compilation.
- [Micronaut](https://micronaut.io/) — compile-time dependency injection and cloud-native services.
- [Helidon](https://helidon.io/) — lightweight Java microservices.
- [Open Liberty](https://openliberty.io/), [Payara](https://www.payara.fish/), [WildFly](https://www.wildfly.org/), [Eclipse GlassFish](https://glassfish.org/), and [Apache Tomcat](https://tomcat.apache.org/).
- Java enterprise APIs — JPA, JTA, CDI, JAX-RS, Servlet, WebSocket, JMS, Bean Validation, JSON-B, JSON-P, and Jakarta Security.
- Java tooling — Maven, Gradle, Bazel, JUnit, Testcontainers, Mockito, Arquillian, Flyway, Liquibase, and OpenRewrite.

## Enterprise Frameworks

- **.NET** — ASP.NET Core, Entity Framework Core, Microsoft Orleans, Dapr, MassTransit, and Azure SDKs.
- **Python** — Django, FastAPI, Flask, Celery, SQLAlchemy, Pydantic, Airflow, and OpenTelemetry SDKs.
- **Go** — Gin, Echo, Chi, Fiber, ConnectRPC, gRPC-Go, Temporal SDK, and Operator SDK.
- **TypeScript** — NestJS, LoopBack, Nx, TypeORM, Prisma, and enterprise Angular.
- **PHP** — Symfony, Laravel, Laminas, Doctrine, and API Platform.
- **Ruby** — Rails, Hanami, Sidekiq, and dry-rb.
- **Rust** — Axum, Actix Web, Tokio, SQLx, and tonic.
- **Integration patterns** — Apache Camel, Spring Integration, Mule runtime, WSO2, and Enterprise Integration Patterns.

## Application Servers and Platforms

- IBM WebSphere, WebSphere Liberty, Oracle WebLogic, Red Hat JBoss EAP, WildFly, Payara, Open Liberty, Apache Tomcat, Eclipse GlassFish, and TIBCO BusinessWorks.
- Mainframe platforms — IBM z/OS, CICS, IMS, DB2 for z/OS, JCL, RACF, and IBM MQ.
- IBM i — IBM i operating system, Db2 for i, RPG, CL, ILE, and WebSphere Liberty.
- Enterprise portal and content platforms — Liferay, OpenText, Alfresco, Magnolia, and Adobe Experience Manager.

## API Management and Integration

- **API standards** — HTTP, REST, OpenAPI, JSON Schema, GraphQL, gRPC, SOAP, WSDL, XML Schema, WS-Security, OData, and AsyncAPI.
- **API gateways and management** — Kong, Tyk, WSO2 API Manager, IBM API Connect, Apigee, MuleSoft Anypoint, Azure API Management, AWS API Gateway, and Gravitee.
- **Enterprise integration** — IBM App Connect, IBM ACE, Oracle Integration, Boomi, MuleSoft, TIBCO, WSO2, Apache Camel, Spring Integration, and Apache Synapse.
- **Service mesh and traffic management** — Istio, Linkerd, Consul, Kuma, Envoy, and ambient mesh architectures.
- **Workflow and orchestration** — Camunda, Flowable, Activiti, Temporal, Netflix Conductor, Apache Airflow, and AWS Step Functions.

## Messaging and Event Streaming

- Apache Kafka, Confluent Platform, Redpanda, Apache Pulsar, NATS, RabbitMQ, ActiveMQ Artemis, IBM MQ, Solace PubSub+, TIBCO EMS, and Amazon MQ.
- Cloud messaging — Amazon SQS/SNS, Azure Service Bus/Event Grid, Google Pub/Sub, and OCI Streaming.
- Enterprise patterns — transactional outbox, idempotency, dead-letter queues, saga orchestration, exactly-once considerations, schema evolution, and event governance.
- Schema and registry tooling — Apicurio Registry, Confluent Schema Registry, Protocol Buffers, Avro, and JSON Schema.

## Databases and Data Platforms

### Relational and transactional

- Oracle Database, Microsoft SQL Server, IBM Db2, PostgreSQL, MariaDB, MySQL, SAP HANA, CockroachDB, YugabyteDB, and TiDB.
- Specialized systems — SQLite, Firebird, Informix, Teradata, Sybase ASE, and Apache Derby.
- Enterprise database tooling — Liquibase, Flyway, Oracle GoldenGate, Debezium, CDC, connection pools, read replicas, partitioning, and sharding.

### NoSQL and distributed storage

- MongoDB, Couchbase, Cassandra, ScyllaDB, Apache HBase, DynamoDB, Azure Cosmos DB, Neo4j, Amazon Neptune, Redis, Valkey, Hazelcast, and Aerospike.
- Search and indexing — Elasticsearch, OpenSearch, Solr, and Vespa.
- Object and file storage — Amazon S3, Azure Blob Storage, Google Cloud Storage, MinIO, Ceph, GlusterFS, and NetApp ONTAP.

### Data integration and governance

- Informatica, Talend, Pentaho, Apache NiFi, StreamSets, dbt, Trino, Presto, Denodo, and Data Virtualization.
- Catalog and governance — Collibra, Alation, Apache Atlas, DataHub, OpenMetadata, Great Expectations, and OpenLineage.

## Cloud and Hybrid Infrastructure

- **Cloud providers** — AWS, Microsoft Azure, Google Cloud, Oracle Cloud Infrastructure, IBM Cloud, Alibaba Cloud, and SAP Business Technology Platform.
- **Enterprise private cloud** — OpenStack, VMware Cloud Foundation, Nutanix, Red Hat OpenShift, Apache CloudStack, and Cloud Foundry.
- **Infrastructure as code** — Terraform/OpenTofu, Pulumi, Ansible, Puppet, Chef, Salt, Crossplane, AWS CloudFormation, Azure Bicep, and Google Cloud Deployment Manager.
- **Hybrid and multicloud** — Azure Arc, Google Anthos, AWS Outposts, VMware Tanzu, Red Hat Advanced Cluster Management, and cloud landing zones.

## Containers and Platform Engineering

- Kubernetes, OpenShift, Rancher, Tanzu Kubernetes Grid, Amazon EKS, Azure AKS, Google GKE, and IBM Red Hat platforms.
- Container runtimes — containerd, CRI-O, Docker Engine, Podman, and Buildah.
- Package and policy tools — Helm, Kustomize, Jsonnet, Carvel, Argo CD, Flux, Kyverno, and Open Policy Agent.
- Internal developer platforms — Backstage, Humanitec, Port, Crossplane compositions, developer portals, golden paths, and platform-as-a-product practices.
- Registries — Harbor, JFrog Artifactory, Sonatype Nexus, Amazon ECR, Azure Container Registry, and Google Artifact Registry.

## Identity, Security, and Secrets

- **Identity standards** — OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, LDAP, Kerberos, X.509, FIDO2/WebAuthn, and WS-Federation.
- **Identity platforms** — Microsoft Entra ID, Active Directory, Okta, Ping Identity, ForgeRock, Keycloak, Auth0, CyberArk, and SailPoint.
- **Secrets and keys** — HashiCorp Vault, CyberArk Conjur, AWS KMS/Secrets Manager, Azure Key Vault, Google Cloud KMS/Secret Manager, and HSMs.
- **Security tooling** — SAST, DAST, SCA, SBOM, dependency management, vulnerability scanning, SIEM, SOAR, EDR, WAF, PAM, zero trust, and secure software supply chains.
- **Standards and frameworks** — NIST CSF, NIST SP 800-53, ISO 27001, CIS Controls, OWASP ASVS, OWASP SAMM, PCI DSS, SOC 2, FedRAMP, HIPAA, GDPR, and regional privacy laws.

## Observability and Operations

- **Telemetry** — OpenTelemetry, Prometheus, Grafana, Loki, Tempo, Jaeger, Zipkin, Fluent Bit, Fluentd, and OpenSearch.
- **Commercial platforms** — Splunk, Dynatrace, New Relic, Datadog, AppDynamics, Elastic Observability, IBM Instana, and ScienceLogic.
- **Operations** — Nagios, Zabbix, Icinga, Checkmk, SolarWinds, PagerDuty, Opsgenie, ServiceNow ITOM, and Rundeck.
- **Reliability engineering** — SLOs/SLIs, error budgets, incident command, runbooks, capacity planning, chaos engineering, disaster recovery testing, and game days.
- **Log and audit requirements** — immutable audit trails, retention policies, correlation IDs, distributed tracing, privileged-action logging, and legal hold.

## Data, Analytics, and AI

- **Warehouses and lakehouses** — Snowflake, Databricks, BigQuery, Redshift, Synapse Analytics, Microsoft Fabric, Teradata Vantage, ClickHouse, Apache Iceberg, Delta Lake, and Apache Hudi.
- **Processing** — Apache Spark, Apache Flink, Apache Beam, Kafka Streams, Apache Samza, and Ray.
- **BI and reporting** — Power BI, Tableau, Qlik, Looker, MicroStrategy, SAP BusinessObjects, IBM Cognos, and JasperReports.
- **ML platforms** — MLflow, Kubeflow, Azure Machine Learning, Amazon SageMaker, Vertex AI, Dataiku, SAS, and IBM watsonx.
- **Enterprise AI concerns** — model governance, explainability, human approval, prompt security, data residency, model monitoring, lineage, and responsible AI.

## Business Platforms

- **ERP** — SAP S/4HANA, Oracle Fusion Cloud ERP, Microsoft Dynamics 365, Infor CloudSuite, NetSuite, and Odoo Enterprise.
- **CRM and customer platforms** — Salesforce, Microsoft Dynamics 365, SAP Customer Experience, Oracle CX, and ServiceNow.
- **HR and finance** — Workday, SAP SuccessFactors, Oracle HCM, UKG, ADP, Coupa, Ariba, and Kyriba.
- **Industry platforms** — Guidewire (insurance), Temenos and Finastra (banking), Epic and Cerner/Oracle Health (healthcare), and Siemens and PTC platforms (manufacturing).
- **Business process management** — SAP Build Process Automation, IBM BAW, Pega, Appian, Camunda, and Microsoft Power Platform.

## Delivery, Quality, and Governance

- **Source control and collaboration** — GitLab, GitHub Enterprise, Bitbucket Data Center, Gerrit, Azure DevOps Server, and Perforce Helix Core.
- **CI/CD** — Jenkins, GitLab CI/CD, GitHub Actions Enterprise, Azure Pipelines, TeamCity, Bamboo, Tekton, Spinnaker, Argo Workflows, and Harness.
- **Quality** — SonarQube, Checkmarx, Fortify, Coverity, Veracode, OWASP ZAP, Trivy, Snyk, JFrog Xray, Pact, Selenium Grid, and Cypress.
- **Project and service management** — Jira Service Management, ServiceNow, Azure Boards, Rally, Planview, IBM Engineering Workflow Management, and BMC Helix.
- **Governance** — change advisory boards, architecture review boards, model risk management, software asset management, CMDBs, audit evidence, segregation of duties, and release governance.

## Enterprise Standards

- **Web and network** — HTTP, TLS, DNS, TCP/IP, IPv6, SMTP, IMAP, FTP/SFTP, SSH, VPN, IPsec, and BGP.
- **Data formats** — JSON, XML, YAML, CSV, Avro, Protocol Buffers, Parquet, EDI/X12, EDIFACT, HL7/FHIR, FIX, SWIFT MT/MX, ISO 20022, and XBRL.
- **Financial and supply chain** — ISO 20022, SWIFT, FIX, EDI, GS1, PEPPOL, and Open Banking APIs.
- **Healthcare** — HL7 v2, FHIR, DICOM, IHE, and SNOMED CT.
- **Security and identity** — OAuth, OIDC, SAML, SCIM, LDAP, Kerberos, X.509, FIDO2, and WebAuthn.

## Deep Enterprise Infrastructure

### Transactions and distributed coordination

- **Transaction monitors** — IBM CICS, IBM IMS TM, Oracle Tuxedo, BEA Tuxedo, Encina, and Microsoft Distributed Transaction Coordinator (MSDTC).
- **Transaction standards** — X/Open XA, JTA/JTS, OTS, WS-AtomicTransaction, WS-BusinessActivity, Sagas, two-phase commit, three-phase commit, and transactional messaging.
- **Coordination and consensus** — Apache ZooKeeper, etcd, Consul, Raft, Paxos, leases, fencing tokens, leader election, and quorum design.
- **Distributed systems disciplines** — idempotency, deduplication, monotonic reads, causal consistency, clock synchronization, split-brain prevention, backpressure, bulkheads, circuit breakers, and graceful degradation.

### Enterprise caching and performance

- Redis/Valkey, Hazelcast, Apache Ignite, Infinispan, Ehcache, Oracle Coherence, Terracotta, Memcached, and Varnish.
- Performance tooling — JFR, JMC, async-profiler, VisualVM, YourKit, .NET Diagnostic Tools, PerfView, eBPF, BPFtrace, perf, DTrace, and flame graphs.
- Capacity practices — workload modeling, load testing, soak testing, stress testing, performance budgets, autoscaling policy, and queueing theory.

### Search, content, and records

- **Search** — Apache Solr, OpenSearch, Elasticsearch, Oracle Text, PostgreSQL full-text search, and MarkLogic.
- **ECM and records** — OpenText Documentum, OpenText Content Server, IBM FileNet, Hyland OnBase, Alfresco, Nuxeo, SharePoint, and M-Files.
- **Records management** — retention schedules, disposition holds, WORM storage, legal discovery, classification, redaction, e-signatures, and chain of custody.

### Enterprise file transfer and batch

- IBM Sterling, Axway, GoAnywhere MFT, MOVEit, Cleo, Globalscape, SFTP, FTPS, AS2, AS4, OFTP2, and managed file transfer gateways.
- Batch and scheduling — Control-M, IBM Workload Scheduler, Redwood RunMyJobs, Tidal, Autosys, Rundeck, Apache Oozie, Quartz, Spring Batch, and enterprise cron estates.
- Batch design — restartability, checkpointing, reconciliation, late-arriving data, cut-off windows, calendars, dependencies, and operational handover.

## Mainframe and Transaction Processing

- **IBM Z** — z/OS, JES2/JES3, USS, RACF, SMP/E, ISPF, TSO, JCL, SDSF, z/OS Connect, WebSphere on z/OS, and z/OSMF.
- **COBOL ecosystems** — Enterprise COBOL, IBM Language Environment, Micro Focus Enterprise Server, GnuCOBOL, copybooks, VSAM, DB2, CICS, IMS, and batch JCL.
- **Data stores** — VSAM KSDS/ESDS/RRDS, IMS DB, DB2 for z/OS, ADABAS, CA Datacom, IDMS, and sequential datasets.
- **Integration** — IBM MQ, CICS IPIC, CICS web services, IMS Connect, z/OS Connect, Connect:Direct, NDM, FTP, and mainframe API gateways.
- **Operations** — IBM NetView, OMEGAMON, MainView, CA SYSVIEW, RMF, SMF, WLM, GDPS, Parallel Sysplex, RACF auditing, and HSM.
- **Other legacy estates** — Unisys ClearPath, Burroughs MCP, Fujitsu Mainframe, Bull/Atos, Tandem NonStop, OpenVMS, VMS clusters, and HP-UX.
- **Modernization** — rehosting, refactoring, API wrapping, data replication, COBOL-to-Java/.NET migration, dual-run validation, strangler migration, and mainframe DevOps.

## Enterprise Networking and Storage

### Networking

- **Data center networking** — Cisco IOS/NX-OS, Juniper Junos, Arista EOS, Brocade, Extreme Networks, VLAN/VXLAN, EVPN, MPLS, SD-WAN, and SDN controllers.
- **Network services** — Infoblox, BlueCat, BIND, CoreDNS, F5 BIG-IP, HAProxy, Citrix ADC, A10, Netscaler, Palo Alto, Fortinet, Check Point, and Cisco ASA.
- **Private connectivity** — AWS Direct Connect, Azure ExpressRoute, Google Cloud Interconnect, MPLS, IPsec, GRE, BGP, NAT, DNSSEC, Anycast, and dedicated cross-connects.
- **Network management** — SNMP, NetFlow/IPFIX, sFlow, syslog, RADIUS, TACACS+, NETCONF, RESTCONF, YANG, Ansible Network, and Cisco NSO.
- **Telecom and real-time** — SIP, RTP, IMS, Diameter, SS7, SMPP, WebRTC, and carrier-grade Linux.

### Storage and resilience

- **SAN/NAS** — Fibre Channel, FCoE, iSCSI, NFS, SMB, NVMe-oF, Dell PowerStore, HPE Alletra, Pure Storage, NetApp ONTAP, IBM Spectrum Storage, and Hitachi Vantara.
- **Data protection** — Veeam, Commvault, IBM Spectrum Protect, Rubrik, Cohesity, Veritas NetBackup, snapshots, replication, deduplication, and immutable backups.
- **Resilience** — RAID, erasure coding, synchronous/asynchronous replication, metro clusters, stretch clusters, active-active data centers, air-gapped recovery, and recovery vaults.
- **Disaster recovery** — VMware Site Recovery Manager, Zerto, Azure Site Recovery, AWS Elastic Disaster Recovery, Oracle Data Guard, Db2 HADR, SQL Server Always On, and SAP HANA System Replication.

## Specialized Enterprise Software

### Financial, trading, and payment systems

- **Banking cores** — Temenos Transact, Finastra Fusion, FIS, Fiserv, Mambu, Thought Machine, and Oracle FLEXCUBE.
- **Payments** — payment switches, ISO 8583, ISO 20022, SWIFT, SEPA, ACH, Fedwire, CHIPS, TARGET2, PCI PIN, HSMs, tokenization, 3-D Secure, and EMV.
- **Trading** — FIX engines, QuantLib, Bloomberg APIs, Refinitiv/LSEG, Murex, Calypso, OpenGamma, exchange gateways, co-location, and low-latency risk controls.
- **Risk and compliance** — Murex, FIS Adaptiv, SAS Risk, Moody's Analytics, counterparty risk, liquidity risk, AML, KYC, sanctions screening, and regulatory reporting.

### Insurance, healthcare, and government

- **Insurance** — Guidewire PolicyCenter/ClaimCenter/BillingCenter, Duck Creek, Sapiens, Majesco, ACORD, actuarial systems, reinsurance, and catastrophe modeling.
- **Healthcare** — HL7 interfaces, FHIR servers, DICOM/PACS, Epic, Oracle Health, MEDITECH, InterSystems IRIS/Caché, Mirth Connect, IHE profiles, and clinical terminology services.
- **Government** — FedRAMP, StateRAMP, IL standards, FISMA, PIV/CAC, NARA records, tax systems, benefits systems, case management, procurement, and public-sector identity.

### Manufacturing, logistics, and physical operations

- **Manufacturing execution** — Siemens Opcenter, Rockwell FactoryTalk, AVEVA MES, GE Proficy, SAP ME/MII, ISA-95, OPC UA, and historian systems.
- **Industrial control** — PLCs, SCADA, DCS, HMI, Modbus, PROFINET, EtherNet/IP, IEC 61131-3, IEC 62443, and operational technology (OT) DMZs.
- **Supply chain** — SAP EWM, Manhattan Associates, Blue Yonder, Oracle SCM, Kinaxis, EDI, GS1, warehouse management, transportation management, and digital twins.
- **IoT and edge** — MQTT, OPC UA, Eclipse Kura, AWS IoT Greengrass, Azure IoT Operations, Azure Digital Twins, industrial gateways, and fleet management.

### Desktop, terminal, and user computing

- **Enterprise desktop** — Microsoft Win32, WPF, WinForms, .NET MAUI, JavaFX, Qt, Electron, Citrix Virtual Apps and Desktops, VMware Horizon, and remote application delivery.
- **Terminal access** — 3270, 5250, TN3270, x3270, Reflection, Attachmate, IBM Personal Communications, and terminal emulation gateways.
- **Endpoint management** — Microsoft Intune, Configuration Manager, Workspace ONE, BigFix, Ivanti, Jamf Pro, Group Policy, Active Directory, and software distribution.

### Low-code, portals, and collaboration

- **Low-code platforms** — Mendix, OutSystems, Appian, Pega, ServiceNow App Engine, Salesforce Platform, Power Apps, Oracle APEX, and GeneXus.
- **Portals and collaboration** — SharePoint, Liferay, HCL Digital Experience, IBM Connections, OpenText, Atlassian Data Center, Mattermost Enterprise, and Microsoft 365.
- **Rules and decisioning** — Drools, Red Hat Decision Manager, IBM ODM, FICO Blaze Advisor, Pega Decisioning, DMN, and business rule repositories.

### Enterprise search, integration, and application lifecycle

- **PLM and engineering** — Siemens Teamcenter, Dassault Systèmes 3DEXPERIENCE, PTC Windchill, Aras Innovator, IBM Engineering, and Polarion.
- **ALM and requirements** — Jama Connect, IBM DOORS/DOORS Next, Codebeamer, Helix ALM, Enterprise Architect, and Rational Rhapsody.
- **IT service management** — ServiceNow, BMC Helix, Ivanti Neurons, HCL BigFix, Cherwell, and ManageEngine ServiceDesk Plus.
- **CMDB and discovery** — ServiceNow CMDB, BMC Discovery, Device42, Lansweeper, i-doit, dependency mapping, service topology, and configuration baselines.

## Books and Reference Material

- *Domain-Driven Design* — Eric Evans.
- *Implementing Domain-Driven Design* — Vaughn Vernon.
- *Enterprise Integration Patterns* — Gregor Hohpe and Bobby Woolf.
- *Building Evolutionary Architectures* — Rebecca Parsons, Neal Ford, and Patrick Kua.
- *Fundamentals of Software Architecture* — Mark Richards and Neal Ford.
- *Release It!* — Michael T. Nygard.
- *Site Reliability Engineering* — Betsy Beyer et al.
- *Designing Data-Intensive Applications* — Martin Kleppmann.
- *Accelerate* — Nicole Forsgren, Jez Humble, and Gene Kim.
- [The Twelve-Factor App](https://12factor.net/).
- [CNCF Landscape](https://landscape.cncf.io/).
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework).
- [OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/).

## Contributing

Contributions are welcome when they add an enterprise-relevant technology, standard, platform, or practice. Prefer projects with clear documentation, sustainable maintenance, production use, and a meaningful enterprise use case. Please keep entries grouped by category and avoid marketing claims.

## License

This catalog is available under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) dedication.
