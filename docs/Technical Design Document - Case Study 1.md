## 1 Overview
This *technical design document* describes in detail all the aspects related to the **Cloud-Based Multi-Service Platform for Smart Event Management** software development case study project.

It begins stating the purpose of the project and what are its target audiences.

Then it provides a summary for this case-study project, describing its scope, constraints, key requirements and primary features.

A high level system architecture is also included, followed by lower level software design specifications for the data, components, interfaces and user interfaces that will be required to build this system.

Towards the end of this document there's a section discussing the assumptions and dependencies that were pondered when putting this project together.

The document ends with a glossary of technical terms which are relevant for facilitating the understanding of everyone involved in this project.
## 2 Purpose
The information here presented is essential for anyone interested in learning more about this case study goals and the benefits it can bring to those who take their time to work on it.
## 3 Target Audience
- Software developers, software engineering students and people in general who want to: 
	- learn and evolve their skills through working on software development tasks that are glued together in the context of a case study of real world proportions and complexity.
	- learn and practice new programming languages in order to match a higher number of job openings technical requirements.
	- integrate multiple technologies, skills, tools and programming languages to build a solution that is more robust, complete and complex than the average examples and exercises you may find elsewhere.
	- learn each one of the technologies selected to build this case-study software development project.
## 4 Project Summary

### 4.1 Scope [^2][^3]

#### 4.1.1 Name
**_Cloud-Based Multi-Service Platform for Smart Event Management_**
#### 4.1.2 Description
The system is a **cloud-native platform** for managing large-scale events (conferences, concerts, workshops) with real-time analytics, ticketing, and personalized recommendations. It will integrate multiple services, each implemented in different languages, and leverage AI tools for development and intelligent features.
#### 4.1.3 Goals
Serve as a didactic, cloud-based, feature rich, multi-service and multi-platform system which presents to its implementers a great and unique opportunity to learn a diverse and multifaced set of technologies, programming languages and concepts that will prepare them for working on real word projects of similar or higher level of complexity.
#### 4.1.4 Deadline
This is a long term case-study project, which at this time does not have a planned deadline of when it should be finished.
#### 4.1.5 Manager
This project was conceived by *Ulysses Alves (https://www.linkedin.com/in/ulysses-alves/)* and is managed by him.
#### 4.1.6 Deliverables
- Free software engineering and programming lectures in the context of this project's content and development. Subscribe to [Zoe Psomí Software Engineering's channel in YouTube](https://www.youtube.com/@zoepsomi) to receive updates on those lectures.
- Artifacts related to this project development (documentation, architecture, planning, source code, test plan, deployment plan, release plan, etc). This items will be made available in the public GitHub repository https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management as soon as they are created.
- Full and functional system, implemented according to its documented requirements, architecture, goals and plan.
#### 4.1.7 Tasks and Activities
- The video lectures related to this project will be [hosted on YouTube](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV) to demo the implemented features, technologies used and the processes followed to implement the proposed case-study system.
- The tasks and activities required to implement this project are organized as issues, deadlines and other planning related items on the [project public GitHub repository](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management). 
	- Interested people may open issues and write comments on existing issues, in order to improve their understanding and learning.
- The actual implementation of the system will take place as time allows. Refer to the Constraints section of this document for more information.
	- You may decide to try and implement your own version of this case-study system specification. This would be the most effective and recommended way for you to take full advantage of all of the learning material that we will be providing in this[ project video lessons](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV).
#### 4.1.8 Exclusions (Not In Scope)
- This is **not a commercial product**, but rather a learning endeavor and didactic opportunity to learn and grow as software developers.
- This project will not accept pull requests.
	- All the implementation will be taken care of by its owner. 
	- If you wish, you may clone its public repository to study the source code and to run it in your own environment.
- There will be no support support team responsible for helping users to operate this system.
	- Following the [video lectures](https://youtube.com/playlist?list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV&si=K84-LltUqaphD0uV) should be enough for learning both how to develop and how to operate the case-study system.
#### 4.1.9 Constraints
##### 4.1.9.1 Budgets
- If you wish to financially contribute to this project, in benefit of the software development community, donations are welcome and are being accepted through PayPal at Zoe Psomí company's donations page.
##### 4.1.9.2 Timelines
- There are no deadlines defined for this project.
- The project will evolve at a pace that depends on how much free time Ulysses will be able to get to work on it.
- Current progress and scheduled/planned tasks can be viewed on the [project's public repository at GitHub](https://github.com/users/UlyssesAlves/projects/4).
##### 4.1.9.3 Resources
- This is a [voluntary project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management) run by [Ulysses Alves](https://www.linkedin.com/in/ulysses-alves/).
- He is basically doing all the technical work involved, including:
	- Documentation
	- Architecture
	- Planning
	- Implementation
	- Test
	- Deploy
	- Release
- [Ulysses](https://www.linkedin.com/in/ulysses-alves/) is also the person working on: 
	- recording and editing the [video lessons/lectures/demos related to this project](https://www.youtube.com/watch?v=C4tE1kZNrX4&list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV).
	- marketing and promoting the project for reaching out as many people as possible, who might be interested in learning more about software development through [this project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management).
		- We would appreciate any marketing contributions to [this project](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management). 
		- Simple acts like sharing the [video lectures, subscribing to our channel, liking the videos and writing comments](https://www.youtube.com/watch?v=C4tE1kZNrX4&list=PLgcaIrgxzJn_IScY-VDAT9pqdS82HKVjV) would be tremendously helpful and highly appreciated.
		- [Starring our repository, watching it, forking it](https://github.com/UlyssesAlves/case-study-1-cloud-based-multi-service-platform-for-smart-event-management) and interacting with us in any way would let us know that [the project](https://github.com/users/UlyssesAlves/projects/4) is reaching its main goals. 
		- So, please let us know how to better serve you and the community as we work to give life to this project and to keep it alive.
#### 4.1.10 Key Requirements
- User Management Service
- Event Management Service
- Ticketing Service
- Recommendation Engine
- Frontend
#### 4.1.11 Primary Features
- Web application for users (React + Node.js)
- Backend microservices (C#, Python, Go)
- AI-powered recommendation engine
- CI/CD pipelines for automated deployment
- Hosted on a major cloud (AWS, Azure, or GCP)

## 5 System Architecture
### 5.1 Architectural Structures and Views
#### 5.1.1 Layer View
<img width="1689" height="937" alt="image" src="https://github.com/user-attachments/assets/55ca1bc6-f13d-4eca-b9d9-4f8e39f41db3" />

### 5.2 Major Components

#### 5.2.1 Internal Components (Modules)

| Module                                                     | Description                                     | Requirements & Purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------------------------------------------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *User Management Service* (C# / .NET)                      | Users management microservice.                  | • Register, authenticate, and manage user profiles.<br>• Role-based access control (organizer, attendee).<br>• Manage user preferences.                                                                                                                                                                                                                                                                                                                                                      |
| *Event Management Service* (Go)                            | Events management microservice.                 | • Create, update, and delete events (conferences, concerts, workshops).<br>• Handle event scheduling. <br>• Handle capacity management (seats availability).                                                                                                                                                                                                                                                                                                                                 |
| *Ticketing Service* (TypeScript / Node.js)                 | Ticketing management microservice.              | • Purchase tickets.<br>• Validate tickets.                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| *Recommendation Engine* (Python)                           | AI powered events recommendation  microservice. | • Suggest events based on user preferences and past behavior.<br>• Use AI/ML models for personalization.<br>• Promote users engagement.<br>                                                                                                                                                                                                                                                                                                                                                  |
| *Frontend Web Application* (React, TypeScript and Node.js) | GUI (Graphical User Interface)                  | **Recommendations**<br>• Viewing recommendations.<br><br>**User Management**<br>• Logon / Logoff<br>• Password recovery / reset.<br>• User preferences and profile.<br>• User registration.<br>• Deleting user account.<br><br>**Events**<br>• Browsing and managing events.<br><br>**Ticketing**<br>• Purchasing tickets. <br>• Browsing purchased tickets.<br>• Validate client tickets.<br><br>**Other Features**<br>• Responsive UI<br>• Service Status Page<br>• Viewing notifications. |

#### 5.2.2 External Components

| Component                            | Description                                                                                                   | Purpose                                                                                                                                                                               |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Oracle Cloud Infrastructure (OCI)*  | Underlying cloud platform.                                                                                    | Provides compute, storage, networking, IAM, free tier resources.                                                                                                                      |
| *Containers on VMs (via Kubernetes)* | Containerized workloads orchestrated by Kubernetes on OCI VMs.                                                | • Run microservices and databases in isolated containers. <br>• Enable scalability, resilience, and CI/CD integration.<br>                                                            |
| *OCI Vault*                          | Managed service for storing and managing secrets securely.                                                    | • Centralizes sensitive data (API keys, passwords).<br>• Enforces access control.<br>• Enables rotation. <br>• Prevents hardcoding secrets in configs                                 |
| OCI Monitoring                       | Observability service.                                                                                        | • Collects metrics from OCI resources (compute, database, networking).<br>• Tracks infrastructure and application metrics (CPU, memory, latency).                                     |
| OCI Alarms                           | Threshold-based alerts on Monitoring metrics.                                                                 | • Detects performance issues.<br>• Triggers alerts when thresholds are breached.                                                                                                      |
| *Docker*                             | Container runtime.                                                                                            | • Packages applications into portable containers.<br>• Modular microservices architecture.                                                                                            |
| *Kubernetes*                         | Container orchestration platform.                                                                             | • Manages container lifecycle, scaling, networking.<br>• Modular microservices architecture.<br>• Automatic failover and load balancing.                                              |
| *Auto-Scaling Compute*               | Elastic scaling of compute resources.                                                                         | Adjusts capacity based on demand.<br>• Automatic failover.<br>• Load balancing.                                                                                                       |
| *Terraform*                          | Infrastructure-as-code tool.                                                                                  | Automates provisioning of cloud resources.                                                                                                                                            |
| *Load-balancer*                      | Distributes traffic across services.                                                                          | • Ensures availability, scales horizontally, improves performance.<br>• Automatic failover and load balancing.<br>• Health checks.                                                    |
| *API Gateway*                        | Managed service for routing APIs.                                                                             | • Exposes microservices securely, rate limiting, monitoring.<br>• Modular microservices architecture.                                                                                 |
| IAM (Identity and Access Management) | Centralized system for managing users, roles, and access policies in Oracle Cloud.                            | • Authenticates users and services.<br>• Authorizes access to cloud resources.<br>• Enforces least‑privilege security.<br>• Provides audit trails and compliance.                     |
| OCI IAM                              | OAuth 2.0 Identity & Access Management                                                                        | Provides user registration, authentication, and role‑based authorization.                                                                                                             |
| *Redis*                              | In-memory cache.                                                                                              | • Speeds up data access.<br>• Session storage. <br>• Caching.                                                                                                                         |
| *RabbitMQ*                           | Message broker.                                                                                               | • Inter-service communication<br>• Handles async communication between services.                                                                                                      |
| *PostgreSQL*                         | Open source relational DB.                                                                                    | • Persistent storage for microservices.<br>• Transaction consistency.<br>• Data Integrity<br>• Complex Queries & Joins<br>• Scalability & indexing.                                   |
| *MongoDB*                            | NoSQL document database.                                                                                      | • Schema Flexibility<br>• Horizontal Scalability<br>• Developer Productivity<br>• Handling Unstructured or Semi‑Structured Data<br>• Decentralized Ownership                          |
| *Hyperswitch*                        | Open source payments switch and orchestrator.                                                                 | Handles secure payments, fraud detection, compliance.                                                                                                                                 |
| *AI/ML Models*                       | Machine learning workloads (open-source libs).                                                                | • Predictions <br>• Classification<br>• Personalization                                                                                                                               |
| *Analytics*                          | Data visualization and monitoring (Grafana/Prometheus or OCI Analytics Cloud).                                | Generates dashboards, insights, metrics.<br>                                                                                                                                          |
| *CDN (Content Delivery Network)*     | Global distribution of static content.                                                                        | • Reduces latency. <br>• Improves performance for static assets.                                                                                                                      |
| *GitHub*                             | Cloud-based platform for hosting, managing, and collaborating on software projects using Git version control. | • Source code hosting and collaboration.<br>• Stores code, manages issues, integrates with CI/CD.                                                                                     |
| *CI/CD Pipelines*                    | Automated build, test, deploy workflows.                                                                      | • Continuous integration.<br>• Continuous delivery.<br>• Automated build.<br>• Automated tests.<br>• Automated linting (static analysis).<br>• Security scans.<br>• Automated deploy. |

#### 5.2.3 Dependencies

| Module or Component                                        | Hard Dependencies                                                                      | Soft Dependencies                                                                   | Consumed By                                                                                                                            |
| ---------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| *User Management Service* (C# / .NET)                      | PostgreSQL, IAM, Kubernetes                                                            | Docker, Auto-Scaling Compute, OCI Vault, OCI Monitoring                             | Frontend Web Application, Ticketing Service, Recommendation Engine                                                                     |
| *Event Management Service* (Go)                            | PostgreSQL, RabbitMQ, Kubernetes                                                       | Redis (cache), API Gateway, Docker, Auto-Scaling Compute, OCI Vault, OCI Monitoring | Ticketing Service, Analytics                                                                                                           |
| *Ticketing Service* (TypeScript / Node.js)                 | Hyperswitch, PostgreSQL, Event Management Service, User Management Service, Kubernetes | Redis, Docker, Auto-Scaling Compute, OCI Vault, OCI Monitoring                      | Frontend Web Application                                                                                                               |
| *Recommendation Engine* (Python)                           | PostgreSQL, MongoDB, AI/ML Models, Kubernetes<br><br>                                  | Docker, Auto-Scaling Compute, OCI Vault, OCI Monitoring                             | Frontend Web Application, Analytics                                                                                                    |
| *Frontend Web Application* (React, TypeScript and Node.js) | User Management Service, Ticketing Service, Recommendation Engine                      | API Gateway, Load-balancer, CDN, Docker, Kubernetes, Auto-Scaling Compute           | End-users (entry point)                                                                                                                |
| *Oracle Cloud Infrastructure (OCI)*                        | *No relevant dependencies*                                                             |                                                                                     | All components                                                                                                                         |
| *Containers on VMs (via Kubernetes)*                       | OCI Compute, Networking, Storage, Container Engine for Kubernetes (OKE)                |                                                                                     | PostgreSQL, MongoDB, RabbitMQ, Redis (as containerized services)<br><br>                                                               |
| *OCI Vault*                                                | OCI                                                                                    |                                                                                     | PostgreSQL, MongoDB, RabbitMQ, Redis, Hyperswitch                                                                                      |
| OCI Monitoring                                             | OCI                                                                                    |                                                                                     | All services                                                                                                                           |
| OCI Alarms                                                 | OCI Monitoring                                                                         |                                                                                     | Ops/DevOps teams                                                                                                                       |
| *Docker*                                                   | OCI Compute                                                                            |                                                                                     | Kubernetes, CI/CD Pipelines, All internal components                                                                                   |
| *Kubernetes*                                               | Docker, Auto-Scaling Compute, Terraform<br>                                            |                                                                                     | All internal services, API Gateway, CI/CD Pipelines                                                                                    |
| *Auto-Scaling Compute*                                     | Kubernetes, Docker, VMs, Terraform                                                     |                                                                                     | All internal services                                                                                                                  |
| *Terraform*                                                | OCI, IAM                                                                               |                                                                                     | Auto-Scaling Compute, Kubernetes, CI/CD Pipelines                                                                                      |
| *Load-balancer*                                            | Auto-Scaling Compute, Kubernetes, VMs                                                  |                                                                                     | API Gateway, Frontend Web Application                                                                                                  |
| *API Gateway*                                              | IAM, Load-balancer, Kubernetes                                                         | Docker (runtime)                                                                    | Frontend Web Application, All microservices                                                                                            |
| IAM (Identity and Access Management)                       | OCI                                                                                    |                                                                                     | API Gateway, Terraform, CI/CD Pipelines                                                                                                |
| OCI IAM                                                    | OCI Infrastructure<br><br><br>                                                         |                                                                                     | User Management Service, API Gateway, Ticketing Service, Recommendation Engine (via user roles), CI/CD Pipelines (for access policies) |
| *Redis*                                                    | VMs, OCI Vault                                                                         | Docker, Kubernetes (runtime)                                                        | Event Management Service, Ticketing Service, Recommendation Engine, Frontend Web Application (cache)                                   |
| *RabbitMQ*                                                 | VMs, OCI Vault                                                                         | Docker, Kubernetes (runtime)                                                        | Event Management Service, Ticketing Service                                                                                            |
| *PostgreSQL*                                               | VMs, OCI Vault, Kubernetes                                                             | Docker, OCI Monitoring                                                              | Recommendation Engine, User Management Service, Event Management Service, Ticketing Service, Analytics                                 |
| *MongoDB*                                                  | VMs, OCI Vault, Kubernetes<br>                                                         | Docker, OCI Monitoring                                                              | Recommendation Engine, Ticketing Service, Analytics                                                                                    |
| *Hyperswitch*                                              | Ticketing Service, User Management Service, External Payment Providers<br><br><br>     |                                                                                     | Ticketing Service                                                                                                                      |
| *AI/ML Models*                                             | OCI Compute<br><br>                                                                    | OCI Vault (for model secrets), OCI Monitoring                                       | Recommendation Engine, Analytics                                                                                                       |
| *Analytics*                                                | PostgreSQL, MongoDB, Event Management Service, Recommendation Engine<br><br>           |                                                                                     | Business stakeholders                                                                                                                  |
| *CDN (Content Delivery Network)*                           | OCI Networking                                                                         |                                                                                     | Frontend Web Application                                                                                                               |
| *GitHub*                                                   | *No relevant dependencies.*                                                            |                                                                                     | CI/CD Pipelines                                                                                                                        |
| *CI/CD Pipelines*                                          | GitHub, Docker, Kubernetes, Terraform                                                  |                                                                                     | All internal services                                                                                                                  |

#### 5.2.4 Tools

| Tool             | Description                  | Purpose                                                    | Depends On                               |
| ---------------- | ---------------------------- | ---------------------------------------------------------- | ---------------------------------------- |
| *GitHub Copilot* | AI-powered coding assistant. | • Suggests code.<br>• Improves developer productivity.<br> | GitHub IDE integration, developer input. |


