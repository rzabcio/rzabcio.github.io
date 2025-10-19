---
layout: cv
title: Jakub Głazik
description: Curriculum Vitae
---

- Download
  [PDF version](https://rzabcio.github.io/CV%20-%20Jakub%20G%C5%82azik.pdf)

- About me:

  > Sysadmin, DevOps, GCP certified engineer, Jira administrator. Linux,
  > (Neo)Vim and automation enthusiast. Java certified programmer, Math master
  > degree. Board game geek, dog person.

- Contact:

  > email: [rzabcio@gmail.com](mailto:rzabcio@gmail.com)  
  > tel: [+48 501649677](tel:48501649677)  
  > LinkedIn: [profile](https://www.linkedin.com/in/jakub-g%C5%82azik-b4545b4b/)

- Motto:
  > _When playing a game, the goal is to win, but it is the goal that is
  > important, not the winning._  
  > -- Reiner Knizia

---

## Skills

| Programming    | Tools            | Servers/Platforms  | Other           |
| -------------- | ---------------- | ------------------ | --------------- |
| ▣▣▣▣ Java      | ▣▣▣▣ Git         | ▣▣▣▢ Kubernetes    | ▣▣▣▣ Jira       |
| ▣▣▣▢ Groovy    | ▣▣▣▢ Bamboo      | ▣▣▣▢ Apache/Httpd  | ▣▣▣▢ Confluence |
| ▣▣▢▢ Bash      | ▣▣▣▢ Bitbucket   | ▣▣▣▢ Tomcat        | ▣▣▣▢ PKI        |
| ▣▣▢▢ Python    | ▣▣▣▢ Ansible     | ▣▣▢▢ Docker        | ▣▣▣▢ Linux      |
| ▣▣▢▢ Go        | ▣▣▣▢ Jenkins     | ▣▣▢▢ NGinx         | ▣▣▢▢ Crowd      |
| ▣▣▢▢ Frontend  | ▣▣▣▢ Wazuh (ELK) | ▣▣▢▢ JBoss/Wildfly | ▣▢▢▢ Windows    |
| ▣▢▢▢ SQL       | ▣▣▢▢ Nexus       | ▣▣▢▢ GCP           |                 |
| ▣▢▢▢ Terraform | ▣▣▢▢ Gitlab      | ▣▢▢▢ AWS/IBMCloud  |                 |
|                | ▣▣▢▢ Grafana     |                    |                 |
|                | ▣▣▢▢ ArgoCD      |                    |                 |
|                | ▣▢▢▢ Prometheus  |                    |                 |
|                | ▣▢▢▢ Zabbix      |                    |                 |

> Legend: ▣▢▢▢ basic, ▣▣▢▢ regular, ▣▣▣▢ advanced, ▣▣▣▣ expert

---

## Certifications

- Sun Certified Java Programmer for Java 1.5, 2008.
- [Google Cloud Certified Associate Cloud Engineer](https://www.credential.net/78b480e5-2bf8-4539-94fc-c2e32cd9ed01?key=3628f63f8b96f9db5ad46e29e8c6463359da22fa088ed79e8d503273951d6103&record_view=true),
  July 2021.
- [Google Cloud Certified Professional Cloud Developer](https://www.credential.net/723f3067-0dc9-4510-9974-f632b46ed867#gs.91nodn),
  August 2022.

---

## Project experience

#### DevOps Engineer

PSI Polska, GEM departament, July 2024-now

**Command** and **Control** - an energy infrastructure management platform,
multi-client (e.g. E.ON, SBB)

###### Skills:

> Kubernetes, ArgoCD, Helm, GCP, IBMCloud, Jenkins (Jenkinsfile/Groovy, JCasC),
> Nexus, Bitbucket, Ansible/AWX, Terraform, Java, Wildfly, Oracle, PostgreSQL
> (CNPG)

###### Responsibilities:

> Administering dev tools chain for 20+ team of developers and testers.
> Responding to developer team requests, pro-active approach to ease daily work
> of the team members.
>
> Maintaning supply chain including **Jenkins**, **Bitbucket**, **Nexus**,
> **Sonar** and set of SBOM tools deployed as **Kubernetes** workload with
> **ArgoCD**. Administering test environments on separate, dedicated VMs,
> deployed with **Ansible**/**AWX**.
>
> Keeping configuration in IaaC (**Terraform** provisioning IBMCloud/GCP
> resources), GitOps (**ArgoCD**, **Helm**) and CaaC (**Ansible**, **JCasC**)
> approach, with PR-based workflow, and code review from other DevOps engineers.
>
> Monitoring the environment using **Prometheus** and **Grafana**. Keeping the
> critical stack working, including outages fixing and security settings and
> updates.
>
> Keeping test environment working and problem solving needed significant
> knowledge of product building blocks: **Java** app desktop,
> **Wildfly**-deployed backend and **Oracle**/**PostgreSQL** database.
>
> Implementing pipelines for dev team, mostly as **Jenkinsfile** (**Groovy**),
> but also as a shared library, according to the DRY principle. Designing
> pipeline orchestration (mutli-job, dependent processes).

#### System Administrator

Sygnity, IT department, 2018-now

###### Skills:

> Linux, Bash, Ansible, Wazuh, Zabbix, Git, Nexus, Apache Httpd, GCP, AWS

###### Responsibilities:

> Administration and maintenance of various back-office applications, including
> the Atlassian stack. Performing upgrades, and maintenance across multiple
> **Linux** servers. Ensuring system reliability by maintaining up-to-date
> operating systems, monitoring uptime and performance with **Wazuh**, and
> applying security patches. Managing full backup and recovery procedures at the
> **VMware** infrastructure level to safeguard data and ensure business
> continuity. Performing SRE duties such as incident response, system
> troubleshooting, and on-call support to maintain high service availability and
> stability.
>
> Managing multiple Linux servers (primarily RedHat/CentOS/OEL), performing
> regular upgrades, migrations, and VM operations within VMware vCenter.
>
> Executing a wide range of SRE tasks for back-office systems. Co-administered
> **Zabbix** and **Wazuh**, including development of custom log decoders for
> server/application monitoring and post-incident analysis.
>
> Oversaw cloud platform organization administration — IAM and billing
> management, project structuring, and advisory for teams transitioning to the
> cloud, primarily **GCP**, with experience in **AWS**, **Azure**, and **OCI**.
>
> Proposing and managed software engineering tools to maintain a company-wide
> “toolbox” for production teams and prevent shadow IT — for example, deploying
> a central **Nexus** repository and containerizing **Bamboo** build agents.
>
> Implementing **Ansible**-based automations, e.g. prod-to-dev environment
> cloning, configuring rev-proxies, bulk HTTPS certificate updates, bulk
> installing agents for **Zabbix**, **Wazuh**, IBM License Metric Tool scanners.
> Developing **Ansible**-based automation for infrastructure operations,
> including environment cloning (prod-to-dev), reverse proxy configuration, bulk
> HTTPS certificate renewals, and agent installations for **Zabbix**, **Wazuh**,
> Qualys and IBM License Metric Tool.
>
> Implementing **Python**/**Go**/**Bash** CLI tools to speed up administering
> tasks, e.g. synchronizing permissions between **Nexus** and **Crowd**, getting
> and processing emails with invoices, log rotating and archiving. Creating
> simple **web pages** for utility purposes and during-maintenance landing
> pages.

#### Atlassian Administrator/Developer

Sygnity, IT department, 2018-2024

###### Skills:

> Linux, Bash, Groovy, Apache/Httpd, Jira, Bitbucket, Bamboo, Confluence, Crowd,
> Windows Server, Tomcat, Python, JavaScript, Go, Python, Ansible

###### Responsibilities:

> Managing Atlassian apps configurations. Collaborating with production teams
> and project managers across the company to streamline software delivery and
> customer support. Adapted back-office processes—such as CMDB, competency
> databases, and overtime systems—to align with **Jira** methodologies.
>
> Extending **Jira** and **Confluence** capabilities with **Groovy**-based
> ScriptRunner plugin: engineered advanced workflows, automated processes,
> custom REST endpoints and UI extensions. Creating and maintaining **Gradle**
> tools and pipelines to speed up scripts testing and deployment.
>
> Evaluation of third-party plugins for production teams and management.
> Developing custom plugins using the Atlassian SDK and **Java** to delivered
> tailored features and experience, primarly focusing on **Jira** reporting for
> management and operational needs.
>
> Delivering **Git** onboarding and best-practices training for teams migrating
> to **Bitbucket**. Providing guidance for teams adopting CI/CD on **Bamboo**
> server. Managing **Bamboo** build agents at scale using **Kubernetes** and
> standalone VMs, automated via **Ansible** (Kubespray). Acting as a consultant
> for software engineering and **DevOps** best practices to support a culture of
> acceleration and continuous improvement.
>
> Implementing **Python**/**Go**/**Bash** CLI tools to accelerate administrative
> tasks, e.g. bulk user management in **Crowd**, project migration between
> **Jira** instances, and usage reports.

#### Release Administrator

Sygnity, 2008-2019

**Sidoma** and **JMaestro** - stock market J2EE applications, multi-client
(e.g., ING, Noble Securities, BNP Paribas, Michael/Strom)

###### Skills:

> Jenkins, SVN, Git, Ant, Maven, JBoss, Linux, Bash, JavaScript

###### Responsibilities:

> Creating, developing and managing deployment pipelines, building releases,
> preparing install procedure documentation.
>
> Source code manager/integrator - merging changes between **SVN** branches
> (trunk based development, client/release branches), resolving source code
> conflicts, working closely with the production team.
>
> Developing continuous delivery from scratch - from local machine manual
> building to **Jenkins** pipeline which resulted in huge speed up of release
> delivery. Creating and managing automation scripts (mix of Ant, Maven and
> Bash), e.g. listing changes components to lower package size, auto-versioning,
> documentation generation depending on changelog.
>
> Migrating large SVN repository to **Git**, training the team for new VCS,
> adjusting existing procedures and pipelines.

#### Java Developer

Projekty Bankowe Polsoft, 2005-2008

**eDokumenty** - workflow for e-documents, multi-client (e.g., ZKZL, Toruń City
Hall, Policja Polska)

###### Skills:

> Java SE, PKI architecture

###### Responsibilities:

> Developing Bouncy Castle based **Java** application for signing/verifying
> e-documents.
>
> Implementing two way SSL/TLS login feature. Connecting to various hardware
> token providers (PKCS#11) and file-based (PKCS#12). Implementing PDF (PKCS#7)
> and XML (XML-DSig) support. Windows Server CA administration.
>
> Working with server-side code and Java-applet embedded into web applications,
> including two way SSL/TLS (logging in with certificate on chip card).

---

## Private and pet projects

> DOI (Document Object Identifier) management app for cultural publishing house
> "Czas Kultury" (NGO my partner works in). Based on **GCP**, Cloud Run, and
> Jira Cloud implemented in **Go** (work in progress, on hold).
>
> Raspberry Pi based home-lab with **Kubernetes** deployed with Kubespray (work
> in progress).
>
> Advent of Code solving, often used to learn a new programming language (Go,
> Elixir). Source code on my Github.

---

## Education

- **Poznan University of Technology**, Math master degree, thesis subject:
  _"Solving systems of linear equations in interval arithmetic"_
- **Marie Curie-Skłodowska High School** in Złotów

---

## Languages

- **Polish**: mother tongue
- **English**: C1

---

## Hobbies

- Hopeless case of **board game** geek: all kinds, from ameri-trash to euro-like
  and everything in between, especially from Uwe Rosenberg, Vital Lacerda and
  Volko Runhke.
- Acquired a taste for good **movies** from a partner. Huge fan of Wes Anderson
  (symmetry!).
- **Books**: loves great, humanistic science fiction (e.g., Stanisław Lem,
  Janusz Zajdel) but not very picky about any novel book.
- Casual **video game player** valuing a good story over competition aspect.
  Cloud gaming early adopter and enthusiast.
