# Mental Health in Technology Companies

An end-to-end data analytics project exploring workplace mental health in the technology industry using Python. This project applies exploratory data analysis (EDA) and statistical analysis to evaluate workplace mental health support and identify factors associated with professional mental health treatment and work interference.

---

# Table of Contents

- [Project Overview](#project-overview)
- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Exploratory Data Analysis](#-xploratory-data-analysis)
- [Statistical Analysis](#statistical-analysis)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Repository Structure](#repository-structure)
- [Skills Demonstrated](#skills-demonstrated)
---

# Project Overview 

Mental health has become an increasingly important issue in the technology industry, where demanding workloads, high-pressure environments, and rapid innovation can significantly affect employee well-being and productivity.

To build healthier workplaces, organizations need to understand how well they support employee mental health and which workplace factors are associated with treatment-seeking behavior and work disruption.

This project analyzes the **Mental Health in Tech Survey** dataset using Python to evaluate workplace mental health support, identify significant factors associated with mental health outcomes, and generate business recommendations that can support HR decision-making.

---

# Business Questions

This project addresses the following business questions:

### Business Question 1

**How supportive are technology workplaces in promoting employee mental health?**

This analysis evaluates organizational support through:

- Mental health benefits
- Care options
- Wellness programs
- Mental health resources
- Workplace culture

---

### Business Question 2

**Which factors are most strongly associated with employees seeking professional mental health treatment?**

Statistical analysis is performed to identify workplace and personal factors associated with employees seeking professional treatment.

---

### Business Question 3

**Which factors are most strongly associated with work interference caused by mental health conditions?**

The analysis identifies variables associated with reduced work performance due to mental health conditions.

---

### Business Question 4

**Which employee segments should HR prioritize for mental health interventions?**

Employee segmentation is conducted using:

- Age
- Gender
- Company Size
- Remote Work
- Family History

---

### Business Question 5

**Based on the findings, which organizational initiatives should HR prioritize?**

Analytical findings are translated into practical recommendations that organizations can implement to improve workplace mental health.

---

# Dataset

**Dataset:** Mental Health in Tech Survey

**Source:** Open Sourcing Mental Illness (OSMI)

The dataset contains employee survey responses regarding workplace mental health support, organizational culture, mental health experiences, and access to professional treatment.

## Dataset Categories

| Category | Variables |
|-----------|-----------|
| Demographics | Age, Gender, Country |
| Employment | Company Size, Remote Work, Self-employed |
| Mental Health History | Family History, Treatment, Work Interference |
| Workplace Support | Benefits, Care Options, Wellness Program, Seek Help |
| Workplace Culture | Leave, Supervisor, Coworkers, Anonymity, Mental vs Physical |
| Workplace Consequences | Mental Health Consequence, Observed Consequence |

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      ├── Handle Missing Values
      ├── Standardize Gender
      ├── Clean Country Values
      ├── Remove Age Outliers
      └── Filter Technology Companies
      │
      ▼
Exploratory Data Analysis
      ├── Respondent Profile
      ├── Workplace Support
      ├── Workplace Culture
      ├── Mental Health Outcomes
      └── Employee Segmentation
      │
      ▼
Statistical Analysis
      ├── Chi-Square Test
      └── Cramér's V
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
```

---

# Exploratory Data Analysis

The exploratory analysis is organized according to the business questions.

## Respondent Profile

The respondent profile provides an overview of the survey population through:

- Age Distribution
- Gender Distribution
- Company Size
- Remote Work Status
- Family History

---

## Workplace Mental Health Support

To evaluate organizational support, the following indicators are analyzed:

- Mental Health Benefits
- Care Options
- Wellness Programs
- Mental Health Resources
- Mental Health vs Physical Health

---

## Workplace Culture

The workplace culture analysis includes:

- Medical Leave
- Supervisor Support
- Coworker Support
- Workplace Anonymity
- Mental Health Consequences
- Observed Workplace Consequences

---

## Mental Health Outcomes

The project also examines:

- Professional Treatment Distribution
- Work Interference Distribution

---

# 📈 Statistical Analysis

To identify variables associated with employee mental health outcomes, statistical association analysis is conducted using:

- **Chi-Square Test of Independence**
- **Cramér's V**

Two target variables are analyzed:

### Target Variable 1

Professional Mental Health Treatment

### Target Variable 2

Work Interference Due to Mental Health Conditions

Variables with the strongest associations are further explored through comparative visualizations.

---

# Key Findings

## Business Question 1

Technology companies provide varying levels of mental health support.

The analysis indicates differences in:

- Availability of mental health benefits
- Access to care options
- Wellness program implementation
- Workplace support culture

---

## Business Question 2

The strongest factors associated with seeking professional treatment are:

1. Family History
2. Care Options
3. Benefits

These findings suggest that both personal history and organizational support influence treatment-seeking behavior.

---

## Business Question 3

The strongest factors associated with work interference are:

1. Treatment
2. Family History
3. Benefits

Employees experiencing more severe mental health conditions are more likely to report work disruption.

---

## Business Question 4

Several employee segments exhibit different mental health patterns, particularly across:

- Age groups
- Company sizes
- Remote work status
- Family history

These findings can help organizations identify priority groups for targeted interventions.

---

## Business Question 5

The analysis suggests several organizational priorities:

- Improve access to mental health care options
- Expand employee wellness programs
- Increase awareness of available support resources
- Encourage supportive management practices
- Foster a psychologically safe workplace

---

# 💼 Business Recommendations

Based on the analysis, organizations should consider:

- Expanding mental health benefits beyond basic healthcare coverage.
- Increasing employee awareness of available care options and support services.
- Investing in preventive wellness programs rather than relying solely on treatment.
- Training managers to support conversations around mental health.
- Creating workplace policies that reduce stigma and encourage early intervention.

---

# 📁 Repository Structure

```text
mental-health-tech-analysis/
│
├── data/
│   └── survey.csv
│   └── df_tech.csv
│
├── notebook/
│   └── Mental_Health_in_Tech_EDA.ipynb
│
└── README.md
```

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Statistical Analysis
- Chi-Square Test
- Cramér's V Analysis
- Data Visualization
- Business Analytics
- HR Analytics
- Data Storytelling
- Business Recommendation Development
