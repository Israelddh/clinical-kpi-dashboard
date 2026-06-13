# Clinical Data Quality & EDC Query Management Dashboard

## Overview

This project simulates a Clinical Data Management (CDM) workflow using a simplified Electronic Data Capture (EDC) dataset.

The goal is to explore how clinical data issues are identified, reviewed, and managed during data cleaning activities. The project focuses on data quality checks, discrepancy tracking, and subject-level review, similar to processes used in clinical research and healthcare data environments.

The workflow is designed around a common clinical data review process:

**Dataset overview → Data quality assessment → Query review → Subject-level investigation**

---

## Project Objectives

The main objectives of this project are:

- Assess clinical dataset completeness and consistency
- Identify missing, inconsistent, or implausible values
- Simulate an EDC query lifecycle (Open → Answered → Closed)
- Explore subject-level clinical information
- Create dashboards that support data review and quality monitoring

---

## Dataset

The project uses two simulated clinical datasets.

### EDC Query Dataset

Represents queries generated during clinical data review.

Includes:

- Field-level discrepancies
- Query status
- Data manager and site responses
- Query timestamps
- Resolution workflow

Example query statuses:

- Open
- Answered
- Closed

---

### Subject-Level Clinical Dataset

Contains structured clinical information including:

- Demographics
- Vital signs
- Derived measurements (such as BMI)
- Subject-level clinical variables

The dataset is used to evaluate completeness and identify potential data quality issues.

---

# Dashboards

## EDC Data Overview

![EDC Data Overview](images/EDC%20Data%20Overview.png)

Provides an initial overview of the dataset before quality review.

Key elements:

- Available clinical variables
- Dataset completeness
- Distribution of collected information
- General data structure

This view represents the first step in understanding the data before performing validation checks.

---

## Discrepancies Dashboard

![Discrepancies](images/Discrepancies.png)

Focuses on data quality monitoring.

The dashboard highlights:

- Missing values
- Implausible measurements
- Cross-field inconsistencies
- Query status distribution

Examples include validation checks such as comparing BMI values against height and weight information.

---

## Subject Drilldown Dashboard

![Subject Drilldown](images/Subject%20Drilldown.png)

Allows detailed review of individual subjects.

Includes:

- Subject demographics
- Vital signs
- Available clinical fields
- Related discrepancies and queries

This view represents the type of investigation performed when reviewing specific records.

---

## Data Quality Approach

The project considers common issues found in clinical datasets:

- Missing data
- Out-of-range values
- Logical inconsistencies between variables
- Duplicate records
- Unresolved or delayed queries

The focus is not only on visualisation, but on improving confidence in the data before analysis.

---

## Analytical Workflow

The workflow followed in this project:

1. Load and inspect clinical datasets
2. Review structure and completeness
3. Identify data quality issues
4. Analyse discrepancies and query status
5. Explore subject-level records
6. Present findings through interactive dashboards

---

## Tools

- Python (pandas)
- Power BI
- DAX
- Git / GitHub

---

## Clinical Data Perspective

Clinical datasets require more than basic analysis.

Before results can be interpreted, data needs to be:

- Complete
- Consistent
- Traceable
- Validated

This project focuses on the data review layer that supports reliable clinical and healthcare analytics.

---

## Limitations

This project uses simulated datasets and focuses on demonstrating analytical workflows.

It does not represent a validated clinical trial database or regulatory-compliant EDC system.

---

## Possible Extensions

Future improvements could include:

- Automated validation rules
- Query turnaround time analysis
- Site-level data quality metrics
- Subject risk scoring
- Trend analysis of data quality issues

---

## Relevance

This project is relevant to:

- Clinical Data Analyst roles
- Clinical Data Management (CDM)
- Real-World Data (RWD) analytics
- Healthcare analytics
- Pharmaceutical and CRO environments

---

## Contact

Email: israelddh@hotmail.com

LinkedIn: https://www.linkedin.com/in/israel-duarte/

ORCID: https://orcid.org/0000-0001-5427-6019