# Aerospace PLM System Customization 🚀🗄️

[![Platform](https://img.shields.io/badge/Platform-Aras_Innovator-red.svg)](https://www.aras.com/)
[![Domain](https://img.shields.io/badge/Domain-Aerospace_Manufacturing-blue.svg)]()
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

Architectural design and customization of a **Product Lifecycle Management (PLM)** system using **Aras Innovator**, specifically tailored for the stringent requirements of the aerospace manufacturing industry.

Developed for the **Aerospace Production (Producción Aeroespacial)** course within the Master's Degree in Aeronautical Engineering at Universidad de Sevilla (ETSI).

---

## 📌 Project Overview

Modern aerospace manufacturing relies heavily on robust PLM systems to manage complex product structures, track revisions, and ensure traceability from design to production. 

This project does not focus on traditional software development, but rather on **Enterprise System Architecture**. It involves the complete customization of a blank Aras Innovator environment to support the operational and manufacturing workflows of an aerospace organization.

### 🎯 Key Objectives & Scope
* **Organizational Modeling:** Definition of the corporate hierarchy, identities, and role-based permissions (Clients, Engineers, Managers).
* **Product Data Management (PDM):** Creation of a custom data model capturing the complete product breakdown structure:
  * Product Families & Product Lines
  * Products & Specific Models
  * Individual Parts & BOMs (Bill of Materials)
* **Manufacturing Process Management (MPM):** Structuring the production phase by defining Process Plans, individual Processes, Workstations, and associated Resources.
* **Lifecycle & Workflow Engineering:** Implementation of custom item lifecycles (e.g., Preliminary, In Review, Released, Rejected) with automated state transitions.
* **UI/UX Customization:** Tailoring item forms and integrating minor JavaScript event handlers (onLoad) to dynamically hide/show tabs and fields based on the item's current lifecycle state.

## 📂 Repository Contents

Since this project was developed natively within the Aras Innovator GUI and database, this repository serves as a documentation archive of the system architecture:

* **`docs/`**: Contains the comprehensive project report (`Report.pdf`). This document acts as the technical blueprint, detailing the requirements analysis, the custom ItemTypes created, relationship matrices, and the implemented JavaScript form events.

## 🛠️ Tech Stack & Methodology

* **PLM Platform:** Aras Innovator
* **Customization Tools:** ItemType creation, Relationship Grids, Lifecycle Maps, Form Editor.
* **Scripting:** Client-side JavaScript (Form Events/Methods).

## 👨‍💻 Authors

* **Alejandro Rivera Míguez**
* **Pablo Sánchez Mora**
* **Narciso Valverde González**

---

Professor: **Jesús Racero Moreno**  
Master in Aeronautical Engineering | Universidad de Sevilla

---
*Disclaimer: This is an academic project. The repository contains the architectural documentation and functional blueprints of the PLM customization, rather than deployable source code.*
