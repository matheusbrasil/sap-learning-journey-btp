# SAP BTP Learning Roadmap

![SAP BTP](https://img.shields.io/badge/SAP-BTP-0FAAFF?logo=sap&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-CAP%20%7C%20Node.js%20%7C%20UI5%20%7C%20HANA%20Cloud-0A6ED1)
![Audience](https://img.shields.io/badge/Audience-Developers%20%26%20Technical%20Leads-1F2937)
![Format](https://img.shields.io/badge/Format-Learning%20Roadmap-16A34A)
![Maintained](https://img.shields.io/badge/Status-Curated%20Links-9333EA)

A curated and practical learning roadmap for developers who want to build applications on **SAP Business Technology Platform (SAP BTP)**, with a primary focus on **CAP**, **Node.js**, **SAPUI5**, **SAP HANA Cloud**, and **SAP Business Application Studio**.

This guide is structured as a **roadmap**, not just a link collection. It can be used to onboard developers, support self-study, and define a clear progression from fundamentals to hands-on delivery.

---

## Table of Contents

- [Who this roadmap is for](#who-this-roadmap-is-for)
- [How to use this roadmap](#how-to-use-this-roadmap)
- [Visual roadmap](#visual-roadmap)
- [Phase 1 - SAP BTP Foundations](#phase-1---sap-btp-foundations)
- [Phase 2 - Core CAP Development](#phase-2---core-cap-development)
- [Phase 3 - Frontend with SAPUI5 and Fiori](#phase-3---frontend-with-sapui5-and-fiori)
- [Phase 4 - Data and Persistence with SAP HANA Cloud](#phase-4---data-and-persistence-with-sap-hana-cloud)
- [Phase 5 - Tooling and DevOps](#phase-5---tooling-and-devops)
- [Phase 6 - Hands-on Practice](#phase-6---hands-on-practice)
- [Phase 7 - Continue Learning](#phase-7---continue-learning)
- [Recommended study plan by capability](#recommended-study-plan-by-capability)
- [Recommended learning paths by profile](#recommended-learning-paths-by-profile)
- [Additional SAP learning journeys](#additional-sap-learning-journeys)
- [Reference links](#reference-links)

---

## Who this roadmap is for

This roadmap is especially useful for:

- Developers starting with SAP BTP
- CAP and Node.js developers who want a structured path
- Full-stack developers working with SAPUI5 and CAP
- Teams onboarding new developers into SAP BTP projects
- Technical leads who want a recommended study sequence
- BTP administrators and HANA-focused learners who want adjacent learning paths

---

## How to use this roadmap

Recommended order:

1. **Understand the platform**
2. **Learn the core development model with CAP**
3. **Add frontend skills with SAPUI5 and Fiori**
4. **Learn persistence with SAP HANA Cloud**
5. **Get comfortable with tooling and DevOps**
6. **Reinforce learning with hands-on tutorials and missions**
7. **Go deeper with videos, references, and samples**

If you are already experienced in one area, skip directly to the capability or profile track that matches your current level.

---

## Visual roadmap

| Phase | Capability | Main Goal | Recommended Outcome | Priority |
|---|---|---|---|---|
| 1 | SAP BTP Foundations | Understand SAP BTP, Cloud Foundry, and side-by-side extension basics | Be able to explain how BTP apps are structured and deployed | Essential |
| 2 | CAP Development | Learn CAP with Node.js and service modeling | Build and run CAP services locally and on BTP | Essential |
| 3 | SAPUI5 / Fiori | Build the frontend layer and connect it to CAP | Deliver SAP-aligned UIs for business apps | Essential for full-stack |
| 4 | HANA Cloud | Understand persistence, data modeling, and full-stack data flow | Design basic persistence for SAP BTP apps | Recommended |
| 5 | BAS and DevOps | Learn the main development workspace and delivery basics | Work efficiently in BAS and understand project delivery flow | Essential |
| 6 | Hands-on Practice | Apply knowledge in realistic exercises | Complete at least one end-to-end implementation | Essential |
| 7 | Deepening and Updates | Stay current and reinforce architectural understanding | Keep learning through videos, references, and missions | Continuous |

### Suggested visual progression

```text
Foundations → CAP → UI5/Fiori → HANA Cloud → BAS/DevOps → Hands-on Practice → Continuous Learning
```

---

## Phase 1 - SAP BTP Foundations

### Goal
Understand what SAP BTP is, how Cloud Foundry fits in, and how SAP development on BTP is typically structured.

### Recommended resources
- [Exploring SAP Business Technology Platform](https://learning.sap.com/courses/exploring-sap-business-technology-platform)
- [Building Side-by-Side Extensions on SAP BTP](https://learning.sap.com/learning-journeys/building-side-by-side-extensions-on-sap-btp)
- [Start Developing in SAP BTP](https://developers.sap.com/mission.scp-1-start-developing.html)
- [Build an Application in the Cloud Foundry Runtime](https://developers.sap.com/group.btp-cf-buildpacks.html)

### Outcome
By the end of this phase, you should understand:
- the purpose of SAP BTP
- the role of the Cloud Foundry runtime
- how applications are built and deployed on the platform
- the basics of side-by-side extensibility

---

## Phase 2 - Core CAP Development

This is the main path for developers building modern SAP BTP applications with **CAP and Node.js**.

### Goal
Learn the CAP programming model, service development, and the standard full-stack development flow on SAP BTP.

### Recommended resources
- [Develop extensions with CAP following the SAP BTP Developer's Guide](https://learning.sap.com/courses/develop-extensions-with-cap-following-the-sap-btp-developer-s-guide)
- [Develop a CAP Node.js App Using SAP Business Application Studio](https://developers.sap.com/group.appstudio-cap-nodejs.html)
- [Build a Business Application Using CAP for Node.js](https://developers.sap.com/mission.cp-starter-extensions-cap.html)

### Optional parallel path
- [Build a Business Application Using CAP for Java](https://developers.sap.com/mission.cap-java-app.html)

### Outcome
By the end of this phase, you should be able to:
- model domains and services with CAP
- implement Node.js-based CAP services
- run and test CAP apps locally and on SAP BTP
- understand the difference between CAP for Node.js and CAP for Java

---

## Phase 3 - Frontend with SAPUI5 and Fiori

### Goal
Learn how to build SAP-aligned web frontends and connect them to CAP services.

### Recommended resources
- [Developing SAPUI5 Applications](https://learning.sap.com/learning-journeys/developing-sapui5-applications)
- [Learning the Basics of SAP Fiori](https://learning.sap.com/courses/learning-the-basics-of-sap-fiori)
- [Develop Your First SAPUI5 Web App with SAP Business Application Studio](https://developers.sap.com/group.sapui5-cf-bas.html)
- [Developing an SAP Fiori Elements App Based on a CAP OData V4 Service](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service)

### Outcome
By the end of this phase, you should be able to:
- understand SAPUI5 fundamentals
- understand SAP Fiori principles
- build a frontend that consumes CAP services
- choose between freestyle UI5 and Fiori elements in common scenarios

---

## Phase 4 - Data and Persistence with SAP HANA Cloud

### Goal
Understand how SAP HANA Cloud supports application persistence and data modeling.

### Recommended resources
- [Developing Data Models with SAP HANA Cloud](https://learning.sap.com/courses/developing-data-models-with-sap-hana-cloud)
- [Get Started with SAP Business Technology Platform SAP HANA Service](https://developers.sap.com/mission.haas-get-started.html)
- [Learn the fundamentals of SAP HANA Cloud, SAP HANA database](https://discovery-center.cloud.sap/missiondetail/3643/3686/)

### Outcome
By the end of this phase, you should understand:
- when to use SAP HANA Cloud in BTP projects
- how to design basic data models
- how CAP and SAP HANA Cloud fit together in a full-stack solution

---

## Phase 5 - Tooling and DevOps

### Goal
Become productive with the main SAP development workspace and understand how to support delivery pipelines.

### Recommended resources
- [Develop cloud applications using SAP Business Application Studio](https://learning.sap.com/courses/develop-cloud-applications-using-sap-business-application-studio)
- [Exploring DevOps with SAP BTP](https://learning.sap.com/courses/exploring-devops-with-sap-btp)
- [Create a Cloud Foundry App Using SAP Cloud SDK](https://developers.sap.com/mission.cloudsdk-cf-app.html)

### Outcome
By the end of this phase, you should be able to:
- work efficiently in SAP Business Application Studio
- understand the basics of delivery and DevOps on SAP BTP
- navigate common project tooling for cloud applications

---

## Phase 6 - Hands-on Practice

### SAP Discovery Center missions
- [Build Java Applications on Cloud Foundry](https://discovery-center.cloud.sap/missiondetail/3302/3347/)
- [Develop a Full-Stack CAP Application Following the SAP BTP Developer’s Guide](https://discovery-center.cloud.sap/missiondetail/4327/4608/)
- [App Development on BTP](https://discovery-center.cloud.sap/missiondetail/4431/4717/)
- [Develop a Side-by-Side CAP-Based Extension Application Following the SAP BTP Developer's Guide](https://discovery-center.cloud.sap/missiondetail/4426/4712/)
- [Implement Observability in a Full-Stack CAP Application Following the SAP BTP Developer's Guide](https://discovery-center.cloud.sap/missiondetail/4432/4718/)
- [Get Started with SAP BTP Enterprise Account](https://discovery-center.cloud.sap/missiondetail/3019/3297/)
- [Setting up a clean-core, 3-tier, BTP landscape for extension development](https://discovery-center.cloud.sap/missiondetail/4484/4771/)
- [Set Up Replication from SAP HANA Database to SAP HANA Cloud](https://discovery-center.cloud.sap/missiondetail/4053/4263/)
- [Extend SAP S/4HANA Cloud with SAP BTP](https://discovery-center.cloud.sap/missiondetail/3277/3331/)
- [Mission 3585 / 3628](https://discovery-center.cloud.sap/missiondetail/3585/3628/)

### SAP Developers practice tutorials
- [Start Developing in SAP BTP](https://developers.sap.com/mission.scp-1-start-developing.html)
- [Build an Application in the Cloud Foundry Runtime](https://developers.sap.com/group.btp-cf-buildpacks.html)
- [Develop a CAP Node.js App Using SAP Business Application Studio](https://developers.sap.com/group.appstudio-cap-nodejs.html)
- [Build a Business Application Using CAP for Node.js](https://developers.sap.com/mission.cp-starter-extensions-cap.html)
- [Build a Business Application Using CAP for Java](https://developers.sap.com/mission.cap-java-app.html)
- [Create a Cloud Foundry App Using SAP Cloud SDK](https://developers.sap.com/mission.cloudsdk-cf-app.html)

### Outcome
By the end of this phase, you should have completed at least one or two realistic hands-on scenarios end-to-end.

---

## Phase 7 - Continue Learning

### SAP Developers YouTube
- [SAP Developers - Playlists](https://www.youtube.com/@sapdevs/playlists)
- [SAP Developers - Latest Videos](https://www.youtube.com/@sapdevs/videos)
- [SAP Cloud Application Programming Model - Devtoberfest Enablement](https://www.youtube.com/watch?v=T1gqalbwzHk&list=PL6RpkC85SLQBFi4SK77b2y4EwlXMVG0XJ)
- [SAP HANA Basics For Developers](https://www.youtube.com/playlist?list=PL6RpkC85SLQAPHYG1x6IEu_exE5pa0UK_)
- [Best Practices for CAP Node.js Apps](https://www.youtube.com/watch?v=WTOOse-Flj8)
- [The SAP BTP CLI](https://www.youtube.com/watch?v=mhk6Kot-Ays&list=PL6RpkC85SLQDXx827kdjKc6HRvdMRZ8P5)
- [SAP BTP Use Cases](https://www.youtube.com/watch?v=XJjVraTrzyk&list=PL6RpkC85SLQCNJCy8uAShcZxAYx5th05Q)

### Suggested use
Use this section to:
- revisit topics after hands-on practice
- stay current with platform updates
- explore best practices and broader architecture topics

---

## Recommended study plan by capability

### 1. SAP BTP Foundations
**Recommended duration:** 1 week  
**Study plan:**
- Complete the SAP BTP foundations course
- Review side-by-side extension concepts
- Finish at least one SAP Developers mission on BTP basics and Cloud Foundry

**Minimum target output:**
- Explain SAP BTP services at a high level
- Describe Cloud Foundry and the side-by-side extension model

### 2. CAP and Node.js
**Recommended duration:** 2 to 3 weeks  
**Study plan:**
- Follow the CAP course from SAP Learning
- Build one CAP Node.js app in BAS
- Complete one end-to-end CAP mission

**Minimum target output:**
- Create CDS models and services
- Run a CAP app locally and deploy it to BTP
- Explain the role of services, entities, and handlers

### 3. SAPUI5 and Fiori
**Recommended duration:** 2 weeks  
**Study plan:**
- Learn SAPUI5 basics
- Complete the Fiori basics course
- Build one small UI5 application or Fiori Elements app consuming CAP services

**Minimum target output:**
- Build a basic UI that reads data from an OData service
- Explain when to use freestyle UI5 versus Fiori elements

### 4. SAP HANA Cloud
**Recommended duration:** 1 to 2 weeks  
**Study plan:**
- Complete the HANA Cloud data-modeling course
- Review one Discovery Center mission
- Connect HANA persistence to a sample app or understand the flow conceptually

**Minimum target output:**
- Explain when HANA Cloud is needed in a BTP app
- Understand basic data-modeling and persistence concepts

### 5. BAS and DevOps
**Recommended duration:** 1 week  
**Study plan:**
- Work through the BAS course
- Review DevOps on SAP BTP
- Practice the local development, Git, and deployment flow

**Minimum target output:**
- Create and use a BAS dev space confidently
- Explain the basics of CI/CD and delivery on BTP

### 6. Hands-on practice and consolidation
**Recommended duration:** 2 to 3 weeks  
**Study plan:**
- Pick one full-stack mission and complete it end-to-end
- Revisit weak areas from previous phases
- Document what you built in a small project summary

**Minimum target output:**
- Finish at least one realistic implementation flow
- Be able to explain the architecture of your sample solution

---

## Recommended learning paths by profile

### 1. Beginner SAP BTP developer
Follow the phases in order:
- Phase 1
- Phase 2
- Phase 3
- Phase 5
- Phase 6

### 2. CAP / Node.js developer
Prioritize:
- Phase 1
- Phase 2
- Phase 4
- Phase 5
- Phase 6

### 3. Full-stack developer on SAP BTP
Prioritize:
- Phase 1
- Phase 2
- Phase 3
- Phase 4
- Phase 5
- Phase 6

### 4. UI5 developer moving into BTP
Prioritize:
- Phase 1
- Phase 3
- Phase 2
- Phase 5

### 5. Developer preparing for project work
Prioritize:
- Phase 1
- Phase 2
- one tutorial from Phase 3
- one tutorial from Phase 4
- one mission from Phase 6

### 6. BTP administrator / platform owner
Prioritize:
- Phase 1
- Additional SAP Learning Journeys
- DevOps topics in Phase 5

### 7. HANA specialist / database-focused learner
Prioritize:
- Phase 4
- Additional SAP Learning Journeys
- selected hands-on missions from Phase 6

---

## Additional SAP Learning Journeys

These are valuable companion learning journeys if you want to expand beyond application development into platform administration and database specialization.

- [Building Side-by-Side Extensions on SAP BTP](https://learning.sap.com/learning-journeys/building-side-by-side-extensions-on-sap-btp)
- [Administrating SAP Business Technology Platform](https://learning.sap.com/learning-journeys/administrating-sap-business-technology-platform-1)
- [Becoming a Certified Database Administrator - SAP HANA](https://learning.sap.com/learning-journeys/becoming-a-certified-database-administrator-sap-hana)

---

## Reference links

### Official SAP references
- [SAP Cloud Application Programming Model](https://cap.cloud.sap/docs/)
- [SAP Cloud SDK](https://sap.github.io/cloud-sdk/)
- [SAP Learning](https://learning.sap.com/)
- [SAP Developers](https://developers.sap.com/)
- [SAP Discovery Center](https://discovery-center.cloud.sap/)
- [SAP Samples on GitHub](https://github.com/SAP-samples)
- [SAP Developers YouTube](https://www.youtube.com/@sapdevs)

### Recommended use of this section
Use these links as your fallback reference set when you need:
- official documentation
- step-by-step tutorials
- sample repositories
- current SAP developer videos

---

## Suggested maintenance notes

To keep this roadmap useful over time:
- review SAP Learning and SAP Developers links periodically
- replace placeholder Discovery Center mission names with official titles when available
- refresh the YouTube section with newer SAP Developers playlists and event sessions
- keep deprecated platforms and outdated links out of the roadmap
