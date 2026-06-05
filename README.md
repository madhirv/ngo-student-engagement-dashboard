# NGO Student Engagement & Risk Analytics Dashboard

Interactive NGO student engagement and risk analytics project using Python, Google Colab, and Looker Studio.

## Interactive Dashboard

[Open Looker Studio Dashboard](https://datastudio.google.com/embed/u/0/reporting/2a7b3eb3-4d48-4e47-a619-fc1b0a3a5c7c/page/y6R0F)

## Project Overview

This project analyzes 500 student records across Bengaluru NGO education programs to evaluate attendance patterns, score improvement, program effectiveness, and student risk segmentation.

The objective is to identify high-risk student groups, compare program outcomes, and support data-driven intervention and resource allocation strategies.

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- Looker Studio
- CSV/Excel

## Dataset

The project uses a cleaned student-level master dataset containing demographic, attendance, academic performance, program participation, and risk-related fields.

Key files included:

- `ngo_student_master_2021_2022.csv`
- `data_dictionary.csv`
- `project_build_summary.csv`
- `NGO_Education_Analytics_Bengaluru_2021_2022.ipynb`

## Dashboard Pages

1. **Executive Overview**  
   Provides KPI monitoring, risk category distribution, and regional high-risk student concentration.

2. **Program Performance**  
   Compares attendance rate, score improvement, and program-level effectiveness.

3. **Risk Analysis**  
   Identifies high-priority student groups and regions requiring intervention.

4. **Insights & Recommendations**  
   Summarizes key findings and data-driven recommendations for resource allocation.

## Key Metrics

- Total students
- Average attendance rate
- High-risk students
- Average score improvement
- Risk category distribution
- Program-level attendance
- Program-level score improvement
- Regional high-risk student concentration

## Key Insights

- 102 students were identified as high-risk out of 500 total students.
- Most students were categorized as medium risk, indicating opportunities for early intervention.
- Yelahanka, KR Puram, and Hebbal showed higher concentrations of high-risk students.
- After-School Tutoring showed the highest average score improvement among the analyzed program types.
- Attendance and score improvement showed a positive relationship at the program level.

## Recommendations

- Prioritize high-risk students for targeted mentor follow-ups and academic support.
- Allocate additional volunteers and tutoring resources to regions with higher risk concentration.
- Expand or strengthen programs with higher attendance and score improvement outcomes.
- Use weekly attendance monitoring as an early warning indicator for student disengagement.
- Maintain standardized student-level tracking across attendance, performance, and intervention records.

## Project Outcome

The final output is an interactive Looker Studio dashboard supported by a Google Colab analysis notebook. The dashboard allows stakeholders to monitor student engagement, identify high-risk groups, evaluate program performance, and support evidence-based decision-making.
