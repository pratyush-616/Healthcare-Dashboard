# Healthcare-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/bc63fb9e-5be2-4f82-9d95-64f5244f3bad/5649d582c4b0400c0104?experience=power-bi

## Problem Statement

This dashboard helps hospitals an understand of their patients' situations. It helps the hospitals by giving them an idea of the type of bed occupancy by a patient, the diagnosis type, the doctors who treated patients for various diseases as well as giving them in idea of final bills and health insurance costs.

Since the healthcare sector is a pivotal area of our economy, it is important for theese hospitals to be organized and well informed of their daily operations.


### Steps followed 

- Step 1 : Loading data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Followup Date".
- Step 5 : Cards indicating Admit Date, Discharge Date, Follow up Date and Billing Amount were added to the dashboard after formatting into their appropriate formats.
- Step 6 : Two slicers, one indicating patient IDs and another indicating admit dates were added into the dashboard so as to extract patient information as per requirement.
- Step 7 : A column chart indicating the type of bed occupancy as a count of bed occupancy was added. The beds were split into three categories, namely, Private,General and ICU.
- Step 8 : A doughnut chart was added indicatiing the Total Feedback recieved per doctor. This also gives us an idea of which doctors have been undertaking the diagnosis of patients.
- Step 9 : A funnel graph was added which indicates the totality of different diseases and represents each disease as a percentage of the first being viral infection. This gives us an overview of the different diseases being treated in the hospital.
- Step 10 : A line graph was introduced which shows us the billing amount to be paid by the patient after treatment and how much of the total bill was covered by health insurance. It also shows us the types tests done on patients to confirm their diagnosis.

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Billing Amount = 190.43 Million INR

   
           
### [2] Split of Bed occupancy

    a) Private beds occupied - 3579
    b) General beds occupied - 2385
    c) ICU beds occupied - 1193
    
  

  
  ### [3] Feedback Volume per doctor
  
      a) Feedback Volume for Dr.Jay Sinha = 1023
      b) Feedback Volume for Dr.Jaya Yaadav = 1023
      c) Feedback Volume for Dr.Mark Joy = 1023
      d) Feedback Volume for Dr.Naresh Goyenka = 1022
      e) Feedback Volume for Dr.Niki Sharma = 1022
      f) Feedback Volume for Dr.Ravi D = 1022
      g) Feedback Volume for Dr.Tejas Saxena = 1022








 ### [4] Split of Diagnostics
    1. Total count of patients with Viral infection = 2004
    2. Total count of patients with Flu = 1717
    3. Total count of patients with Malaria = 1431
    4. Total count of patients with Typhoid = 1145
    5. Total count of patients with Pneumonia = 573
    6. Total count of patients with Fracture = 287 

## Dataset Used
[Healthcare-Dataset.xlsx](https://github.com/user-attachments/files/18137854/Healthcare-Dataset.xlsx)
