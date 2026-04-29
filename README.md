# Cybersecurity Governance & Financial Modeling: ITIL 4 & eTOM Frameworks

## 📌 Project Overview
This project serves as a comprehensive guide to integrating **ITIL 4** and **eTOM** frameworks within a Cybersecurity context. It moves beyond technical implementation to focus on **Service Management**, **Governance**, and **Financial Quantification (CRQ)**, ensuring that security operations are aligned with business value.

## 🚀 Framework Convergence

### 1. ITIL 4 (Service Value System)
ITIL 4 shifts the focus from "processes" to "value co-creation." In this repository, we explore how Cybersecurity acts as a service provider to the business.
*   **SVS (Service Value System):** Integration of Opportunity/Demand into Value through Guiding Principles, Governance, and Practices.
*   **Service Value Chain:** A set of interconnected activities (Plan, Improve, Engage, Design, Build, Deliver) to realize security value.

### 2. eTOM (Business Process Framework)
While ITIL provides the "What," eTOM provides the "How" for Telecommunications and Service Providers.
*   **Strategy & Infrastructure:** Long-term security architecture and lifecycle management.
*   **Operations:** Focused on day-to-day incident management and SOC performance.

## 📊 Financial Modeling & Risk Quantification
One of the most critical aspects of this project is translating technical vulnerabilities into financial risk language for stakeholders.

### Risk Calculation (ALE Model)
*   **Asset Value (AV):** Monetary value of the data or infrastructure.
*   **Exposure Factor (EF):** Impact percentage of a specific threat.
*   **SLE (Single Loss Expectancy):** `AV * EF`
*   **ARO (Annual Rate of Occurrence):** Estimated frequency of an incident per year.
*   **ALE (Annual Loss Expectancy):** `SLE * ARO` (The key metric for ROI/ROSI analysis).

### ROSI (Return on Security Investment)
To justify the budget for a new tool (e.g., SIEM or EDR):
`ROSI = (Risk Mitigated - Cost of Solution) / Cost of Solution`

## 🛠️ Operational Strategy: Internal vs. Outsourced SOC
The governance model evaluates the financial impact of different SOC structures:

| Aspect | Internal SOC (In-House) | Managed Security Service (MSSP) |
| :--- | :--- | :--- |
| **Costs** | High CAPEX & OPEX (Staffing/Infrastructure) | Predictable Monthly Fee (OPEX) |
| **Knowledge** | Deep Institutional Knowledge | Broad Industry Expertise |
| **Control** | Full Visibility and Customization | Limited by SLA and Multi-tenancy |
| **Scalability**| Resource-intensive and Slow | Modular and Rapid |

## 📂 Implementation Roadmap
1. **Service Definition:** Define security capabilities as "Services" in a Catalog.
2. **Double Filter Logic:** Refine business data through financial and operational filters to identify true cost drivers (FTEs, Licenses, Infrastructure).
3. **Maturity Assessment:** Apply the **Information Technology Investment Management (ITIM)** logic to move from reactive to strategic investment.
