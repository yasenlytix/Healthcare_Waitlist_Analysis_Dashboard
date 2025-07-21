# Healthcare_Waitlist_Analysis_Dashboard

<br>
<br>

# **🎯 Project Goals**

### 1. Track the current status of the patient waiting list.
### 2. Analyze the historical monthly trend of the waiting list in inpatient and outpatient waiting lists.
### 3. Build a dynamic dashboard for data-driven decision making and smarter resource planning.

<br>

# **🧾 Data Scope**
### 2018 ---> 2021

<br>

# **📈 Metrics Required**
### 1. Average & Median waiting list.
### 2. Current total waitlist.

<br>

# **📌 Views Required**
### A. Summary Dashboard

<br>
<br>

------------------------------------

<br>
<br>

# ***🚀 Project Working***

<br>

## 😫 Problems To Uncover
#### **☑️ Rising Wait List:-** The Latest month’s total wait list is 709K, increased from 640K last year — showing a clear backlog trend.
#### **☑️ Long Waiting Periods:-** Over 415 cases are waiting for 18+ months, indicating serious delays in patient treatment.
#### **☑️ Age Group Imbalance:-** A large portion of waitlisted patients are aged 0–15, raising concerns about delayed care for children.
#### **☑️ Case Type Pressure:-** 72.49% of all cases are Outpatient, highlighting an overloaded outpatient system needing process improvements.
#### **☑️ No Declining Trend:-** Despite slight seasonal drops, no long-term decreasing trend exists, pointing to systematic backlog issues.

<br>

## 😵 Steps Taken to Uncover Possibilities

### 1️⃣ Data Collection & Cleaning
#### I started by collecting raw data from XLSX files. Cleaned it in Power Query, fixed missing values, removed errors, and filtered the needed date range (Jan 2018 to Mar 2021).

### 2️⃣ Data Modelling
#### I built a Date Table for better time analysis. Connected tables with correct relationships (Date, Case Type, Specialty). Then created simple hierarchies like Year > Quarter > Month to make trends easy to explore. Efficient Data Modeling made this visual possible.

<br>

<p align="center">
  <img src="https://github.com/yasenlytix/Healthcare_Waitlist_Analysis_Dashboard/blob/b9a3cb5db09342e6ad9b5e1b0412c214e98d6cef/3rd_KPI.jpg?raw=true" alt="3rd_KPI" style="max-width: 100%; height: auto;" />
</p>


<br>


### 3️⃣ Essential DAX Measures
#### I wrote easy-to-medium-level DAX formulas to calculate total wait list numbers, compared current vs last year trends, and found averages or medians for wait times. Also, calculated percentages for each case type (Outpatient, Day Case, Inpatient). The best thing I did here was that I separately created a table and then inserted all custom measures into it.

### 4️⃣ Built Interactive UI & Visuals
#### I designed clear visuals — like pie charts for case type split, line charts for monthly trends, and stacked columns for age groups vs wait time. I used cards for highlighting key numbers. Then I added slicers so users can filter by date, specialty, or case type. I used Figma here to build a seamless user experience with interactive UI to make things interesting and easily approachable even for non-technical users.

### 5️⃣ Found Deeper Patterns
#### I used simple DAX and filters to see the Top 5 Specialties with the longest waits. Then I grouped patients by age bands and waiting periods to spot hidden delays. This helped me reveal exactly where the biggest backlogs were. It was a bit difficult to get this simple visual cause it made me able to write complex DAX, and after some research, I made it possible.


<br>

<p align="center">
  <img src="https://github.com/yasenlytix/Healthcare_Waitlist_Analysis_Dashboard/blob/ca8dfbf7289fca1efb2c6433398c3e758425a7bd/1st_KPI.jpg?raw=true" alt="1st_KPI" style="max-width: 100%; height: auto;" />
</p>


<br>


### 6️⃣ Double-Checked Accuracy
#### During the building process, I always double-checked whether the numbers matched the raw data. I tested the dashboard visuals and filters again & again. I added drill-through pages or tooltips to let users see details behind summary charts.

<br>

### ✅ Data-driven Impact
#### I highlighted the main pain points clearly:- 
#### Rosen wait lists, overloaded outpatient cases, and long delays for certain specialties and age groups. This approach made the dashboard interactive and easy for decision-makers to explore.
#### Ultimately, I	turned complexity into clarity, enabling faster data-backed decisions, budget controlling, and smarter resource planning.

<br>
<br>
<br>

![Healthcare_Report](https://github.com/yasenlytix/Healthcare_Waitlist_Analysis_Dashboard/blob/12e05f88ea4cae84b58fda952dd953b7790829be/Hc_Dashboard.jpg)



<br>
<br>

> ## Note
### This Dashboard is a Mix of:---
- #### My Research
- #### Kaggle Dataset
- #### Medical Understanding
- #### Tutorials (-- especially on DAX & Custom Measures --)
- #### Figma (-- I nailed the Dashboard UI using Figma --)
- #### MS Power BI
- #### ChatGPT

<br>

#### 💬 Share your thoughts and comments if you found something helpful...

<br>
<br>


> ***<h3 align="center">Data is like a Parasite, it needs a host to grow!</h3>***


<br>
<br>
