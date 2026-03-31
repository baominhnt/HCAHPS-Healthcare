# HCAHPS-Healthcare
🏥 HCAHPS Patient Experience Analysis
Improving healthcare quality through data‑driven insights

📌 Overview
This project analyzes Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey data to evaluate patient experience across U.S. hospitals. The goal is to identify performance patterns, uncover drivers of patient satisfaction, and provide actionable insights for healthcare quality improvement.

The analysis includes:
- Data cleaning and standardization
- Exploratory data analysis (EDA)
- Visualization of patient experience metrics
- Comparative performance across states and hospital types
- Insight‑driven recommendations for quality improvement

🎯 Objectives
- Understand national trends in patient satisfaction
- Identify top‑ and bottom‑performing hospitals
- Explore relationships between hospital characteristics and HCAHPS scores
- Provide clear, stakeholder‑ready insights for healthcare administrators and policymakers

📂 Project Structure
HCAHPS-Analysis/
│
├── data/
│   ├── raw/                # Original HCAHPS datasets
│   └── processed/          # Cleaned and standardized datasets
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_visualizations.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── eda_utils.py
│   └── visualization.py
│
├── outputs/
│   ├── figures/            # Exported charts and plots
│   └── tables/             # Summary tables and metrics
│
├── dashboard/              # Optional dashboard (Power BI / R Markdown)
│
└── README.md



🧹 Data Sources & Preparation
The project uses publicly available HCAHPS survey data from CMS. Key steps include:
- Handling missing values and inconsistent formatting
- Normalizing hospital identifiers
- Converting survey responses into standardized performance metrics
- Merging hospital characteristics (ownership, size, location)

📊 Key Analyses
1. National Performance Overview
- Distribution of HCAHPS summary star ratings
- Trends in communication, responsiveness, and care transitions
2. State‑Level Comparisons
- Ranking states by overall patient satisfaction
- Geographic variation in care quality
3. Hospital Characteristics & Outcomes
- Performance differences by ownership (nonprofit, for‑profit, government)
- Relationship between hospital size and patient experience
- Urban vs. rural performance patterns
4. Drivers of Patient Satisfaction
- Correlation analysis
= Feature importance (if modeling is included)

📈 Visualizations
The project includes clear, publication‑ready charts such as:
- Heatmaps of state‑level performance
- Boxplots comparing hospital types
- Trend lines for national HCAHPS metrics
- Interactive dashboards (optional)

🧠 Insights & Recommendations
Key takeaways typically include:
- Communication and responsiveness are strong predictors of overall satisfaction
- Smaller hospitals often outperform larger systems in patient experience
- Geographic disparities highlight opportunities for targeted interventions
- Consistent underperformance in care transitions suggests systemic gaps

🛠️ Tools & Technologies
- SQL — Unified relational tables, resolved missingness, and generated segmented summaries across communication, responsiveness, and discharge‑planning domains.
- Python — Conducted statistical and visual analyses to identify correlation patterns, benchmark hospital performance against national standards, and surface key drivers of patient satisfaction.

- pandas, numpy, seaborn, matplotlib, plotly — Enabled efficient data manipulation, exploratory analysis, and publication‑ready visualizations.
- Spark Jupyter Notebooks — Structured the analytical workflow into clear, reproducible steps.
- Git & GitHub — Ensured version control, transparency, and reproducibility across the project lifecycle.

🚀 How to Reproduce
1. Clone the repository
2. Install dependencies
3. Place raw HCAHPS data in data/raw/
4.Run preprocessing scripts
5. Execute notebooks in order

📬 Contact

For questions, collaboration, or feedback: 
James Nguyen  
Data Analyst & Dashboard Designer
(Linkedin: https://www.linkedin.com/in/tran-bao-minh-nguyen-296b01333/  
For more projects finding:https://baominhnt.github.io/tbmnguyen.com/index.html)

