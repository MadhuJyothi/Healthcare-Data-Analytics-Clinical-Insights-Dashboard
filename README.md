# Healthcare Data Analytics & Clinical Insights Dashboard

## Project Overview

This is an end-to-end **Healthcare Data Analytics** portfolio project
using synthetic healthcare data. It uses **Oracle SQL** for database
management and **Power BI** for modeling, analysis, and interactive
dashboards.

> **Note:** All data is synthetic and used only for educational and
> portfolio purposes. No real patient or protected health information
> (PHI) is used.

## Tools & Technologies

-   Oracle SQL / Oracle AI Database 26ai Free
-   Power BI Desktop
-   DAX
-   Excel
-   Git & GitHub

## Dataset

The project contains data for Patients, Doctors, Appointments,
Diagnoses, and Insurance Claims.

## Dashboard Pages

1.  **Healthcare Overview** --- Patients, doctors, appointments, claims,
    financial KPIs, denial reasons, and insurance providers.
2.  **Diagnosis & Clinical Analysis** --- Top diagnoses and diagnosis
    severity.
3.  **Clinical Trends & Patient Analysis** --- Diagnosis trends and
    patient demographics.
4.  **Patient Demographics** --- Age-group and geographic analysis.
5.  **Insurance & Patient Analysis** --- Insurance provider analysis by
    age group, gender, and city.
6.  **Healthcare Clinical & Claims Insights** --- Appointment volume,
    claim status, payments, and denied claims by diagnosis.
7.  **Healthcare Analytics Executive Summary** --- Management-level
    healthcare KPIs and summary insights.

## Key Metrics

-   30 Patients
-   8 Doctors
-   120 Appointments
-   54 Completed Appointments
-   54 Claims
-   12 Denied Claims
-   22.22% Claim Denial Rate
-   Total Billed Amount
-   Total Allowed Amount
-   Total Paid Amount

## Key Analysis Areas

-   Appointment status and trends
-   Appointments by doctor
-   Top diagnoses and severity
-   Patient demographics and age groups
-   Geographic patient distribution
-   Insurance provider distribution
-   Claim status and denial reasons
-   Claims by insurance provider
-   Billed vs. paid amounts
-   Payments by diagnosis
-   Denied claims by diagnosis

## Project Structure

``` text
Healthcare-Data-Analytics/
├── README.md
├── sql/
│   ├── 01_create_patients.sql
│   ├── 02_create_doctors.sql
│   ├── 03_create_appointments.sql
│   ├── 04_insert_sample_data.sql
│   └── 05_analysis_queries.sql
├── powerbi/
│   └── Healthcare_Analytics_Dashboard.pbix
├── data/
│   └── Healthcare_Informatics_PowerBI_Practice.xlsx
└── screenshots/
    └── healthcare-dashboard.png
```

## Data Model

The Power BI model connects patient, doctor, appointment, diagnosis, and
claims information using related identifiers such as Patient ID, Doctor
ID, and Appointment ID. DAX measures and calculated columns support KPIs
such as total patients, doctors, appointments, completed appointments,
claim denial rate, financial totals, patient age, and age groups.

## Purpose

This project demonstrates practical **Health Informatics and Healthcare
Data Analytics** skills including healthcare database design, SQL
querying, data modeling, DAX, healthcare KPI development, clinical and
claims analysis, Power BI visualization, and executive reporting.

## Disclaimer

This project is for **educational and portfolio purposes only**. All
patient, clinical, appointment, diagnosis, and claims data is synthetic.
