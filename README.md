# SQL_Healthcare_Data_Management

Problem Statement:

A hospital wants to implement a Patient Management System to efficiently manage patient
records, doctor appointments, treatment history, and hospital performance metrics. The system
should allow for the storage of electronic health records (EHR), patient demographics, medical
diagnoses, treatment history, and doctor information. Additionally, it should support analysis of
patient demographics, disease prevalence, treatment outcomes, and hospital performance
metrics.

Solution:

1) Designed and Implemented a relational database system to store patient and doctor
information, medical records, and treatment details.

2) Utilized SQL queries to perform various analyses such as patient demographics, disease prevalence, treatment outcomes, and hospital
performance metrics.

Database Schema: 

Patients Table: patient_id (PK), patient_name, date_of_birth, gender, address, phone_number

Doctors Table: doctor_id (PK), doctor_name, specialization, department

Medical Records Table: record_id (PK), patient_id (FK), admission_date, discharge_date, diagnosis, treatment, doctor_id (FK)

SQL Analysis:

1) The percentage of male and female patients in the database was calculated.
2) The patient with the highest number of medical records was identified.
3) The top 3 doctors who treated the most patients were listed.
4) The average length of hospital stay for each diagnosis was calculated.
5) Patients were ranked based on the number of medical records they had, from highest to lowest.
6) The patient who spent the most time in the hospital was displayed.
7) The median length of hospital stay for all patients was calculated.
8) Patients who were treated by doctors specializing in Cardiology or Pulmonology were listed.
9) The doctor who treated the most patients diagnosed with Diabetes was identified.
10) The total number of patients treated by each doctor, including those with no patients, was calculated.
11) Patients who had been readmitted within 30 days of discharge were identified.
12) The average length of hospital stay by month for the past year was calculated.
13) Patients who had been admitted to the hospital more than once in the past year were listed.
14) Patients whose total hospital charges exceeded a certain threshold were found.
15) The percentage change in the number of patients admitted each month compared to the previous month was calculated.

![Health_sql1](https://github.com/user-attachments/assets/8b5cda69-6b88-4154-9b7a-dbf741ada0f5)


![image](https://github.com/user-attachments/assets/ebc720b0-ee6f-4813-8ffd-ee99c8e5fcef)


