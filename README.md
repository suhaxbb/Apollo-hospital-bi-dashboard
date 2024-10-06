# 🏥 Apollo Hospitals: Patient Workflow Dashboard

## 📋 Problem Statement

The objective of this project was to design a **comprehensive Power BI dashboard** to provide insights into the **patient workflow** at Apollo Hospitals. The dashboard allows hospital administrators to easily monitor:

- Patient details
- Billing information
- Bed occupancy
- Doctor feedback
- Diagnosis statistics
- Financial comparisons between billing and insurance amounts

## 📊 Key Metrics

This dashboard focuses on the following critical metrics:

1. **Patient Info by Patient_ID**
2. **Billing Information**
3. **Bed Occupancy Breakdown**
4. **Overall Feedback for Doctors**
5. **Diagnosis-wise Statistics**
6. **Billing vs. Insurance Comparisons**

## 🛠️ Project Overview

This dashboard solves the challenge of fragmented patient workflow data by bringing all crucial insights into one place. It helps administrators to:

- Track **patient information** efficiently.
- Compare **billing details** with insurance amounts.
- Monitor **bed occupancy rates** across categories like Private, General, and ICU.
- Assess **feedback** for doctors based on volume.
- Review **diagnosis trends** based on patient data.

## 🔄 Steps to Recreate the Dashboard

### Step 1: Data Preparation

**Data Sources:**
The data was sourced from Apollo Hospitals and included the following tables:

- **Patient information** with a unique `Patient_ID`
- **Billing details**
- **Bed occupancy records**
- **Doctor feedback**
- **Diagnosis and treatment details**
- **Insurance information**

**Data Cleaning:**
The data was cleaned using **Power Query**, where the following steps were performed:

- Handled missing values
- Removed duplicate entries
- Standardized data formats across all tables

### Step 2: Dashboard Design in Power BI

- **Patient Info by Patient_ID**: Used **Card visuals** to display key patient info (e.g., admit date, discharge date, follow-up date, and total bill amount). Added a **slicer** for filtering data by `Patient_ID`.
  
- **Billing Information**: Utilized **bar and line charts** to show billing details and compared them with insurance amounts.
  
- **Bed Occupancy Breakdown**: Designed a **bar chart** to display bed occupancy distribution across different categories (Private, General, ICU).

- **Overall Feedback for Doctors**: Used a **donut chart** to show the feedback volume for each doctor, allowing easy comparison.

- **Diagnosis-wise Statistics**: Created a **stacked bar chart** to show patient counts per diagnosis category.

- **Billing vs. Insurance Comparisons**: Plotted a **line chart** to compare billing amounts with corresponding insurance amounts for various diagnoses.

### Step 3: Formatting & Customization

- **Themes**: Applied a consistent color theme in line with Apollo Hospitals’ branding.
  
- **Interactivity**: Enabled **cross-filtering** to allow dynamic interactions across visuals.

- **Date Range Slicer**: Added a **date range slicer** for filtering by admission or discharge dates.

### Step 4: Final Touches

- **Tooltips**: Customized tooltips to provide additional insights on hover.
  
- **Exporting**: Saved the dashboard as a `.pbix` file for editing and as a `.pdf` for easy sharing with stakeholders.

## 📝 How to Use the Dashboard

- **Filtering by Patient**: Use the `Patient_ID` slicer to filter data related to a specific patient.
  
- **Viewing Doctor Feedback**: The **donut chart** allows you to quickly compare feedback volume for each doctor.

- **Analyzing Financial Trends**: The **billing vs. insurance line chart** lets you track financial trends across different diagnoses.



