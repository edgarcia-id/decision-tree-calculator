# 🌳 Enterprise Decision Tree & Expected Value Calculator

**A client-side Decision Support System (DSS) utilizing probabilistic Decision Trees to evaluate business options under uncertainty. Calculate Expected Monetary Value (EMV), mitigate risk, and generate audit-ready strategic reports.**

[![Live Application](https://img.shields.io/badge/Live_Decision_Tree-Launch_Calculator-4f46e5?style=for-the-badge&logo=githubpages)](https://edgarcia-id.github.io/decision-tree-calculator/)
[![Algorithm](https://img.shields.io/badge/Algorithm-Expected_Value_Analysis-10b981?style=for-the-badge)](#)
[![Architecture](https://img.shields.io/badge/Architecture-100%25_Client--Side-f59e0b?style=for-the-badge)](#)
[![Maintained By](https://img.shields.io/badge/Maintained_By-NusaIT-0f172a?style=for-the-badge)](https://nusait.com)

---

## 🌐 Interactive Mathematical Modeling Lab
Strategic business decisions—such as opening a new service line, selecting an IT vendor, or expanding infrastructure—are rarely certain. Making decisions based purely on "best-case scenarios" often leads to financial ruin.

We have deployed an interactive client-side Decision Tree calculator where IT Leaders, Project Managers, and C-Level Executives can map out scenarios, assign probabilities, and calculate the mathematical Expected Value to determine the most logical path forward:  
👉 **[Launch the Enterprise Decision Tree Calculator](https://edgarcia-id.github.io/decision-tree-calculator/)**

---

## 🧐 Executive Overview: Why Expected Value Matters
In project management (PMP) and corporate finance, a **Decision Tree Analysis** is a standard tool used to evaluate the implications of choosing one option over another when the outcomes are uncertain.

Instead of guessing, this engine calculates the **Expected Value (EV)**—or Expected Monetary Value (EMV)—by multiplying the probability of each outcome by its financial impact and summing the results. This prevents decision-makers from being blinded by an unlikely high payoff while ignoring highly probable catastrophic losses.

---

## 🏛️ The 3-Stage Decision Architecture

This tool automates the probabilistic math required for objective strategic planning:

```text
[ Strategic Dilemma (e.g., Build vs. Buy) ]
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 1: Option & Scenario Mapping                     │
│ • Define multiple strategic choices.                   │
│ • Define all possible outcomes (scenarios) per choice. │
└────────────────────────────────────────────────────────┘
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 2: Probability & Financial Impact                │
│ • Assign a probability (%) to each outcome (sum = 100).│
│ • Assign the net impact (profit/loss) per outcome.     │
└────────────────────────────────────────────────────────┘
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 3: Expected Value Calculation & Reporting        │
│ • Automatically calculates Expected Value per option.  │
│ • Renders a visual Decision Tree.                      │
│ • Exports an audit-ready PDF justification report.     │
└────────────────────────────────────────────────────────┘
```

---

## 🛠️ Core Features for C-Level & Project Managers

### 1. Dynamic Scenario Builder
Users can dynamically add multiple decision options and unlimited scenarios per option. The engine enforces the Law of Total Probability by visually alerting users if the sum of probabilities for any given option does not exactly equal 100%.

### 2. Expected Value (EV) Engine
The calculator instantly computes the weighted average of all possible outcomes. It automatically ranks the options and provides a clear recommendation based on the highest Expected Value, while also explicitly displaying the "Worst-Case Scenario" to aid risk-averse organizations.

### 3. Visual Decision Tree Rendering
Generates a clean, horizontal flowchart representation of the decision paths, making complex probabilistic data easy to understand during board meetings or stakeholder presentations.

### 4. Audit-Ready PDF Export
Generates a highly professional, native PDF report outlining the decision paths, outcome probabilities, financial impacts, and the final mathematical recommendation. This document serves as formal evidence for project charters or procurement justifications.

---

## 💻 Technical Architecture
This application is built with the "Reachable Code" philosophy and strict privacy standards:
* **100% Client-Side:** Written in Vanilla JavaScript. The calculation engine runs entirely within the browser. No sensitive financial projections or strategic plans are sent to external servers.
* **Embedded PDF Generation:** Utilizes a minified `jsPDF` library bundled directly within the file to generate rich, multi-page PDF reports offline without backend dependencies.
* **Responsive UI:** Clean, enterprise-focused design tailored for both desktop planning and mobile review.

---

## 👨‍💻 About the Author & Enterprise Architecture Partner

Calculating expected value is only **the planning phase**; the real challenge is **execution, secure architecture, and risk mitigation**.

If your organization requires a seasoned technology partner to conduct an **IT Vendor Audit**, manage complex **Digital Transformations**, or develop custom **ERP platforms engineered with resilience**:

**Alfredo (Ed) Garcia** is a Senior ERP Architect, IT Infrastructure Lead, and Principal Consultant at **[Nusa Industri Teknologi (NusaIT)](https://nusait.com)**. He brings deep practical expertise in bridging complex governance mandates with reachable, maintainable software architecture.

* 👔 **LinkedIn:** [Alfredo (Ed) Garcia](https://www.linkedin.com/in/alfredo-garcia-elbarta-tarigan/)
* 🏢 **Consulting Firm:** [PT Nusa Industri Teknologi (NusaIT)](https://nusait.com)
* 📧 **Consultation Inquiries:** [NusaIT Contact & Advisory](https://nusait.com/contact)

---
*© 2026 Alfredo Garcia / NusaIT. Released under the MIT License.*
