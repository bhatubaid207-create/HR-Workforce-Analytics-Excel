# HR Workforce Analytics — Attrition & Predictive Risk

### Interactive Excel HR Analytics | Workforce Intelligence | Predictive Modeling

An end-to-end HR analytics project built in **Microsoft Excel** to analyze workforce attrition, identify key employee risk factors, estimate attrition probability using **logistic regression**, and translate analytical findings into actionable retention recommendations.

The project analyzes **5,000 employee records** through an interactive executive dashboard, workforce segmentation, predictive risk modeling, and a management-focused HR report.

![HR Workforce Analytics Dashboard](images/dashboard_overview.png)

## 📊 Project Highlights

- **5,000** employee records analyzed
- **37.10%** overall attrition rate
- **1,600 employees** identified in the High-Risk segment
- **63.06%** actual attrition within the High-Risk segment
- Interactive filtering by **Department, Gender, and Age Group**
- Logistic regression attrition-risk model with **ROC-AUC of 0.716**
- Employee-level **Low, Moderate, and High** risk segmentation
- Management-focused retention recommendations and monitoring framework

## 🎯 Business Problem

Employee attrition can create significant workforce disruption through increased recruitment costs, loss of organizational knowledge, productivity gaps, and pressure on existing employees.

The objective of this project is to move beyond basic attrition reporting and answer three management-focused questions:

1. **Where is employee attrition concentrated across the workforce?**
2. **Which workforce factors are associated with higher attrition?**
3. **How can predictive analytics help HR prioritize employees or workforce segments for further retention assessment?**

The analysis therefore combines **descriptive HR analytics, interactive workforce segmentation, predictive risk modeling, and management recommendations** to support evidence-based retention decisions.

## 🔍 Analytical Objectives

- Measure overall workforce size, attrition, retention, compensation, and tenure.
- Analyze attrition across employee experience and workforce characteristics.
- Evaluate patterns associated with **job satisfaction, appraisal ratings, overtime, work-life balance, and tenure**.
- Build a logistic regression model to estimate employee attrition probability.
- Segment employees into **Low, Moderate, and High attrition-risk groups**.
- Translate analytical findings into practical HR retention priorities.
- Provide an interactive dashboard for workforce exploration by **Department, Gender, and Age Group**.

## ⚙️ Project Workflow

The project follows an end-to-end HR analytics workflow:

**Raw HR Data → Data Cleaning → Feature Engineering → Workforce Metrics → Attrition Analysis → Predictive Modeling → Risk Segmentation → Interactive Dashboard → Management Recommendations**

### 1. Data Preparation
- Preserved the original dataset in a dedicated `Raw_Data` worksheet.
- Created a structured `Clean_Data` layer for analysis.
- Standardized workforce variables and prepared analytical fields.
- Maintained all **5,000 employee records** throughout the data-preparation process.

### 2. Feature Engineering
Derived analytical variables were created to support workforce segmentation and attrition analysis, including:

`Attrition_Flag` • `Age_Group` • `Salary_Band` • `Tenure_Band` • `Role_Tenure_Band` • `Distance_Band` • `Satisfaction_Level` • `WLB_Level` • `Training_Band` • `Leave_Band`

### 3. Descriptive HR Analytics
Excel PivotTables and calculated metrics were used to evaluate:
- Workforce headcount and active employees
- Attrition and retention rates
- Compensation and tenure
- Job satisfaction
- Appraisal ratings
- Overtime
- Work-life balance
- Company and role tenure
- Training, leave, and commuting-distance patterns

### 4. Predictive Attrition Modeling
A **logistic regression model** was developed to estimate employee attrition probability using five workforce risk indicators:

- Low Job Satisfaction
- Low Appraisal Rating
- Overtime
- Poor Work-Life Balance
- Early Company Tenure

The model generates an employee-level attrition probability that is subsequently used for workforce risk segmentation.

### 5. Risk Segmentation
Employees were classified into **Low, Moderate, and High Risk** groups based on their predicted attrition probabilities. The resulting segments were validated against observed employee attrition to assess whether the model meaningfully differentiated workforce risk.

### 6. Interactive Reporting
The final Excel solution combines:
- Dynamic KPI cards
- Attrition-driver analysis
- Work-life balance analysis
- Predictive risk intelligence
- Department, Gender, and Age Group slicers
- Management-focused HR reporting and retention recommendations

## 📈 Key HR Insights

### 1. Low Job Satisfaction — Strongest Observed Attrition Signal
Employees with **Low Job Satisfaction recorded 51.48% attrition**, compared with the overall workforce attrition rate of **37.10%**.

This represents a **14.38 percentage-point increase** over the overall workforce rate, making low job satisfaction the strongest observed attrition signal in the analysis.

### 2. Low Appraisal Ratings
Employees receiving appraisal ratings of **1–2 recorded a combined attrition rate of 49.71%**.

The pattern suggests that employees experiencing lower performance outcomes may warrant further investigation around coaching, development, role alignment, and manager feedback.

### 3. Overtime
Employees working overtime recorded **43.60% attrition**, compared with **30.80%** among employees without overtime.

This indicates a meaningful association between overtime exposure and employee exits within the dataset.

### 4. Work-Life Balance
Employees reporting **Poor Work-Life Balance recorded 43.00% attrition**, compared with **29.91%** among employees reporting Good Work-Life Balance.

This highlights work-life balance as an important workforce experience factor for retention analysis.

### 5. Early Company Tenure
Employees with **1–2 years of company tenure recorded 40.23% attrition**.

Attrition subsequently declined across longer-tenure groups, indicating that the early employment period deserves particular attention in retention planning.

> **Interpretation Note:** These findings represent associations observed within the dataset and should not be interpreted as evidence that any individual factor directly causes employee attrition.
