Apollo Hospitals: Patient Workflow Dashboard

Problem Statement : The objective was to create a comprehensive dashboard that provided insights into various aspects of patient workflow at Apollo Hospitals. 

The key metrics displayed were:

1.Patient Info according to Patient_ID 

2.Billing Information

3.Bed Occupancy Breakdown

4.Overall Feedback for Doctor

5.Diagnosis-wise Stats

6.Billing vs. Insurance Stats

Overview:

This dashboard addressed the problem statement by visualizing crucial patient workflow metrics. It enabled hospital administrators to monitor patient information, billing details, bed occupancy, doctor feedback, diagnosis statistics, and financial comparisons between billing and insurance.

Steps to Recreate the Dashboard

Step 1: Data Preparation

Data Sources: The required data tables were gathered from raw data in excel sheet provided by apollo hospital, including:

1.Patient information with unique Patient_ID.

2.Billing details.

3.Bed occupancy records.

4.Patient feedback for doctors.

5.Diagnosis and treatment details.

6.Insurance information.

Data Cleaning: Power Query was used to:


Handle missing data.

Remove duplicates.

Standardize the data across all tables.



Step 2: Dashboard Design in Power BI

Patient Info according to 

Patient_ID: Card visuals were created to display key patient information such as admit date, discharge date, follow-up date, and total bill amount.
A slicer was used to filter data by Patient_ID.

Billing Information:  Bar and line charts were created to visualize billing details, including comparisons with insurance amounts.

Bed Occupancy Breakdown:  A bar chart was created to show the distribution of bed occupancy across different categories (e.g., Private, General, ICU).

Overall Feedback for Doctor:A donut chart was used to display the volume of feedback received by each doctor.

Diagnosis-wise Stats:  A stacked bar chart was created to display the patient count for each diagnosis category.

Billing vs. Insurance Stats: A line chart was plotted to compare billing amounts with corresponding insurance amounts for various diagnoses.



Step 3: Formatting & Customization

Themes: A consistent color theme was applied throughout the dashboard to align with Apollo Hospitals’ branding.

Interactivity: Cross-filtering was enabled to allow users to click on any visual and see the related data across the entire dashboard.

Date Range: A date range slicer was added to filter the dashboard by specific admission or discharge dates.


Step 4: Final Touches

Tooltips: Tooltips were customized to provide additional insights when hovering over visual elements.

Exporting: The dashboard was saved as a .pbix file for future editing and as a .pdf for easy sharing with stakeholders.


How to Use the Dashboard

Filtering by Patient: The Patient_ID slicer was used to filter data related to specific patients.

Viewing Feedback: The donut chart in the center showed the feedback volume for each doctor, allowing easy comparison.

Analyzing Trends: The billing vs. insurance line chart was used to track financial trends across different diagnoses.


Conclusion

This dashboard was a powerful tool for hospital administrators, providing valuable insights into patient management, financials, and operational efficiency. With Power BI's interactive capabilities, users were able to easily explore the data and derive actionable insights.

