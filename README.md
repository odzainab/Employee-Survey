# Pierce County Employee Engagement Survey Analysis

_Uncovering workforce engagement patterns, department performance, and actionable insights for Pierce County._

---

## Quick Look

- **Survey Participants:** 14,710 valid responses (99.08% completion)  
- **Overall Sentiment:** 75% positive responses (Agree / Strongly Agree)  
- **Top Strengths:** Role clarity, supervisor support, use of strengths  
- **Lowest-Rated Area:** Friendship at work / social connection  
- **Top Departments:** Family Justice Center (3.61)  
- **Tools Used:** Excel (Pivot Tables, Formulas), Power Query
- **Dataset:** [View the Dataset](https://docs.google.com/spreadsheets/d/1nbhfp2ModgqDAPveYQG9CknRw2PYJQxbOTs3xSKOB8E/edit?gid=61186505#gid=61186505)
- **Full Story & Deep Dive:** [Read Full Analysis on Medium](https://medium.com/@odzainab1/what-14-700-employees-told-us-about-workplace-engagement-insights-from-the-pierce-county-survey-e583d4a58d0f)

---

## Introduction

Pierce County’s workforce drives public services and administration daily. This voluntary Employee Engagement Survey collected **14,725 responses** to capture employees’ experiences, satisfaction, and engagement levels across departments and roles.  

The goal: **identify strengths, highlight areas for improvement, and support data-driven decisions to enhance employee experience.**

---

## Business Problem

- Identify survey questions employees agree or disagree with most  
- Detect engagement patterns by department or role  
- Provide actionable insights to improve employee satisfaction  

---

## Dataset & Tools

**Key Dataset Fields:**  
- Response ID, Status, Department  
- Role Indicators: Director, Manager, Supervisor, Staff (binary 0/1)  
- Question, Numeric Response (0–4), Response Text (Strongly Disagree → Strongly Agree)  

**Tools:**  
- Excel (Pivot Tables, Formulas, Charts)  
- Power Query (Data Cleaning & Standardization)  

---

## Data Preparation & Validation

1. **Formatting & Import:** Promoted headers, set proper data types  
2. **Standardizing Questions:** Corrected inconsistencies, mapped standard question text using XLOOKUP  
3. **Handling Missing Data:** Nulls replaced with 0 (numeric) or “Missing” (text)  
4. **Numeric Conversion:** Positive responses flagged as 1 for aggregation  
5. **Duplicate Removal:** Ensured unique Response ID (14,710 rows)  
6. **Pivot Tables:** Calculated averages by question, department, and role  
7. **Data Validation:** Confirmed consistency and correctness  

---
## Data Visulaization
<img width="1230" height="678" alt="Employee Screenshot" src="https://github.com/user-attachments/assets/5ad33378-59fd-4c8c-a256-b1e575c128b6" />

## Key Insights

- **High Participation:** 99.08% completion suggests strong engagement  
- **Positive Sentiment:** 75% of responses indicate favorable employee experiences  
- **Strengths:** Role clarity, supervisor support, effective use of strengths  
- **Opportunities:** Workplace social connection, departmental variability  
- **Department Highlights:** Family Justice Center, Emergency Management, Executive Office & Directors lead, Communications and HR lower  

---

## Recommendations

1. **Improve Workplace Social Connection** – cross-team initiatives, informal engagement forums  
2. **Use Targeted Department-Level Actions** – tailored interventions for lower-performing departments  
3. **Sustain Leadership Practices** – continue supervisor support and communication initiatives  
4. **Maintain Role Clarity** – clear expectations, ongoing feedback, performance communication  
5. **Track Progress** – follow-up surveys and pulse checks to monitor improvements  

---

## Next Steps

- Prioritize action areas: social connection and low-scoring departments  
- Translate insights into department-specific improvement plans  
- Leverage high-performing departments as best practice examples  
- Monitor engagement trends over time with follow-up measurements  

---

## Conclusion

Overall, Pierce County employees are **largely satisfied and engaged**, particularly regarding leadership support and role clarity. Differences across departments and weaker social connection highlight opportunities for targeted action. Applying these insights will strengthen engagement, consistency, and workplace satisfaction.


