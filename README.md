# 🎓 Indian College Admissions & Scholarship Analysis

An end-to-end data analytics project exploring student admission trends, entrance exam impacts, and scholarship eligibility across India.

## 📌 Project Overview
This project analyzes a dataset of 25,000+ student applications to identify key factors influencing university admissions. It covers the entire data lifecycle: **Cleaning (Python) -> Querying (SQL) -> Visualization (Power BI).**

## 🛠️ Tech Stack
- **Data Cleaning:** Python (Pandas, NumPy)
- **Database:** MySQL
- **Visualization:** Power BI
- **Documentation:** Markdown

## 🚀 Key Features & Workflow
1. **Professional Data Cleaning (Python):** - Handled non-unique Student IDs by creating a Composite Unique Key.
   - Performed logic-based validation (e.g., ensuring Entrance Scores are 0 for 'None' exam type).
   - **Feature Engineering:** Created `performance_tier` (Elite, High, Average) to simplify analysis.
2. **Deep-Dive SQL Analysis:**
   - Analyzed admission success rates across different streams.
   - Compared performance metrics across JEE, NEET, and CET exams.
3. **Interactive Power BI Dashboard:**
   - KPI Cards for Admission Rates and Scholarship %
   - Geographic distribution of applicants using Indian Map.
   - Slicers for real-time filtering by Category, Gender, and Performance Tier.

## 📊 Key Insights
- **Stream Competition:** Identified [Insert Stream Name] as the most competitive stream with the lowest admission rate.
- **Scholarship Trends:** Found that [Insert Category] has the highest scholarship eligibility based on merit.
- **Exam Impact:** Students appearing for [Insert Exam] had a [X]% higher probability of admission compared to others.

## 📂 Project Structure
- `/Data`: Raw and Cleaned CSV files.
- `/Python`: Jupyter Notebook for cleaning & EDA.
- `/SQL`: SQL scripts for business queries.
- `/Dashboard`: Power BI (.pbix) file.

## 📝 How to Use
1. Clone this repository.
2. Run the Python script to see the cleaning logic.
3. Import the `Cleaned_College_Admission_Final.csv` into MySQL/Power BI.
4. Open the Power BI file to explore the interactive dashboard.
