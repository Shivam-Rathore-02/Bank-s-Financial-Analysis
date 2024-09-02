# **Bank’s Financial Performance Analysis Dashboard**

## **Project Overview**

This project involves the creation of a comprehensive Power BI dashboard to analyze the financial performance of a bank. The dashboard is designed to provide insights into key metrics such as bank deposits, achievements, and aspirations over time, helping stakeholders make informed decisions and strategize for sustainable growth.

## **Table of Contents**
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Dashboard Components](#dashboard-components)
  - [Overview Section](#overview-section)
  - [Quarterly Performance Analysis](#quarterly-performance-analysis)
  - [Past 12-Quarter Trend Analysis](#past-12-quarter-trend-analysis)
  - [Average Performance Calculation](#average-performance-calculation)
- [Interactivity Features](#interactivity-features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## **Data Description**

The dashboard utilizes data from two primary tables:

### **1. Market Share Table**
   - **City**: The city where the data is collected.
   - **Market Deposit**: Total deposit amount in the market for that city.
   - **Bank Deposit**: Total deposit amount held by the bank in that city.
   - **Market Deposit CAGR 3yr**: Compound Annual Growth Rate of the market deposit over the past 3 years.
   - **Bank Deposit CAGR 3yr**: Compound Annual Growth Rate of the bank's deposit over the past 3 years.

### **2. Vision Table**
   - **FY**: Fiscal Year.
   - **Quarter**: Quarter of the fiscal year (e.g., Q1, Q2, Q3, Q4).
   - **Sol ID**: Solution ID (unique identifier for solutions or products).
   - **Achievement_SA Retail**: Achievement of Savings Account (SA) Retail for the quarter.
   - **Achievement_SA ID**: Achievement of Savings Account (SA) ID for the quarter.
   - **Achievement_CA Retail**: Achievement of Current Account (CA) Retail for the quarter.
   - **Achievement_CA ID**: Achievement of Current Account (CA) ID for the quarter.
   - **Achievement_FD Retail**: Achievement of Fixed Deposit (FD) Retail for the quarter.
   - **Achievement_FD ID**: Achievement of Fixed Deposit (FD) ID for the quarter.
   - **Aspiration_SA Retail**: Aspiration (goal) for Savings Account (SA) Retail for the quarter.
   - **Aspiration_SA ID**: Aspiration (goal) for Savings Account (SA) ID for the quarter.
   - **Aspiration_CA Retail**: Aspiration (goal) for Current Account (CA) Retail for the quarter.
   - **Aspiration_CA ID**: Aspiration (goal) for Current Account (CA) ID for the quarter.
   - **Aspiration_FD Retail**: Aspiration (goal) for Fixed Deposit (FD) Retail for the quarter.
   - **Aspiration_FD ID**: Aspiration (goal) for Fixed Deposit (FD) ID for the quarter.
   - **Balance_SA Retail**: Balance of Savings Account (SA) Retail for the quarter.
   - **Balance_SA ID**: Balance of Savings Account (SA) ID for the quarter.
   - **Balance_CA Retail**: Balance of Current Account (CA) Retail for the quarter.
   - **Balance_CA ID**: Balance of Current Account (CA) ID for the quarter.
   - **Balance_FD Retail**: Balance of Fixed Deposit (FD) Retail for the quarter.
   - **Balance_FD ID**: Balance of Fixed Deposit (FD) ID for the quarter.

## **Dashboard Components**

The dashboard consists of the following main sections:

### **1. Overview Section**
   - **Purpose**: Provides a high-level summary of the bank's financial performance.
   - **Visuals**:
     - **Summary Card**: Displays key metrics such as Total Bank Deposit, Previous Quarter Bank Deposit, and Average Bank Deposit CAGR.
     - **Comparison Chart**: Compares metrics between the current and previous quarters.

### **2. Quarterly Performance Analysis**
   - **Purpose**: Visualizes the bank’s performance over the last quarter.
   - **Visuals**:
     - **Bar Chart**: Shows the bank's deposit amounts for the last and previous quarters.
     - **KPI Indicators**: Highlights metrics such as Quarterly Achievement Rate and Quarterly Growth Rate.
     - **Table**: Provides detailed data on achievements and aspirations.

### **3. Past 12-Quarter Trend Analysis**
   - **Purpose**: Displays a trend of selected metrics over the past 12 quarters.
   - **Visuals**:
     - **Line Chart**: Shows trends and highlights peak values.

### **4. Average Performance Calculation**
   - **Purpose**: Calculates the average performance of selected metrics over the most recent four quarters.
   - **Visuals**:
     - **Column Chart**: Displays the average performance metrics.

## **Interactivity Features**

- **Slicers**: Enable users to filter data based on branch hierarchy (e.g., City, Fiscal Year).
- **Click Interaction**: Clicking on data points in the charts filters other visuals to display relevant information for the selected period.


