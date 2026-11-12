<h1 align="center">Rida Najjari</h1>

<p align="center">
  <b>Salesforce Consultant · Apex &amp; LWC Developer · Administrator</b><br/>
  4× Salesforce Certified · Paris, France · open to France &amp; Morocco
</p>

<p align="center">
  <a href="https://rida-najjari.netlify.app"><img src="https://img.shields.io/badge/Portfolio-rida--najjari.netlify.app-0A66C2?style=flat&logo=netlify&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/rida-najjari/"><img src="https://img.shields.io/badge/LinkedIn-rida--najjari-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:najjaririda6@gmail.com"><img src="https://img.shields.io/badge/Email-najjaririda6%40gmail.com-555555?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### About me

I'm an engineer with nearly four years in IT and a **dual developer + administrator** profile on Salesforce. I build
Apex (triggers, Batch, Schedulable, Queueable), Lightning Web Components, Flows and REST integrations on **Sales
Cloud, Service Cloud and Experience Cloud**, and I take them from requirements to production: specs, deployments
across Dev / UAT / Prod, and L1–L3 support under SLA.

**What drives me:** turning a business process into a Salesforce solution that people actually use, and building
it properly: bulk-safe, secure, tested, and documented so the next admin or developer can pick it up. I keep
practising in public: every project below is deployed and tested in a real Salesforce org, and its README explains
the design choices, not just the code.

- 💼 **Salesforce Consultant (work-study)** at Vulcain Engineering Group, since January 2026
- 🎓 Engineering degree in Computer Science &amp; Networks (EMSI) · Data Engineer master's in progress (Institut F2i)
- 🔎 Looking for a permanent role (CDI) as a Salesforce Consultant, Developer or Administrator
- 🌍 French · English · Arabic

### Certifications

![Platform Administrator](https://img.shields.io/badge/Salesforce-Platform%20Administrator-00A1E0?style=flat&logo=salesforce&logoColor=white)
![Platform App Builder](https://img.shields.io/badge/Salesforce-Platform%20App%20Builder-00A1E0?style=flat&logo=salesforce&logoColor=white)
![Platform Developer I](https://img.shields.io/badge/Salesforce-Platform%20Developer%20I-00A1E0?style=flat&logo=salesforce&logoColor=white)
![Salesforce Associate](https://img.shields.io/badge/Salesforce-Associate-00A1E0?style=flat&logo=salesforce&logoColor=white)

### Salesforce projects

Public, documented code: each repo has a README covering the business need, the design choices and how to deploy it.

| Project | What it shows |
| --- | --- |
| **[case-escalation-automation](https://github.com/ridanajjari/case-escalation-automation)** · Service Cloud | Hourly Batch Apex that escalates Cases breaching their SLA. Thresholds live in Custom Metadata, age is measured from the last escalation (no double escalation), and partial-success DML only notifies owners (Chatter + email) for rows that were saved. **15/15 Apex tests passing · 88% / 100% coverage.** |
| **[lead-auto-assignment](https://github.com/ridanajjari/lead-auto-assignment)** · Sales Cloud | Before-save trigger on the Trigger Handler pattern. Routing rules in Custom Metadata, most specific first, to a user or a queue; assignees resolved in bulk with cached queries, and misconfigured rules skipped instead of failing the save. **15/15 Apex tests passing · 93% / 100% coverage.** |
| **[lwc-kpi-dashboard](https://github.com/ridanajjari/lwc-kpi-dashboard)** · LWC | KPI component loaded with `@wire` and refreshed with `refreshApex`; Apex controller with `WITH USER_MODE`, Custom Labels and SLDS styling hooks. **7/7 Apex tests · 100% coverage · 5 Jest tests.** |
| **[salesforce-api-integration](https://github.com/ridanajjari/salesforce-api-integration)** · Integration | REST callout through a Named Credential with the API key kept out of code and the repo, typed JSON parsing, timeout and error handling, and a Queueable + Flow-invocable action for bulk updates. **18/18 Apex tests passing · 96–100% coverage.** |
| **[admin-flow-toolkit](https://github.com/ridanajjari/admin-flow-toolkit)** · Flow | Five Flows with fault paths: record-triggered (before / after save), scheduled flows and a scheduled path, deployed to a Salesforce org and retrieved so the XML is exactly what the platform emits. |

Tests and coverage were measured in a Salesforce Developer Edition org at API 68.0.

### Toolbox

**Salesforce development** &nbsp;
![Apex](https://img.shields.io/badge/-Apex-00A1E0?style=flat&logo=salesforce&logoColor=white)
![LWC](https://img.shields.io/badge/-Lightning%20Web%20Components-00A1E0?style=flat&logo=salesforce&logoColor=white)
![SOQL](https://img.shields.io/badge/-SOQL-00A1E0?style=flat&logo=salesforce&logoColor=white)
![Flow](https://img.shields.io/badge/-Flow-00A1E0?style=flat&logo=salesforce&logoColor=white)
![REST](https://img.shields.io/badge/-REST%20%2F%20Named%20Credentials-00A1E0?style=flat&logo=salesforce&logoColor=white)

**Administration** &nbsp; Users, profiles, roles &amp; permission sets · sharing model · validation rules · objects &amp; fields ·
record types &amp; page layouts · Lightning App Builder · reports &amp; dashboards · sandboxes

**Data &amp; DevOps** &nbsp;
![Salesforce CLI](https://img.shields.io/badge/-Salesforce%20CLI-333333?style=flat&logo=salesforce&logoColor=00A1E0)
![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)
![GitLab CI](https://img.shields.io/badge/-GitLab%20CI-333333?style=flat&logo=gitlab)
![Jenkins](https://img.shields.io/badge/-Jenkins-333333?style=flat&logo=jenkins)
&nbsp; Data Loader · Workbench · Change Sets

**Also** &nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
![React](https://img.shields.io/badge/-React-333333?style=flat&logo=react)
![Java](https://img.shields.io/badge/-Java-333333?style=flat&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-333333?style=flat&logo=springboot)
![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
![SQL](https://img.shields.io/badge/-SQL-333333?style=flat&logo=postgresql)

**Ways of working** &nbsp; Agile Scrum · Kanban · requirements gathering · functional &amp; technical specs · UAT · ITSM / SLA

### Experience

- **Salesforce Consultant (work-study)** — Vulcain Engineering Group · Jan 2026 – present
  LWC, Apex, Batch and Flow on Sales &amp; Service Cloud; admin and Change Set deployments Dev → UAT → Prod; data
  migration with Data Loader / Workbench; specs, release notes and L1–L3 incidents under SLA for several clients.
- **Technical Support Engineer** — Dell Technologies · Sep 2023 – Dec 2025
  High-volume L1/L2 support under SLA; improved ticket categorisation, escalation routing and resolution times.
- **Software Engineer** — Sofrecom · Oct 2022 – Apr 2023
  Customer loyalty web &amp; mobile app (React, React Native, REST APIs, Redux Toolkit, Jest).

---

<p align="center">Open to Salesforce Consultant / Developer / Administrator opportunities: let's talk on
<a href="https://www.linkedin.com/in/rida-najjari/">LinkedIn</a> or by <a href="mailto:najjaririda6@gmail.com">email</a>.</p>
