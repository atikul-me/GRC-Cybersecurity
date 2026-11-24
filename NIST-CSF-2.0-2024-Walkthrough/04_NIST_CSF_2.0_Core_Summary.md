# 🛡️ NIST Cybersecurity Framework (CSF) 2.0 — Introduction to the CSF Core

> **Reference:** NIST CSWP 29 (February 26, 2024\)  
> **Topic:** Section 2 \- Introduction to the CSF Core

---

## 📌 Overview

The **CSF Core** (Appendix A of NIST CSF 2.0) is a structured set of cybersecurity outcomes arranged hierarchically by **Function**, **Category**, and **Subcategory**.

### Key Principles to Remember:

* **Not a Checklist:** These outcomes are *not* a rigid checklist of actions. Specific actions taken to achieve an outcome will **vary** depending on the organization, use case, and responsible individuals.  
* **No Implied Sequence:** The order and size of Functions, Categories, and Subcategories do not dictate the sequence or relative importance of achieving them.  
* **Risk Operationalization:** The structure is designed to **resonate** most with professionals charged with operationalizing risk management within an organization.

---

## 🏗️ CSF Core Structure

The framework breaks down cybersecurity outcomes into three levels:

```
[ Cybersecurity Framework Core ]
               │
               ├──► Functions (Highest level, named after verbs)
               │       │
               │       └──► Categories (Related cybersecurity outcomes)
               │               │
               │               └──► Subcategories (Specific technical & management outcomes)
```

* **Functions:** Organize cybersecurity outcomes at their highest level. Each Function is named after a **verb** that summarizes its contents.  
* **Categories:** Group related cybersecurity outcomes that collectively comprise a Function.  
* **Subcategories:** Further divide each Category into more specific outcomes of technical and management activities. *(Note: Subcategories are **not exhaustive**, but they describe detailed outcomes supporting each Category).*

---

## ⚙️ The 6 CSF Core Functions

The CSF Core is built around six interconnected Functions: **GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND,** and **RECOVER**.

### 1\. 🏛️ GOVERN (GV)

> *"The organization’s cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored."*

* **Role:** Informs **what an organization may do to achieve** and prioritize the outcomes of the other five Functions in the context of its mission and stakeholder expectations.  
* **Enterprise Integration:** Critical for incorporating cybersecurity into an organization’s broader **Enterprise Risk Management (ERM)** strategy.  
* **Key Focus Areas:**  
  * Understanding of organizational context  
  * Establishment of cybersecurity strategy  
  * Cybersecurity supply chain risk management  
  * Roles, responsibilities, and authorities  
  * Policy and **oversight of cybersecurity strategy**

---

### 2\. 🔍 IDENTIFY (ID)

> *"The organization’s current cybersecurity risks are understood."*

* **Role:** Understanding the organization’s assets (data, hardware, software, systems, facilities, services, people), suppliers, and related risks enables an organization to prioritize its **efforts consistent with its risk management strategy** and mission needs identified under **GOVERN**.  
* **Continuous Improvement:** Includes identifying improvement opportunities for policies, plans, processes, procedures, and practices to inform **efforts** across all six Functions.

---

### 3\. 🛡️ PROTECT (PR)

> *"Safeguards to manage the organization’s cybersecurity risks are used."*

* **Role:** Once assets and risks are identified and prioritized, **PROTECT** supports the **ability to secure** those assets to prevent or lower the likelihood and impact of adverse events, while increasing the ability to **take advantage of opportunities**.  
* **Key Outcomes:**  
  * Identity management, authentication, and access control  
  * Awareness and training  
  * Data security  
  * Platform security (securing hardware, software, and services of physical and virtual platforms)  
  * Resilience of technology infrastructure

---

### 4\. 📡 DETECT (DE)

> *"Possible cybersecurity attacks and compromises are found and analyzed."*

* **Role:** Enables the **timely discovery** and **analysis** of anomalies, indicators of compromise (IoCs), and other potentially adverse events indicating that cybersecurity attacks and incidents are occurring.  
* **Impact:** Directly supports **successful incident response and recovery activities**.

---

### 5\. 🚨 RESPOND (RS)

> *"Actions regarding a detected cybersecurity incident are taken."*

* **Role:** Supports the ability to contain the **effects** of cybersecurity incidents.  
* **Key Outcomes:** Incident management, analysis, mitigation, reporting, and communication.

---

### 6\. 🔄 RECOVER (RC)

> *"Assets and operations affected by a cybersecurity incident are restored."*

* **Role:** Supports the **timely restoration** of normal operations to reduce the effects of cybersecurity incidents and enable **appropriate communication** during recovery efforts.

---

## 💡 Strategic Insight: Turning Risk Management into Opportunity

> While many cybersecurity risk management activities focus on preventing negative events, they may also support **taking advantage of positive opportunities**.

> * **Example:** Actions to reduce risk can benefit an organization by **increasing revenue**—such as offering excess facility space to a commercial hosting provider and migrating a major financial system from an in-house data center to the hosting provider to reduce cybersecurity risks.

---

## 🔄 How the Functions Relate (The CSF Wheel)

```
          [ RECOVER ] ◄───► [ IDENTIFY ]
               ▲                 ▲
               │   ┌─────────┐   │
               ├───┤ GOVERN  ├───┤
               │   └─────────┘   │
               ▼                 ▼
          [ RESPOND ] ◄───► [ PROTECT ]
               ▲                 ▲
               └───►[ DETECT ]◄──┘
```

* **GOVERN at the Center:** **GOVERN** sits in the center of the wheel because it **informs** how an organization will implement **the other five Functions**.  
* **Concurrent & Continuous Execution:**  
  * All Functions should be addressed **concurrently**.  
  * **GOVERN, IDENTIFY, PROTECT,** and **DETECT** actions should happen **continuously**.  
  * **RESPOND** and **RECOVER** actions must be **ready at all times** and triggered when incidents occur.  
* **Incident Lifecycle Roles:**  
  * **Prevent & Prepare:** GOVERN, IDENTIFY, and PROTECT outcomes.  
  * **Discover & Manage:** GOVERN, DETECT, RESPOND, and RECOVER outcomes.

---

## 🌐 Scope & Future-Readiness

The Functions, Categories, and Subcategories **apply to all ICT** (Information and Communications Technology) used by an organization, including:

* Information Technology (**IT**)  
* Internet of Things (**IoT**)  
* Operational Technology (**OT**)

It applies across all environments—including **cloud, mobile, and artificial intelligence (AI) systems**—and is designed to be forward-looking to adapt to **future changes** in technologies and environments.