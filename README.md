# 🏥 NHS Healthcare Data Visualisation and Evaluation (UK 2022–2023)

![Tableau](https://img.shields.io/badge/Tableau-Visualization-blue?logo=tableau)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-success?logo=microsoft-excel)
![Python](https://img.shields.io/badge/Language-English-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📊 Introduction
This project evaluates and visualizes **NHS healthcare data** across the **United Kingdom (2022–2023)**.  
Two interactive **Tableau dashboards** were created to analyze patient trends, waiting times, and healthcare resource allocation across NHS trusts.

- 🧑‍⚕️ **Dashboard 1** – For the **general public**: waiting lists, mean time waited, mean length of stay, and NHS performance.  
- 🏛️ **Dashboard 2** – For **managers and policymakers**: inpatient/outpatient volumes, hospital counts, and specialties.

👉 **[View Dashboards on Tableau Public](https://public.tableau.com/app/profile/sukhman.singh1298/viz/CapstoneDataVisualisation_17188433554620/Dashboard1_1?publish=yes)**

---

## 🩺 Objectives
- Analyze NHS datasets for **patterns in waiting times, patient demographics, and efficiency**.  
- Visualize **inpatient vs outpatient trends** to support decision-making.  
- Deliver insights for:
  - **Public use** (patients making treatment choices)
  - **Healthcare management** (resource planning and policy decisions)

---

## 🧭 Table of Contents
- [Dashboards Overview](#-dashboards-overview)
- [Data Preparation](#-data-preparation)
- [Design & Visualisation Principles](#-design--visualisation-principles)
- [Data Sources](#-data-sources)
- [Target Audience](#-target-audience)
- [Evaluation Summary](#-evaluation-summary)
- [References](#-references)
- [Tools & Technologies](#-tools--technologies)
- [Usage Instructions](#-usage-instructions)
- [Contact](#-contact)

---

## 📈 Dashboards Overview

<details>
<summary><b>🧑‍⚕️ Dashboard 1 – Public-Facing Insights</b></summary>

**Focus:** Waiting lists, mean time waited, mean age, and hospital stay durations.

### Key Visuals
- **Top 5 & Bottom 5 ICBs (Urgent Mental Health Cases)**  
  → Bar chart with parameters showing performance across NHS regions.  
- **Mean Age, Stay & Wait Time by Ethnic Category**  
  → Multi-chart design (bar, square, area) to analyze treatment variation by ethnicity.  
- **Waiting List vs Mean Time Waited (Top 15 ICBs)**  
  → Comparison using circles and squares to highlight efficiency differences.  
- **Routine Mental Health Treatment Times (0–1 vs 4–12 Weeks)**  
  → Combined bar and line chart to compare immediate vs delayed treatments.

</details>

---

<details>
<summary><b>🏛️ Dashboard 2 – Managerial & Policy Insights</b></summary>

**Focus:** Total inpatient/outpatient numbers and hospital distribution by region.

### Key Visuals
- **Hospitals by County (Top 15)**  
  → Treemap showing healthcare facility concentration (e.g., London, Greater Manchester).  
- **Consultant Episodes (Top 15 Specialties)**  
  → Box & Whisker plot showing outpatient vs inpatient data spread.  
- **Age 50–69: Outpatient vs Inpatient Episodes**  
  → Stacked area chart revealing treatment trends by specialty.  
- **Day Case vs FCE Bed Days (Top 15 ICBs)**  
  → Line chart comparing one-day cases vs multi-day inpatients.

</details>

---

## 🧹 Data Preparation

<details>
<summary><b>⚙️ Data Cleaning and Integration Process</b></summary>

| Step | Description |
|------|--------------|
| **1. Cleaning in Excel** | Removed redundant rows, headers, and descriptions. |
| **2. Handling Missing Values** | Filtered nulls directly in Tableau. |
| **3. Normalization** | Scaled data for consistent comparisons. |
| **4. Data Blending** | Merged NHS and Kaggle datasets on shared fields like hospital ID and specialty. |
| **5. Validation** | Checked consistency, completeness, and accuracy. |

🗂 **Key Datasets:**
- NHS Digital — Official data (Hospital Outpatient Activity 2022–23)  
- Kaggle — Supplementary dataset on UK hospital distribution  

</details>

---

## 🎨 Design & Visualisation Principles

<details>
<summary><b>🎯 Core Principles</b></summary>

### **1. Clarity and Simplicity**
- No chart clutter; clean layout with white space.
- Clear, concise titles and axis labels.

### **2. Effective Use of Color**
- Consistent color schemes across all dashboards.
- Heatmaps to represent hospital density and accessibility.

### **3. Interactivity**
- Filters, parameters, and tooltips for user-driven exploration.
- Drill-down functionality for granular analysis.

### **4. Accessibility**
- High color contrast and readable font sizes.
- Designed for inclusivity (low-vision accessibility considered).

</details>

---

## 📚 Data Sources
- [NHS Digital – Hospital Outpatient Activity 2022–23](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-outpatientactivity/2022-23)  
- [Kaggle – UK Hospital Dataset](https://www.kaggle.com)  
- Verified through official records and cleaned for analytical consistency.

---

## 🎯 Target Audience
| Audience | Purpose |
|-----------|----------|
| **General Public** | Understand NHS performance and make informed treatment choices. |
| **Healthcare Managers & Policymakers** | Allocate resources efficiently and identify service bottlenecks. |

---

## 🧾 Evaluation Summary
This project highlights the power of **data-driven insights** in UK healthcare.

✅ Enables patients to make informed NHS choices  
✅ Helps policymakers allocate resources more effectively  
✅ Visualizes inefficiencies and regional disparities  
✅ Applies best practices in **data visualization** and **data quality assurance**

---

## 📖 References
- Guerrero, H. (2019). *Excel Data Analysis.* Springer.  
- Majaw, N. (2023). *Exploring Data Distributions using Box and Whisker Plot Analysis.* IEEE.  
- Milligan, J. N. (2019). *Learning Tableau 2019.*  
- Ohmann, A. (2015). *Creating Data Stories with Tableau Public.*  
- Ryan, G. (2014). *Pixel Approximate Entropy as a Measure of Line Chart Complexity.* IEEE.  
- Swapna, S. (2017). *Data Cleaning for Data Quality.* IEEE.  
- Wijk, J. V. (2013). *Cushion Treemaps: Visualisation of Hierarchical Information.* IEEE.  

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Data cleaning & preprocessing |
| **Tableau Public** | Interactive dashboard creation |
| **Kaggle / NHS Digital** | Data sourcing |
| **GitHub** | Documentation & version control |

---

## 🚀 Usage Instructions
1. Open the **[Tableau Public Dashboard](https://public.tableau.com/app/profile/sukhman.singh1298/viz/CapstoneDataVisualisation_17188433554620/Dashboard1_1?publish=yes)**.  
2. Use filters, parameters, and tooltips to explore each visualization interactively.  
3. Switch between **Dashboard 1 (public)** and **Dashboard 2 (managerial)** using the tabs.

---

## 💬 Contact

**Author:** [Sukhman Singh](https://www.linkedin.com)  
📧 **Email:** your-email@example.com  
💻 **GitHub:** [@your-github-username](https://github.com/your-github-username)  
🌐 **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com)

---

> “Data visualization is not just about seeing data — it’s about understanding stories that numbers alone can’t tell.”  
> — *Sukhman Singh, 2023*
