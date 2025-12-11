# Technical Experience Reference
**Last Updated:** December 11, 2025

**Purpose:** Authoritative reference for technical tools, platforms, and technologies. Use this to ensure accuracy when creating technical sections of resumes and cover letters.

**Rule:** Only list technologies in application materials if they appear in "Production Experience" unless specifically noted otherwise.

---

## PRODUCTION EXPERIENCE
*Technologies used in actual production systems - safe to list on resumes*

### Cloud Platforms

#### AWS (10+ years, expert-level)
- **Compute:** EC2, Lambda, Elastic Beanstalk
- **Networking:** VPC, CloudFront, Route 53
- **Storage:** S3, Glacier, EFS
- **Database:** RDS (PostgreSQL, MySQL)
- **Container Services:** EKS (5+ years - Novaprime, Gro), ECS (familiarity only)
- **Monitoring:** CloudWatch, CloudTrail
- **Infrastructure:** CloudFormation, IAM
- **Messaging:** SQS, SNS, SES, EventBridge
- **Context:** Deep expertise across all major services, cost optimization, security best practices

#### Google Cloud Platform (3+ years)
- **Container Orchestration:** GKE (Roivant Sciences)
- **Messaging:** Pub/Sub (Roivant Sciences)
- **Data:** BigQuery (Roivant Sciences)
- **Context:** Production experience primarily at Roivant supporting pharmaceutical R&D platform

#### Azure
- ⚠️ **NO PRODUCTION EXPERIENCE** - Light exposure only, not listable on resume

### Container Orchestration & Virtualization

#### Kubernetes (5+ years production)
- **EKS:** Novaprime (2024), Gro Intelligence (2023-2024)
- **GKE:** Roivant Sciences (2019-2022)
- **⚠️ CRITICAL:** NEVER list AKS - no production experience, only EKS and GKE
- **Associated Tools:**
  - Helm (Roivant - production with GKE)
  - ArgoCD (Roivant - production GitOps with GKE)
  - FluxCD (Novaprime - production GitOps with EKS)
- **Context:** Architected and operated production clusters, automated scaling, health monitoring, deployment automation

#### Docker (8+ years)
- **Experience:** Containerization, multi-stage builds, registry management, security scanning
- **Context:** Getty Images (Jenkins + Docker CI/CD), Roivant, Novaprime, Gro

#### Service Mesh / Legacy Orchestration
- **Consul:** Getty Images - service discovery with Mesos/Marathon
- **Mesos/Marathon:** Getty Images - production service mesh serving millions of users
- **Context:** Pre-Kubernetes era distributed systems

### Infrastructure as Code

#### Terraform (5+ years, advanced)
- **Roivant:** Comprehensive CI/CD pipelines, reduced provisioning from days to hours
- **Novaprime:** EKS infrastructure, VPC design, RDS, S3
- **Gro:** Production-ready modules for EKS with FluxCD
- **Context:** Expert-level, primary IaC tool across multiple companies

#### CloudFormation
- **Experience:** Familiar with AWS native IaC
- **Context:** Not primary tool, Terraform preferred, but can work with existing CloudFormation

#### Ansible
- ⚠️ **EXPOSURE ONLY:** Light exposure at Gro Intelligence
- **Cannot speak to concepts deeply** - not listable as production experience
- **Use case:** Configuration management familiarity, transferable concepts only

### CI/CD & Automation Tools

#### GitHub Actions
- **Novaprime:** Comprehensive CI/CD pipelines, automated deployment workflows
- **Context:** Production use for infrastructure and application deployments

#### GitLab CI
- **Roivant:** Terraform CI/CD pipelines, automated testing workflows
- **Context:** Primary CI/CD tool at Roivant for infrastructure-as-code

#### Jenkins
- **Getty Images:** CI/CD pipelines, Docker container build automation
- **Context:** Traditional CI/CD, reduced release cycle time for high-traffic production

#### ArgoCD
- **Roivant:** GitOps with GKE, continuous deployment for containerized applications
- **Context:** Production GitOps implementation

#### FluxCD
- **Novaprime:** GitOps with EKS, automated deployments
- **Gro:** Delivered production-ready modules (handoff incomplete, prototyped)
- **Context:** Production at Novaprime, prototyped but unimplemented at Gro

### Monitoring, Logging & Observability

#### CloudWatch
- **Experience:** 10+ years, AWS native monitoring and logging
- **Context:** Metrics, logs, alarms, dashboards across all AWS roles

#### New Relic
- **Novaprime:** Centralized observability platform, custom metrics, dashboards, alerting
- **Context:** APM and infrastructure monitoring for production systems

#### Splunk
- **Getty Images:** Enterprise Splunk, machine configuration, agent deployment
- **Context:** Centralized logging platform for distributed services, log analysis

#### PagerDuty
- **Novaprime:** Production alerting and incident response
- **Context:** On-call rotation, alert routing, incident management

#### Grafana
- ⚠️ **NO PRODUCTION EXPERIENCE**
- **Understanding:** Transferable concepts, know it pairs with Prometheus for visualization
- **Do NOT list on resume** - can mention "familiar with Prometheus/Grafana ecosystem" in cover letter if needed

#### ELK Stack (Elasticsearch, Logstash, Kibana)
- ⚠️ **PROTOTYPED, UNIMPLEMENTED**
- **Gro Intelligence:** Prototyped but never deployed to production
- **Do NOT list on resume** - understand concepts and architecture

### Messaging & Event Systems

#### RabbitMQ
- **Getty Images:** Production message queue
- **Context:** Distributed message broker for microservices

#### Kafka / MSK
- **Roivant Sciences:** Production event streaming, MSK (AWS Managed Kafka)
- **⚠️ NOTE:** MSK and Kafka are the same thing - MSK is AWS managed Kafka
- **Context:** Event-driven architectures, understand differences from Pub/Sub and RabbitMQ

#### Google Cloud Pub/Sub
- **Roivant Sciences:** Production messaging, data pipelines
- **Context:** Cloud-native pub/sub for event-driven systems

#### AWS Messaging (SQS, SNS, SES)
- **SQS:** Queue service for decoupled systems
- **SNS:** Notification service for pub/sub patterns
- **SES:** Email service
- **Context:** Production use across AWS environments

#### Redis
- **Novaprime:** Production, Kubernetes-hosted, backend for BullMQ job queue
- **Context:** Caching and job queue backend

#### BullMQ
- **Novaprime:** Job queue system backed by Redis
- **Context:** Async job processing for production systems

### Databases & Data Stores

#### PostgreSQL
- **RDS:** Novaprime, Roivant - production database administration
- **Context:** Configuration, optimization, backup/restore strategies, high availability, replication

#### MySQL
- **RDS:** Familiarity with MySQL on AWS
- **Context:** Can work with MySQL, not primary database, PostgreSQL preferred

#### MongoDB
- ⚠️ **EXPOSURE ONLY:** Getty Images (long ago)
- **Understanding:** Familiar with NoSQL/document stores, indexing differs from RDBMS
- **Context:** Not current expertise, can discuss concepts but not production-current

#### Redis
- See "Messaging & Event Systems" - used as both cache and queue backend

### Programming & Scripting

#### Python (Advanced)
- **Gro Intelligence:** Redesigned entire CI/CD pipeline from bash to Python OOP architecture
- **Novaprime:** Automation tooling for infrastructure provisioning
- **Context:** Advanced proficiency, infrastructure automation, DevOps tooling

#### Go
- **Novaprime:** Automation tooling development
- **Metropolitan Museum:** Web services and backend APIs
- **Gro Intelligence:** Support for Rust stack (not deep Rust expertise)
- **Context:** Comfortable building automation tools and web services

#### Bash (Advanced)
- **All roles:** Scripting, automation, infrastructure management
- **Context:** Expert-level shell scripting for Linux administration

#### JavaScript / Node.js
- ⚠️ **NOT A FOCUS AREA**
- **Context:** Not a JavaScript developer
- **Do NOT apply to roles requiring 8+ years Node.js/JavaScript** - this is a deal-breaker gap

### Security & Compliance

#### SOC2
- **Roivant Sciences:** Pharmaceutical regulatory environment, collaborated with Security/Compliance teams
- **Context:** Infrastructure architecture meeting SOC2 requirements

#### SOX (Sarbanes-Oxley)
- **Experience:** Meeting SOX requirements for financial systems
- **Context:** Regulatory compliance for financial controls

#### HIPAA
- **Experience:** Meeting HIPAA requirements for healthcare systems
- **Context:** Healthcare data privacy and security regulations

#### NIST
- ⚠️ **NO SPECIFIC EXPERIENCE**
- **Do NOT list on resume** - have SOC2/SOX/HIPAA instead

#### ITIL
- ⚠️ **NO SPECIFIC EXPERIENCE**
- **Do NOT list on resume** - have SOC2/SOX/HIPAA instead

#### Security Tools & Practices
- **HashiCorp Vault:** Roivant - secrets management for production systems
- **Zero Trust Architecture:** Roivant - implemented Zero Trust principles
- **IAM Best Practices:** AWS IAM policies, least privilege, role-based access
- **Audit Logging:** CloudTrail, comprehensive audit trails for compliance

### Identity & Access Management

#### Okta Integration
- **Roivant Sciences:** Cross-domain authentication, JWT/SAML tokenization
- **Context:** Identity and access management, SSO integration

### Blockchain & Emerging Tech

#### Digital Asset Canton
- **Gro Intelligence:** Blockchain deployment support
- **Context:** Not deep blockchain expertise, supported deployment and operations

---

## PROTOTYPED / UNIMPLEMENTED
*Technologies prototyped but never deployed to production - be careful listing these*

### ELK Stack (Elasticsearch, Logstash, Kibana)
- **Gro Intelligence:** Prototyped logging stack, not implemented
- **Context:** Understand architecture and use cases, but no production operations

### FluxCD with EKS (at Gro)
- **Gro Intelligence:** Delivered production-ready Terraform modules, incomplete handoff
- **Context:** Modules were ready but project didn't reach production deployment

---

## EXPOSURE / FAMILIARITY ONLY
*Technologies with limited experience - only mention if explicitly asked or as "transferable skills"*

### Ansible
- **Gro Intelligence:** Light exposure for configuration management
- **⚠️ CANNOT speak to concepts deeply**
- **Context:** Basic familiarity, not production depth

### MongoDB
- **Getty Images:** Exposure long ago
- **Context:** Understand NoSQL/document store concepts, indexing differences from RDBMS, not current expertise

### CloudFormation
- **AWS:** Familiar with AWS native IaC
- **Context:** Terraform is primary tool, can work with existing CloudFormation

### ECS
- **AWS:** Familiarity with container service
- **Context:** Not deep production experience, Kubernetes/EKS is primary container platform

### Grafana
- **Understanding:** Know it pairs with Prometheus for visualization
- **Context:** Transferable concepts from other monitoring tools, no hands-on production experience

---

## IMPORTANT TECHNICAL NUANCES

### Resume Accuracy Principles
1. **Only list production technologies actually used** - Example: EKS and GKE (production), NEVER AKS (not used)
2. **Avoid "-ready" language** - Save transferable skills discussion for cover letters
3. **Frame exposure honestly** - "Familiarity with X" not "expertise in X"

### Kubernetes Experience Specifics
- **Production:** EKS (Novaprime, Gro) and GKE (Roivant) ONLY
- **⚠️ NEVER list AKS** - no production Azure Kubernetes experience
- **5+ years total Kubernetes production experience** across EKS and GKE

### MSK = Kafka
- **MSK is AWS Managed Kafka** - same technology, different name
- **Roivant experience:** Both can be referenced as Kafka or MSK
- **Understanding:** Differences between Kafka, Pub/Sub, RabbitMQ in event streaming

### Contractor Work Inheritance
- **Novaprime:** First FULL-TIME infrastructure hire
- **Not "first hire"** - inherited existing contractor AWS infrastructure
- **Achievement:** Professionalized and transformed contractor work into production-grade systems
- **Principle:** Never say "built from the ground up" unless true

### Compliance Framework Experience
- **HAVE:** SOC2, SOX, HIPAA
- **DO NOT HAVE:** NIST-specific, ITIL-specific compliance experience
- **Context:** Regulatory compliance from pharmaceutical and healthcare environments

### Monitoring & Logging Stack
- **Production:** CloudWatch, New Relic, Splunk, PagerDuty
- **Prototyped:** ELK Stack (Gro - unimplemented)
- **NO Production:** Grafana (understand concepts, transferable from other tools)
- **Context:** Understand logging standards for containerization, injecting monitoring tools with sources

### Event Streaming Platforms
- **Understand differences:** Kafka vs. Pub/Sub vs. RabbitMQ
- **Kafka/MSK:** Event streaming, high-throughput, replayable logs
- **Pub/Sub:** Google Cloud native, fully managed, push/pull
- **RabbitMQ:** Traditional message queue, AMQP protocol

### Logging Standards for Containerization
- **Understanding:** How to inject logging tools into containerized environments
- **Experience:** Structured logging, stdout/stderr patterns, sidecar patterns
- **Context:** Splunk agent configuration, logging standards for Kubernetes

### Network Security Architecture
- **IPsec Tunnel Design:** Novaprime - proposed design (not implemented)
- **Context:** Network security architecture proposal, demonstrated expertise but not production-deployed

---

## TECHNICAL DEAL-BREAKER GAPS
*Technologies/requirements that are automatic PASS decisions*

- **JavaScript/Node.js roles requiring 8+ years** - Not primary focus area
- **QA Automation focus** - Selenium, Cypress, Playwright, Jest, PyTest (50%+ QA work)
- **Azure-heavy roles** - Light exposure only, AWS is primary cloud
- **Grafana as required production tool** - No production experience (transferable concepts only)
- **AKS (Azure Kubernetes Service)** - No production experience, only EKS and GKE
- **NIST/ITIL as required compliance** - Have SOC2/SOX/HIPAA instead
- **Mandarin fluency** - Not a language skill available

---

## REVISION HISTORY

**December 11, 2025:** Initial technical experience reference document created
- Split from master reference document for GitHub publishing
- Removed personal preferences, mission alignment, and employment details
- Focused purely on technical tools, platforms, and production context
