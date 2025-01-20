# Healthcare Insights Dashboard using Power BI

## Executive Summary
This project utilizes Power BI to analyze inpatient discharge data from healthcare facilities, focusing on procedures like total hip replacements. The dashboard highlights key metrics such as treatment costs, length of stay and hospital profiles. These insights can guide healthcare administrators in optimizing operational efficiency and improving patient outcomes.

## Tools and Skills
Power BI: Developed dynamic visualizations and an interactive dashboard.

Data Analysis: Performed in-depth analysis of hospital and patient data to derive meaningful insights.

Statistical Analysis: Applied statistical methods to uncover trends and correlations in the data.

Healthcare Domain Expertise: Interpreted analytical results with a strong understanding of healthcare operations and patient care.

## Datasets
This project leverages hospital inpatient discharge data provided by the New York State Department of Health. The dataset contains 30 columns, as described below:

1. Facility Information

health_service_area: Description of the health service area where the hospital is located.

hospital_county: County where the hospital is located.

operating_certificate_number: Facility Operating Certificate Number assigned by NYSDOH.

facility_id: Permanent Facility Identifier (PFI).

facility_name: Name of the facility where services were performed.


2. Patient Demographics

age_group: Patient's age grouped into categories (e.g., 0 to 17, 18 to 29, etc.).

zip_code_3_digits: First three digits of the patient’s ZIP code.

gender: Patient gender (Male, Female, or Unknown).

race: Patient’s racial category (e.g., White, Black/African American, etc.).

ethnicity: Patient ethnicity (e.g., Hispanic, Non-Hispanic, etc.).


3. Hospital Stay Details

length_of_stay: Total number of days the patient stayed in the hospital.

type_of_admission: Manner of admission (e.g., Elective, Emergency, etc.).

patient_disposition: Patient’s status upon discharge.

discharge_year: Year of discharge.


4. Diagnosis and Procedure Details

ccs_diagnosis_code: AHRQ Clinical Classification Software Diagnosis Code.

ccs_diagnosis_description: Description of the diagnosis code.

ccs_procedure_code: AHRQ Clinical Classification Software Procedure Code.

ccs_procedure_description: Description of the procedure code.


5. APR (All Patient Refined) Classification

apr_drg_code: All Patient Refined Diagnosis Related Group (APR-DRG) code.

apr_drg_description: Description of the APR-DRG code.

apr_mdc_code: All Patient Refined Major Diagnostic Category code.

apr_mdc_description: Description of the APR Major Diagnostic Category.

apr_severity_of_illness_code: Severity of illness code (1 = Minor, 2 = Moderate, etc.).

apr_severity_of_illness_description: Description of severity (e.g., Minor, Major).

apr_risk_of_mortality: Risk of mortality classification (e.g., Minor, Major).

apr_medical_surgical_description: Classification (Medical or Surgical).


6. Provider Information

attending_provider_license_number: License number of the attending healthcare provider.

operating_provider_license_number: License number of the provider who performed the procedure.


7. Financial Information

total_charges: Total charges billed for the patient’s hospital stay.

total_costs: Total estimated costs incurred by the hospital.


## Business Question

"How can the hospital optimize treatment costs and length of stay while maintaining or improving hip-replacement's patient recovery outcomes?"

## Key Insights

1. Length of Stay (LOS) Analysis
Average LOS: The overall average length of stay across all hospitals is 2.65 days.

Top 3 Hospitals with Highest Average LOS:

Kings County Hospital

Interfaith Medical Center

Memorial Hospital for Cancer and Allied Diseases


Bottom 3 Hospitals with Lowest Average LOS:

Northern Dutchess Hospital

St. Elizabeth Medical Center

Alice Hyde Medical Center

Key Drivers of Increased LOS:

Extreme Severity of Illness: Leads to the largest increase in LOS (impact score: 8.96).

Extreme Risk of Mortality: Second-highest contributor to increased LOS (impact score: 6.09).

New York City Health Service Area: Associated with a smaller but noticeable increase in LOS (impact score: 1.68).

2. Cost Analysis

Average Cost per Discharge: The average cost is $21,000, with a minimum total cost of $64.45K and a maximum of $688K.

Top 3 Hospitals with Highest Average Cost per Discharge:

NYU Lutheran Medical Center

Olean General Hospital

Memorial Hospital for Cancer and Allied Diseases

Bottom 3 Hospitals with Lowest Average Cost per Discharge:

United Memorial Medical Center

St. Mary’s Healthcare

Newark-Wayne Community Hospital

Key Drivers of Decreased Costs:
Health Service Areas like Capital/Adiron and Southern Tier: Show significantly reduced average costs per discharge (impacts: $59K and $58.31K, respectively).

3. Discharge Distribution and Patient Outcomes

Total Discharges: 26,000 across all hospitals, with 151 unique hospitals and 627 surgeons involved.

Common Diagnosis: The majority of discharges are related to hip replacement surgeries and osteoporosis-related treatments.

Discharge Destinations:
A significant proportion of patients are discharged to home/self-care, while others are sent to skilled nursing or inpatient rehabilitation facilities.

## Recommendations

High Priority
Focus on Reducing Length of Stay (LOS):

Implement enhanced care protocols for patients in hospitals like Kings County Hospital and Interfaith Medical Center to address the extended LOS while maintaining quality care.
Use predictive models to identify high-risk patients (e.g., extreme severity or mortality risk) early, enabling better resource allocation and preemptive interventions.

Cost Optimization Strategies:

Investigate high-cost hospitals (e.g., NYU Lutheran Medical Center) for inefficiencies in operations or resource utilization.
Expand best practices from cost-efficient hospitals like United Memorial Medical Center to other facilities, focusing on maintaining high-quality care at lower costs.

Medium Priority
Regional Resource Management:

Adjust resource allocation to high-cost regions and areas with high LOS trends (e.g., New York City Health Service Area).
Prepare hospitals for seasonal fluctuations based on historical admission trends, especially in critical service areas.
Improved Discharge Planning:

Enhance post-discharge support for patients transitioning to home/self-care to reduce the likelihood of readmissions.
Collaborate with skilled nursing and rehab facilities to ensure smoother transitions for patients requiring extended care.
Low Priority
Diagnosis-Specific Programs:

Invest in early treatment plans for common diagnoses like osteoporosis and related conditions to reduce LOS and costs.
Pilot alternative care methods (e.g., outpatient physical therapy) for certain procedures to minimize hospital stays and associated costs.
Performance Benchmarking:

Regularly evaluate the performance of top hospitals (e.g., Northern Dutchess Hospital) with low LOS and costs to identify replicable success strategies.
