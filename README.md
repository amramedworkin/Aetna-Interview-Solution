![AetnaCVS Logo](./logo.svg)
# Aetna Interview
## *Solutions Architecture Package*
 
Welcome to the Solution Architecture Package for the Aetna Interview Project - Movie API. This document is your guide to understanding the structure, content, and usage of the deliverables in this repository. Each folder and file in this package serves a specific purpose aligned with the architecture lifecycle: from discovery to delivery.

---
`Logical Architecture`
![Logical Architecture](./03_Architecture_Design/03_08_Logical_Architecture_Diagram.svg)

`Physical Architecture`
![Physical Deployment Diagram](./03_Architecture_Design/03_09_Physical_Deployment_Diagram.svg)

## 📘 00_ReadMe/
### `00_00_ReadMe.md` [📝](00_ReadMe/00_00_ReadMe.md)
This file. Describes the full structure, purpose, and navigation of the solution architecture package.

---

## 💼 01_Business_Context/
### `01_01_Project_Goals_and_Objectives.docx` [📄](01_Business_Context/01_01_Project_Goals_and_Objectives.docx)
Outlines the business drivers, success criteria, and objectives of the project.

### `01_02_Stakeholder_Map.xlsx` [📊](01_Business_Context/01_02_Stakeholder_Map.xlsx)
Maps key stakeholders, their influence, and their engagement level. Used to drive communication and decision-making alignment.

### `01_03_Business_Capability_Map.pptx` [📽️](01_Business_Context/01_03_Business_Capability_Map.pptx)
Visual map connecting business capabilities to proposed technical components and business outcomes.

---

## ✅ 02_Requirements/
### `02_04_Functional_Requirements.docx` [📄](02_Requirements/02_04_Functional_Requirements.docx)
Captures user stories and high-level system functions required to meet the business needs.

### `02_05_NonFunctional_Requirements.xlsx` [📊](02_Requirements/02_05_NonFunctional_Requirements.xlsx)
Defines critical quality attributes including availability, performance, security, and scalability.

### `02_06_Traceability_Matrix.xlsx` [📊](02_Requirements/02_06_Traceability_Matrix.xlsx)
Ensures that each business requirement is mapped to system components and addressed within the architecture.

---

## 🏗️ 03_Architecture_Design/
### `03_07_Context_Diagram.puml` [🖼️](03_Architecture_Design/03_07_Context_Diagram.svg)
Visual diagram showing the boundaries of the system, external users, and interfacing systems.

### `03_08_Logical_Architecture.puml / 03_08_Logical_Architecture.svg` [🖼️full,](03_Architecture_Design/03_08_Logical_Architecture_Diagram.svg) [🟢production,](03_Architecture_Design/08_Logical_Architecture/03_08a_Logical_Architecture_PRODUCTION_Diagram.svg) [🔵development,](03_Architecture_Design/08_Logical_Architecture/03_08b_Logical_Architecture_DEVELOPMENT_Diagram.svg) [⚙️CICD](03_Architecture_Design/08_Logical_Architecture/03_08c_Logical_Architecture_CICD_PIPELINE.svg)
Shows the logical structure of components, services, and data flow  abstracted from physical deployment details.

### `03_09_Physical_Deployment_Diagram.puml / 03_09_Physical_Deployment_Diagram.svg` [🖼️full,](03_Architecture_Design/03_09_Physical_Deployment_Diagram.svg) [🟢production,](03_Architecture_Design/09_Physical_Deployment_Architecture/03_09a_Physical_Deployment_PRODUCTION_Architecture.svg) [🔵development](03_Architecture_Design/09_Physical_Deployment_Architecture/03_09b_Physical_Deployment_DEVELOPMENT_Architecture.svg)
Provides the actual deployment layout (AWS resources such as VPCs, ECS, RDS, etc.) for production infrastructure.

### `03_10_Data_Model.puml / 03_10_Data_Model.svg` [🖼️](03_Architecture_Design/03_10_Data_Model.svg)
Logical entity-relationship diagram representing domain models such as Movies and Ratings.

### `03_11_Integration_Model.puml / 03_11_Integration_Model.svg` [🖼️](03_Architecture_Design/03_11_Integration_Model.svg)
Details interfaces, API endpoints, protocols, and data flow across systems and services.

### `03_12_Security_Architecture_Overview.docx` [📄,](03_Architecture_Design/12_Security_Architecture/03_12_Security_Architecture_Overview.docx) [🖼️](03_Architecture_Design/03_12_Security_Architecture_Overview.svg)
Covers authentication, authorization, data encryption, access policies, and compliance requirements using AWS services like Cognito and Secrets Manager.

### `📁 03_13_ADRs/`
Contains Architecture Decision Records (`.md` files) documenting important design decisions, context, alternatives considered, and consequences.

---

## ⚖️ 04_Risk_and_Tradeoffs/
### `04_14_Risk_Register.xlsx` [📊](04_Risk_and_Tradeoffs/04_14_Risk_Register.xlsx)
Lists risks specific to the architecture, their probability and impact, and defined mitigation strategies.

### `04_15_TradeOff_Analysis_Matrix.docx` [click](04_Risk_and_Tradeoffs/04_15_TradeOff_Analysis_Matrix.docx)
Evaluates key architecture options and their trade-offs (e.g., performance vs. cost).

### `04_16_Assumptions_And_Dependencies.docx` [click](04_Risk_and_Tradeoffs/04_16_Assumptions_And_Dependencies.docx)
Documents key assumptions (e.g., developer skill sets, AWS usage) and external dependencies (e.g., data availability).

---

## 🗺️ 05_Roadmap/
### `05_17_Implementation_Roadmap.xlsx` [📊](05_Roadmap/05_17_Implementation_Roadmap.xlsx)
Outlines the project phases, timelines, and key milestones.

### `05_18_Phased_Architecture_Timeline.pptx` [click](05_Roadmap/05_18_Phased_Architecture_Timeline.pptx)
Presentation slide summarizing the phased implementation plan in a visual format for stakeholder review.

---

## 📦 06_Final_Delivery/
### `06_19_Architecture_Overview_OnePager.pdf` [click](06_Final_Delivery/06_19_Architecture_Overview_OnePager.pdf)
Single-page visual + narrative summary of the architecture  suitable for executive review.

### `06_20_Final_Presentation_Deck.pptx` [click](06_Final_Delivery/06_20_Final_Presentation_Deck.pptx)
10-slide (max) visual architecture presentation, tailored for a 30-minute briefing covering design, value alignment, risks, and roadmap.

### `06_21_Deliverables_Index.xlsx` [📊](06_Final_Delivery/06_21_Deliverables_Index.xlsx)
Checklist of all included artifacts with descriptions, intended audiences, and ownership metadata.

---

## 🧪 07_Internal_Working_Files/ *(Not client-deliverable)*
Contains scratch work, interview notes, and design prototypes.

- `Interviews/`: Discovery notes, user interviews
- `Draft_Diagrams/`: Miro or Lucidchart exports, intermediate design versions
- `Notes/`: Raw thinking, workshop notes, sticky notes
- `Tools/`: Templates, scripts, helpers used during development

---

# How to Use This Package

| Role | How to Use |
|------|------------|
| **Architect** | Reference all design diagrams and ADRs during review and implementation phases. |
| **Product Owner** | Focus on the capability map, traceability matrix, and implementation roadmap to align with business needs. |
| **Dev Team** | Review logical/physical diagrams, data model, and integration models. Use ADRs for implementation decisions. |
| **Security Team** | Focus on `12_Security_Architecture_Overview.docx`, `05_NonFunctional_Requirements.xlsx`, and `14_Risk_Register.xlsx`. |
| **Executives** | Use `19_Architecture_Overview_OnePager.pdf` and `20_Final_Presentation_Deck.pptx` for quick understanding. |
| **DevOps / Infra** | Use deployment diagrams, `17_Implementation_Roadmap.xlsx`, and CI/CD definitions (within ADRs and diagrams). |

---

## Tooling and Standards

- Diagrams: Created in PlantUML (`.puml`), exportable to `.svg` or `.png`
- Text Docs: MS Word (`.docx`)
- Spreadsheets: MS Excel (`.xlsx`)
- Presentations: MS PowerPoint (`.pptx`)
- ADRs: Markdown (`.md`)  GitHub-friendly
- All files version-controlled in GitHub
- Follows TOGAF-style layered methodology and AWS Well-Architected Framework

---

## Versioning & Updates

This package represents **Version 1.0** of the architecture. Updates will be maintained via GitHub PRs and noted in `21_Deliverables_Index.xlsx`.

---

For questions or contributions, contact the Architecture Owner or refer to the `Deliverables_Index.xlsx` for artifact ownership.


