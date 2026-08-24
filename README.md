# Infrastructure Migration & Enterprise Architecture Case Study

> A real-world infrastructure evolution project covering on-premises systems, legacy applications, Microsoft 365, Azure Active Directory, networking, VPN connectivity, development infrastructure and remote-work enablement.

## Overview

During my professional career, one of the most significant infrastructure challenges I faced was the evolution and migration of an enterprise environment that had accumulated several generations of technology.

The infrastructure had to support both modern services and legacy applications that were still operational, maintained and business-critical.

This case study documents the architecture and the decisions involved in two major migration stages, from a legacy Novell NetWare environment to a modern hybrid infrastructure based on Windows Server, Linux, Microsoft 365 and Azure services.

The architecture also included connectivity between headquarters and branch offices through VPNs, development platforms, DNS services, datacenter resources and legacy application workloads.

---

## Architecture Overview

![Enterprise Infrastructure Architecture](architecture/infrastructure-architecture.png)

The architecture represents the coexistence of:

* On-premises infrastructure
* Microsoft 365 and Azure Active Directory
* Windows Server and Linux workloads
* Legacy applications and databases
* DNS and Internet services
* VPN connectivity between locations
* Datacenter-hosted services
* Source code management platforms
* Internal and public-facing applications
* Backup and database infrastructure

> **Note:** The architecture has been sanitized for publication. Names, domains, IP addresses and other identifying information have been anonymized or replaced.

---

## Migration Journey

### Migration 1 — Novell NetWare to Windows Server

The first major migration involved replacing the existing Novell NetWare 4.11 infrastructure with an on-premises Windows Server environment.

One of the objectives was to remove the remaining dependency on the legacy IPX protocol used by the Novell environment and move the network and server infrastructure toward TCP/IP-based services.

During this stage, it was also necessary to preserve several legacy applications.

Some of these systems were still working reliably, receiving maintenance and supporting business processes. Replacing them immediately would have represented a significant operational and technical risk.

To support these workloads, a Linux server was deployed alongside the Windows infrastructure.

This allowed the organization to modernize the infrastructure while maintaining compatibility with applications that could not yet be replaced.

---

### Migration 2 — Hybrid Infrastructure and Microsoft 365

The second migration represented a much broader infrastructure transformation.

Planning for this stage was carried out together with **Sergio Sosa**, with the objective of executing the migration while maintaining business continuity.

The migration included the deployment and transition of:

* Azure Active Directory
* Microsoft Teams
* Microsoft Office 365
* SharePoint
* OneDrive for Business

The resulting environment combined on-premises infrastructure with cloud-based Microsoft services.

This hybrid approach allowed the organization to maintain existing workloads while progressively adopting cloud services for collaboration, identity and productivity.

---

## Networking & Branch Connectivity

The infrastructure connected the headquarters with branch offices through VPN-based connectivity.

The architecture included:

* Headquarters infrastructure
* Branch-office networks
* Internet edge connectivity
* VPN connections
* DNS services
* Public and private network segments
* Datacenter connectivity

This connectivity was particularly important for maintaining access to centralized systems and applications across geographically distributed locations.

---

## Development Infrastructure

The organization also maintained infrastructure supporting internal software development and application management.

The development workflow included:

* Bitbucket
* GitLab
* Jira

These platforms were used for source-code management, repositories and ticket-based work management.

The infrastructure therefore supported not only production workloads, but also the internal software development lifecycle.

---

## Legacy Systems

One of the main architectural challenges was the coexistence of modern infrastructure with legacy applications.

The environment included workloads based on technologies such as:

* Windows Server
* Linux
* Microsoft SQL Server
* MySQL
* xBase
* Clipper
* Visual-based legacy applications
* Older Windows environments
* Internal and public-facing web applications

The strategy was not to replace every legacy component immediately.

Instead, the infrastructure was evolved incrementally, allowing critical applications to continue operating while newer platforms and services were introduced around them.

This approach reduced migration risk and allowed the business to continue operating while the underlying technology evolved.

---

## Remote Work Enablement

One of the most important outcomes of this infrastructure was its ability to support remote operations during the COVID-19 quarantine.

The combination of:

* Microsoft 365
* Teams
* OneDrive
* SharePoint
* VPN connectivity
* Existing on-premises systems
* Internet-based services

allowed the organization to transition personnel to remote work while maintaining business operations.

The infrastructure that had been designed and evolved before the quarantine became a critical enabler for business continuity during an unexpected disruption.

---

## Key Architecture Principles

Several principles guided the evolution of the environment:

### Incremental modernization

Modernize the infrastructure without unnecessarily disrupting systems that were still providing business value.

### Business continuity

Infrastructure changes had to be performed while keeping critical services operational.

### Hybrid architecture

Combine on-premises systems with cloud services where each approach provided the most appropriate capabilities.

### Legacy coexistence

Maintain and isolate legacy workloads while creating a path toward future modernization.

### Centralized connectivity

Provide reliable connectivity between headquarters, branch offices, datacenter resources and external services.

### Operational pragmatism

Technical decisions were driven not only by technology, but also by business requirements, risk, cost and the practical difficulty of replacing long-running systems.

---

## Technologies & Platforms

| Area                       | Technologies                             |
| -------------------------- | ---------------------------------------- |
| Identity                   | Active Directory, Azure Active Directory |
| Collaboration              | Microsoft Teams, Office 365              |
| File & Document Management | SharePoint, OneDrive for Business        |
| Servers                    | Windows Server, Linux                    |
| Databases                  | Microsoft SQL Server, MySQL              |
| Networking                 | TCP/IP, VPN, DNS                         |
| Development                | Bitbucket, GitLab                        |
| Work Management            | Jira                                     |
| Virtualization             | VMware                                   |
| Legacy                     | Novell NetWare, IPX, xBase, Clipper      |
| Hardware                   | Enterprise server infrastructure         |
| Datacenter                 | Tier III datacenter services             |

---

## My Role

This project represents part of my professional experience designing, deploying, migrating and maintaining enterprise infrastructure.

My responsibilities included infrastructure planning, implementation, migration, system administration, networking and the integration of legacy and modern platforms.

The second migration was planned together with **Sergio Sosa**, combining infrastructure knowledge and operational planning to achieve the migration objectives while maintaining business continuity.

---

## Lessons Learned

Large infrastructure migrations are rarely about replacing one technology with another.

They are primarily about managing dependencies, business risk and change.

In environments with long-lived applications, modernization requires understanding what can be replaced, what must be preserved and how both worlds can coexist during the transition.

The most successful infrastructure is not necessarily the newest one. It is the one that allows the business to continue operating while creating a path toward a better architecture.

---

## Disclaimer

This repository is a technical case study based on a historical enterprise infrastructure.

All company names, domains, IP addresses, hostnames and other potentially identifying information have been anonymized or modified.

No confidential credentials, proprietary source code or sensitive company information is included.
