# Student-Result-Visualization
This project is part of the online internship offered by GUVI - HCL. The goal is to analyze student academic performance data and create an interactive dashboard to visualize key insights like average scores, pass percentages, grade distribution, and overall trends.

# Project Structure
student-result-visualization/
│
├── student_performance_dataset.csv # Raw dataset
├── cleaned_final_student_data.csv # Cleaned dataset
├── student_performance_analysis.ipynb # Python (Colab) preprocessing code
├── student_result_dashboard.twbx # Tableau dashboard (packaged workbook)
├── requirements.txt # Python library dependencies
└── README.md # Project description

## Key Features of the Dashboard
- **Subject-wise average score** comparison
- **Term-wise score progression** for selected students
- **Pass percentage** and student count
- **Grade distribution across terms**
- **Histograms** for pass/fail distribution in Term 1, Term 2, and Overall
- **Heatmap** for correlation between subjects

## Tools & Technologies
- **Python** (Pandas, NumPy, etc.) for data cleaning
- **Google Colab** for preprocessing
- **Tableau** for interactive dashboard visualization
- **GitHub** for version control

## Data Preprocessing Steps
1. Cleaned missing and inconsistent values
2. Standardized grades and marks
3. Added calculated columns (like `PassFlag`, `Average`, `Term-wise Total`)
4. Exported cleaned data for visualization

## Sample Insights
- Overall student performance trends
- Subjects with highest and lowest average scores
- Comparison between Term 1 and Term 2 results
- Percentage of students passing per subject

## How to Use
1. Open `student_performance_analysis.ipynb` in Google Colab to view data preprocessing.
2. Open `student_result_dashboard.twbx` in Tableau Desktop/Public to interact with the dashboard.


Feel free to star the repo if you find it useful or want to reuse the dashboard template.


