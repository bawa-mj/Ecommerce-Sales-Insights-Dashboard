# 🛒 Ecommerce Sales Insights Dashboard

An interactive, data-driven Power BI solution designed to track, analyze, and optimize online retail operations. This dashboard processes cross-channel transactional data to surface key ecommerce performance indicators, helping stakeholders understand consumer behavior and revenue velocity.

## 🚀 Key Business Metrics Tracked
*   **Revenue & Profitability:** Real-time analysis of gross merchandise value (GMV), net profit margins, and average order value (AOV).
*   **Customer Segmentation:** Insights into user demographics, purchase frequency, and lifetime value (LTV).
*   **Product Performance:** Deep-dive into top-selling product categories, inventory stock turns, and returns analysis.
*   **Geographical Breakdown:** Visual mapping of sales distribution and high-value regional markets.

## 📁 Repository Structure
The repository contains the core architectural components of the extracted Power BI template:

*   **`sales dashboard.pbix`** — The production-ready Power BI desktop file containing pre-built DAX measures, star-schema data models, and visualization canvases.
*   **`DataModel`** — Schema definitions and dimensional table relationships mapping orders, products, and customer entities.
*   **`Report/Layout`** — UI grid configuration, visual alignment coordinates, and responsive sizing configurations.
*   **`Report/StaticResources/`** — Asset files including the modern workspace visual layer (`dark-gradient04501070646154981.jpg`).
*   **`Report/SharedResources/BaseThemes/`** — The central styling sheet (`CY26SU02.json`) managing conditional formatting rules, dark-mode styling blocks, and universal typography configurations.

## 🛠️ Setup & Local Deployment

### Prerequisites
*   Windows OS (or a compatible VM environment).
*   Latest version of [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.

### Step-by-Step Installation
1. Clone the repository directly to your local workspace:
   ```bash
   git clone [https://github.com/your-username/Ecommerce-Sales-Insights-Dashboard.git](https://github.com/your-username/Ecommerce-Sales-Insights-Dashboard.git)
   cd Ecommerce-Sales-Insights-Dashboard
