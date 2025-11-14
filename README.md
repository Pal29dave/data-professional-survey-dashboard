### Data Professional Survey Dashboard (2022) - Power BI Project

### 1. 🚀 Project Overview

This project showcases an end-to-end data analysis workflow, from raw data ingestion and transformation (ETL) to the creation of an interactive Business Intelligence (BI) dashboard using **Power BI**. The goal was to analyze and visualize the **2022 Data Professional Survey Dataset** to uncover key trends in salaries, work-life balance, and technical preferences across different global regions.

### 2. 🔑 Key Insights & Data Storytelling

The analysis of ~630 survey responses revealed critical insights into the global data career landscape:

| Insight Category | Key Finding | Analytical Context & Storytelling |
| :--- | :--- | :--- |
| **Salary Disparity** | US Data Scientists averaged **$140k**; Data Analysts averaged **$80k**. | Established a baseline for high-income roles. |
| **Global Compensation** | Indian Data Scientists averaged **$68k** (USD). | Demonstrated the need for **contextual analysis**. The lower nominal salary reflects a lower cost of living, not necessarily reduced purchasing power, highlighting a key difference in global data interpretation. |
| **Work-Life Balance (WLB)** | Global average WLB satisfaction was strong at **6.4/10**. **Canadians** reported the highest satisfaction. | Identified regional happiness trends and established a critical metric for employee satisfaction. |
| **Compensation Satisfaction** | Only **4.13/10** on average were happy with their salary. | Revealed a significant global opportunity for companies to better align compensation with professional expectations. |

### 3. ⚙️ Technical Stack

* **Business Intelligence & Visualization:** **Power BI** (Dashboarding, Custom Visuals)
* **Data Transformation:** **Power Query** (ETL, Data Cleaning, Standardization)
* **Data Source:** Real Data Professional Survey Dataset (2022)
* **Concepts:** Data Cleaning, Data Modeling, DAX (implied for custom measures), Data Storytelling.

### 4. 📐 Design Approach & Methodology

#### A. Data Transformation & Cleaning

The raw data required significant cleaning to ensure visualization accuracy:

1.  **Duplicate Removal:** Removed duplicate survey IDs to ensure a count of **630 unique respondents**.
2.  **Job Title Standardization:** Transformed and grouped similar job titles (e.g., "Data Scientist (Jr)" and "Data Scientist") into standardized categories for effective analysis.
3.  **Handling Nulls/Outliers:** Addressed missing or obviously erroneous data entries, particularly in the salary field.

#### B. Visualization Choices

* **Cards:** Used prominently at the top for critical KPIs: **Unique ID Count** (~630) and **Average Age** (~30).
* **Stacked Bar Chart:** Used to effectively compare **Transformed Job Title** against **Average Salary** across different countries, clearly showing distribution and hierarchy.
* **Clustered Column Chart:** Utilized to visualize the frequency of **Favorite Programming Languages**, making it easy to see top preferences (e.g., Python vs. R).


### 6. 📝 Installation and Usage

1.  **Clone the Repository:** Download the project files.
2.  **Open Power BI:** Download and open the .pbix file within the repository using Power BI Desktop.
3.  **Explore the Data:** Interact with the slicers and filters to explore metrics by country, job title, and programming language.

### 7. 🔗 Connect with Me

* **LinkedIn:** https://www.linkedin.com/in/palakintech/
* **Email:** palak18dave@gmail.com


