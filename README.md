# Optimizing Diabetes Management in US Hospitals (1999-2008)
## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)


# Overview:
This project aims to explore diabetes-related trends, outcomes, and disparities in hospital data from 1999 to 2008. Key questions include trends in admissions, factors influencing readmissions, and disparities in outcomes based on demographics. Data will be sourced from the UCI repository, specifically the "Diabetes 130-US Hospitals" dataset. Challenges include handling missing data and balancing insights with ethical considerations.


# Motivation:
Diabetes is a critical public health issue, and understanding hospital trends can help identify gaps in care and resource allocation. As a health and wellness coach, I’ve worked closely with diabetic patients and witnessed the challenges they face—especially during care transitions between hospital stays and home care. These gaps in care can have serious consequences, leading to avoidable readmissions and worsening health outcomes. This project will provide actionable insights for healthcare administrators and policymakers by leveraging data analysis to illuminate trends and disparities over a decade.


## Questions:
1) What are the characteristics of diabetes-related hospital admissions?
2) How does hospital stay vary across demographics and clinical factors?
3) What factors influence the likelihood of hospital readmissions?


## Limitations/Challenges:
➡ Missing values limited certain analyses.
➡ Variability in categorical fields made data cleaning difficult.
➡ No financial data, timestamps, or outpatient medication adherence tracking.

## Technologies Used:
1) Python / Jupyter Notebook / Pandas - for data exploration, cleaning, transformation, and aggregation of the datasets
2) Power BI - for creating interactive dashboard and presentation
4) Github - for data storage & version control
5) Excel - Data exploration


## Data Sources:
1) Research Literature:
   
  Diabetes Care 2024;47(Supplement_1):S52–S76
	https://doi.org/10.2337/dc24-S004

  Diabetes Res Clin Pract. 2022 May; 187: 109862. doi:10.1016/j.diabres.2022.109862

2) Data Source:
  https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008
  
  Beata Strack et al., “Impact of  HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol.       2014, Article ID 781670, 11 pages, 2014.

  https://www.ahd.com/reference/ICD9desc_diag_CMS2015.pdf

  https://www.cms.gov/medicare/coding-billing/icd-10-codes/icd-9-cm-diagnosis-procedure-codes-abbreviated-and-full-code-titles

3) Definitions: [Merriam-Webster](https://www.merriam-webster.com/)


## Conclusion:
1) Demographic Profile:
   ➡ Minimal variability: Mainly Caucasian women
   ➡ Age: Between 50-80
   ➡ Primary Diagnosis Group: Mainly circulatory - confirms the complexity of diabetes and the comorbidites of a diabetic patient
   ➡ Admission Type: Emergency
   
3) Number of admissions generally has a positive correlation with length of hospital stay.

4) Targeted Interventions within Care:
   ➡ Readmissions AFTER 30 days of the first discharge was found to be greater than readmissions WITHIN 30 days, especially patients with more than 6 outpatient visits one year        prior to their admission (documented within this dataset). Focus resources and efforts on outpatient care.

5) Profile of Higher-Risk Patients:
   ➡ Emergency room patients
   ➡ Frequent in-patient visits
   ➡ Higher number of outpatient visits
   ➡ Higher medication count

7) Call to Action:
  ➡ Hospital Staff → Enhance discharge planning for high-risk patients.
  ➡ Administrators → Allocate resources for diabetes education programs.
  ➡ Care Coordinators → Focus on frequent emergency room patients to prevent readmissions.
  ➡ Quality Teams → Use data-driven insights to improve diabetes prevention programs.
  ➡ Patients → Encourage consistent primary care engagement instead of emergency room reliance.
