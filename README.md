<h1 align="center">👋 Hi, I'm Marko Khomytsia</h1>
<h3 align="center">Principal Software Engineer / Architect</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-25%2B%20years-blue" />
  <img src="https://img.shields.io/badge/Role-Principal%20Engineer%20%2F%20Architect-success" />
  <img src="https://img.shields.io/badge/Status-Under%20NDA-important" />
</p>

---

### 🚀 About Me

- 🏆 25+ years of experience in software engineering, architecture, and technical leadership.
- 💡 Passionate about designing scalable, secure, and innovative solutions for high-traffic platforms.
- 🌍 Based in EU.

---

### 🛠️ Core Competencies

- **DevOps & Cloud:** Kubernetes, Terraform, Flux, Jenkins, Gitea, CI/CD Pipelines, Harbor, Docker, Helm, Ansible, Prometheus, Grafana, ELK stack
- **Architecture:** Microservices, Distributed Systems, High Availability, Scalability, Security Best Practices
- **Programming:** PHP, JavaScript, Python, Bash, Go, SQL, REST, SOAP, etc
- **AI Integrations:** MCP, A2A, Chatbots, ML APIs, Automation, Data Pipelines
- **Other Tools:** Atlassian Suite, Git, SVN, Gitea, Monitoring & Reporting, Payment Systems, API Integrations

---

### 💼 Experience

- **Principal Software Engineer / Architect**  
  _Under NDA | Apr 2010 – Present_  
  
  Leading architecture and DevOps transformation initiatives for enterprise-scale platforms with focus on cloud-native infrastructure and AI-driven automation.
  
  **Technical Leadership:**
  - Architected and implemented GitLessOps platform on Kubernetes, introducing OCI-based artifact promotion workflow that eliminated Git commits from deployment pipeline
  - Designed and deployed multi-environment (dev/staging/production) infrastructure using Terraform, GKE, and FluxCD with automatic image reconciliation
  - Established zero-trust security model using Workload Identity, SOPS encryption with Cloud KMS, and eliminated static credentials across all environments
  
  **Cloud Infrastructure & Platform Engineering:**
  - Built production-ready GKE clusters with Gateway API, Workload Identity Federation, and private node pools with Cloud NAT
  - Implemented comprehensive GitOps workflows with FluxCD image automation, OCIRepository controllers, and multi-repository synchronization
  - Deployed full observability stack: Prometheus for metrics, Grafana for visualization, Jaeger for distributed tracing, and Loki for log aggregation
  
  **AI & Automation:**
  - Integrated AI agents using KAgent framework with Model Context Protocol (MCP) for tool integration and Agent-to-Agent (A2A) communication
  - Developed Release Agent with voice-command capabilities for infrastructure operations through MCP servers (Flux, Kubernetes, GCP)
  - Implemented KGateway as AI-native API Gateway with support for LLM traffic, WebSocket connections, and A2A protocol routing
  
  **DevOps & CI/CD:**
  - Designed multi-stage Docker builds for Go and React applications with BuildKit optimizations and layer caching
  - Established GitHub Actions workflows with Workload Identity Federation (OIDC) for secure GCP authentication without service account keys
  - Automated secrets management pipeline: GCP Secret Manager → SOPS encryption → Git → Flux decryption → Kubernetes Secrets
  
  **Technical Stack:**
  - Infrastructure: GCP (GKE, Artifact Registry, Secret Manager, Cloud KMS), Terraform, FluxCD, Kustomize, Helm
  - Kubernetes: Gateway API, Workload Identity, RBAC, NetworkPolicies, HPA, PodDisruptionBudgets
  - Monitoring: Prometheus, Grafana, Jaeger (OpenTelemetry), Loki, Fluent Bit
  - Development: Go 1.25, React 19, Vite, nginx, gorilla/mux, OpenTelemetry SDK
  - AI/Agents: KAgent (v0.7.7), KGateway (v2.1.2), MCP Protocol, A2A Protocol
  - Security: Workload Identity, SOPS, Cloud KMS, non-root containers, private GKE nodes

- **PHP Developer (eBay, Marktplaats.nl)**  
  _Lohika | Jan 2009 – May 2010_  
  - Developed and maintained Marktplaats.nl, the leading online classifieds site in the Netherlands.
  - Platform: 9M+ unique visitors/month, 80M visits/month, 1600M pageviews/month, 800+ web servers.
  - [More details](http://www.ebayclassifiedsgroup.com/marktplaats-nl/about)

- **Developer / Team Lead**  
  _Lvivmedia | Oct 2000 – Dec 2008_

---

### 🎓 Education

- **Ivan Franko National University of Lviv**  
  _Master’s Diploma in Informatics and Mathematics, Applied Mathematics and Informatics (1998 – 2003)_

---

### � Hackathon Achievement

**GitLessOps Release Agent** — AI-Driven Infrastructure Automation Platform  
_Completed: January 2026_

Successfully completed a 2-week intensive hackathon focused on building modern Agentic AI infrastructure on Kubernetes. The project demonstrates cutting-edge approaches to cloud-native automation and AI-native architecture.

**Project Overview:**
- Developed Release Agent that automates application deployments through OCI image tagging, enabling GitLessOps workflow where releases are promoted via tags instead of Git commits
- Implemented voice-controlled infrastructure operations through Agent-to-Agent (A2A) protocol integration
- Built complete end-to-end automation: voice command → agent processing → OCI tagging → Flux reconciliation → deployment verification

**Technical Implementation:**

*AI Agents & Integration:*
- KAgent framework (v0.7.7) with declarative agent definitions and MCP client support
- Release Agent with skills: version validation, OCI tagging, deployment verification, status reporting
- A2A Protocol integration enabling voice-controlled infrastructure operations
- MCP (Model Context Protocol) for standardized tool integration (Flux, Kubernetes, GCP APIs)

*GitLessOps Architecture:*
- Flux Image Automation with OCIRepository controllers tracking dev/stable/prod tags
- OCI artifacts for Kubernetes manifests stored in Google Artifact Registry
- ImagePolicy and ImageUpdateAutomation for zero-Git deployment workflow
- Tag-based promotion: `gcloud artifacts docker tags add :v1.2.3 :prod` triggers automatic deployment

*Infrastructure & Platform:*
- Agent Gateway (KGateway v2.1.2) for security, observability, and A2A routing with experimental WebSocket support
- Full observability stack with Prometheus, Grafana, Jaeger, and Loki integrated through Gateway API
- Multi-environment deployment (dev, staging, production) with Kustomize overlays
- Workload Identity for secure authentication between Kubernetes and GCP services

*DevOps & Automation:*
- GitHub Actions with Workload Identity Federation for OIDC-based authentication
- Automated Docker builds and OCI manifest packaging with version pinning
- SOPS encryption with Cloud KMS for secrets management in Git
- Terraform infrastructure-as-code for complete GKE cluster and services

**Deliverables:**
- GitHub repository with complete source code: [SuperKuberTeam](https://github.com/mkhomytsya/SuperKuberTeam)
- Architecture Decision Records (ADR) documenting key design decisions
- High-Level Design (HLD) with system architecture diagrams
- Comprehensive documentation and deployment guides
- Working demo application (React + Go) deployed across three environments

**Technical Stack:**
- **Cloud & Orchestration:** GCP, GKE, Terraform, FluxCD, Kustomize, Helm
- **AI & Agents:** KAgent, KGateway, MCP Protocol, A2A Protocol, OpenAI
- **Application:** Go 1.25 (gorilla/mux, OpenTelemetry), React 19 (Vite)
- **Observability:** Prometheus, Grafana, Jaeger, Loki, Fluent Bit
- **Security:** Workload Identity, SOPS, Cloud KMS, Gateway API
- **CI/CD:** GitHub Actions, Google Artifact Registry, Docker BuildKit

**Key Achievements:**
- Implemented complete GitLessOps workflow eliminating Git commits from deployment pipeline
- Achieved voice-controlled infrastructure operations through AI agents
- Built production-ready multi-environment platform with full observability
- Demonstrated modern security practices with zero static credentials

---

### 📊 Technology Stack Summary

Based on current projects and hackathon work, my technology expertise spans:

**Cloud & Infrastructure:**
- Google Cloud Platform: GKE, Artifact Registry, Secret Manager, Cloud KMS, Cloud NAT, Workload Identity
- Kubernetes: Gateway API, FluxCD, Kustomize, Helm, CRDs, Operators, RBAC, NetworkPolicies
- Terraform: Multi-module infrastructure, remote state, resource dependencies
- Container Runtime: Docker, BuildKit, multi-stage builds, layer optimization

**DevOps & GitOps:**
- FluxCD: OCIRepository, ImageRepository, ImagePolicy, ImageUpdateAutomation, SOPS decryption
- CI/CD: GitHub Actions, Workload Identity Federation (OIDC), artifact management
- Security: SOPS encryption, Cloud KMS, Workload Identity, non-root containers, secrets rotation

**AI & Agent Frameworks:**
- KAgent: Declarative agents, MCP client, A2A gateway, skill definitions
- KGateway: AI-native gateway, LLM traffic routing, WebSocket support, observability
- MCP (Model Context Protocol): Flux Operator, Kubernetes, GCP integrations
- A2A Protocol: Agent-to-agent communication, voice agent integration

**Application Development:**
- Backend: Go 1.25 (gorilla/mux, Prometheus client, OpenTelemetry SDK)
- Frontend: React 19, Vite, modern JavaScript, responsive design
- Web Servers: nginx, reverse proxy configuration, static asset serving
- APIs: RESTful design, JSON, health checks, versioning

**Observability & Monitoring:**
- Metrics: Prometheus (collectors, exporters, PromQL, recording rules)
- Visualization: Grafana (dashboards, alerts, data sources)
- Tracing: Jaeger, OpenTelemetry (OTLP/HTTP, instrumentation, context propagation)
- Logging: Loki, Fluent Bit (log aggregation, filtering, structured logging)

**Legacy & Enterprise:**
- PHP: Marktplaats.nl (80M visits/month, 800+ servers), Smarty, SOAP, REST
- Databases: MySQL (master-slave replication), SQLite, data migrations
- Build Tools: Ant, Maven, Gradle, make
- Version Control: Git, SVN, Gitea, GitHub Actions, deployment strategies

**Architectural Patterns:**
- Microservices architecture with service mesh readiness
- GitOps and GitLessOps deployment patterns
- Event-driven architecture with message queues
- Multi-environment promotion strategies (dev → staging → production)
- Infrastructure as Code with modular design
- Zero-trust security model

---

### �🌟 Featured Project

**eBay/Marktplaats**  
_Feb 2009 – Jun 2011 (with Lohika)_

Marktplaats.nl is the leading online classifieds site in the Netherlands, acquired by eBay in 2004.  
- 9M+ unique visitors, 8M+ new ads/month, 80M visits/month, 1600M pageviews/month, 800+ web servers.
- **Tech:** Apache, PHP, Smarty, SimpleTest, SOAP, REST, Ant, Memcache, MySQL (master-slave), SVN, Atlassian tools.
- **Role:** Backend development, API integrations, payment systems, ETL.

---

### 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/mkhomytsia/)

---

<!--
**mkhomytsya/mkhomytsya** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
