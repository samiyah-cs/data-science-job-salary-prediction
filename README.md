# Global Data Science Salary Trends Analysis

An end-to-end data analysis project designed to explore and uncover global data science salary trends. This project cleans raw market data, uncovers key economic patterns, visualizes critical workforce insights, and presents data-driven conclusions suitable for professional portfolio demonstrations and academic review.

##  Project Objective
The primary goal of this repository is to analyze how various professional factors impact compensation within the data science industry. By exploring individual features, this project aims to answer:
- What are the core driving factors behind salary variations globally?
- How do experience levels, company sizes, and remote work ratios dictate compensation?
- Can we build a well-documented analytical pipeline to help professionals understand market dynamics?

##  Dataset & Features
The project utilizes the comprehensive `ds_salaries.csv` dataset, which captures global employment metrics including:
- **Experience Level:** Entry-level (EN), Mid-level (MI), Senior-level (SE), and Executive-level (EX).
- **Employment Type:** Full-time, Part-time, Contract, and Freelance work.
- **Job Titles:** Data Scientist, Data Analyst, Machine Learning Engineer, etc.
- **Salary in USD:** Standardized compensation values for accurate international comparisons.
- **Remote Ratio:** The proportion of work performed remotely (0%, 50%, or 100%).
- **Company Size:** Small (S), Medium (M), and Large (L) scale corporate environments.

##  Exploratory Data Analysis Results

### 1. Salary Distribution Analysis (Histogram)
The histogram highlights the frequency distribution and density of data science compensation globally.
![Salary Distribution](images/salary_distribution.png)
*Insight:* The visualization reveals a right-skewed distribution, demonstrating that while the majority of data science roles cluster around the $100,000 mark, a thin tail of highly compensated specialist roles extends toward the upper bounds of $500,000.

### 2. Salary Range & Outlier Detection (Boxplot)
This boxplot highlights the overall spread of salary estimates and identifies significant industry outliers stretching across parameters.
![Salary Boxplot](images/salary_boxplot.png)
*Insight:* The central box indicates where the majority of data science salaries lie, with a clear median line (red). Notably, the analysis exposes several statistical outliers stretching beyond $300,000 up to nearly $600,000, representing executive or highly specialized positions in the global market.

### 3. Feature Correlation Mapping (Heatmap)
This correlation matrix layout provides crucial insights into quantitative feature relationships.
![Correlation Heatmap](images/correlation_heatmap.png)
*Insight:* A very strong positive correlation (dark red) is clearly visible between `Salary Estimate`, `Min_Salary`, and `Max_Salary`. This relationship is expected, as the estimate is directly derived from the reported salary bounds. This visualization ensures the data structure aligns with professional logic before deeper analysis.

## 🛠️ Tools & Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Visual Studio Code
- **Deployment & Viewing:** Interactive HTML Web Layout Export

##  Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Outlier Detection & Statistical Interpretation
- Data Visualization
- Business Insight Generation
- Technical Documentation

##  Key Insights & Results
- **Experience Matters:** A substantial and consistent salary jump is observed between Mid-level (MI) and Senior-level (SE) roles, highlighting the high market value of independent technical ownership.
- **Corporate Scale Influence:** Medium and Large companies offer statistically higher baseline compensation, but small companies often compensate with higher remote flexibility.
- **The Remote Work Era:** 100% remote positions have shown competitive, and in some regions superior, salary standards compared to strictly on-site arrangements.

##  Repository Structure
- `data-science-job-salary-prediction-glassdoor.ipynb` : The core analytical Jupyter Notebook with documented python code and markdown explanation blocks.
- `data-science-job-salary-prediction-glassdoor-html.html` : The generated interactive web-app version for presentation and rapid review.
- `ds_salaries.csv` : The structured raw dataset supporting all visualizations and computations.

##  How to Run
1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells to reproduce the analysis and visualizations.
