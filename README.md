# Healthcare Data Understanding, Cleaning & Exploratory Analysis

##  Project Overview

This project focuses on understanding, cleaning, and analyzing healthcare data using **Python and Pandas** in **Google Colab**.

The main purpose is to clean healthcare records, standardize date values, categorize patient admissions, calculate summary statistics, and analyze patient demographics based on medical conditions.

##  Objectives

* Understand the healthcare dataset.
* Identify and clean missing values.
* Standardize date attributes.
* Calculate hospital stay duration.
* Categorize admissions into Emergency, Elective, and Urgent.
* Calculate billing and hospital stay statistics.
* Analyze demographics based on medical conditions.
* Visualize important healthcare information.

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Google Colab
* CSV Dataset

##  Dataset Information

The dataset contains patient-related healthcare information such as:

* Patient Name
* Age
* Gender
* Medical Condition
* Date of Admission
* Discharge Date
* Billing Amount
* Admission Type
* Other healthcare-related attributes

##  Data Cleaning

The following cleaning operations are performed:

1. Missing numerical values are replaced using the median.
2. Missing categorical values are replaced using the mode.
3. Date columns are converted into proper datetime format.
4. Admission types are standardized.
5. Hospital stay duration is calculated from admission and discharge dates.

##  Admission Categorization

Patient admissions are categorized into three types:

* **Emergency** – Immediate medical attention is required.
* **Elective** – Planned admission.
* **Urgent** – Requires prompt medical attention but is not necessarily an immediate emergency.

## 🏥 Hospital Stay Calculation

Hospital stay is calculated using:

```text
Hospital Stay Days = Discharge Date - Date of Admission
```

This helps analyze how long patients stay in the hospital.

##  Billing Analysis

Summary statistics are calculated for patient billing amounts, including:

* Mean
* Median
* Minimum
* Maximum
* Standard Deviation
* Quartiles

##  Hospital Stay Analysis

Summary statistics are also calculated for hospital stay duration.

This helps understand the average and variation in the number of days patients stay in the hospital.

##  Demographic Analysis

Patients are segmented based on their medical condition.

The analysis includes:

* Patient count by medical condition
* Average age by medical condition
* Gender distribution by medical condition
* Average billing amount by medical condition
* Average hospital stay by medical condition

##  Data Visualization

Matplotlib is used to create visualizations such as:

* Patients by medical condition
* Billing amount distribution
* Hospital stay distribution

These visualizations make it easier to understand patterns in the healthcare data.

##  Project Workflow

```text
Upload Dataset
      ↓
Understand Dataset
      ↓
Check Missing Values
      ↓
Clean Missing Values
      ↓
Standardize Dates
      ↓
Calculate Hospital Stay
      ↓
Categorize Admissions
      ↓
Calculate Summary Statistics
      ↓
Segment Demographics
      ↓
Create Visualizations
      ↓
Final Clean Dataset
```

##  How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Upload the healthcare CSV dataset.
4. Run the Python code step by step.
5. View the cleaned data, statistics, and visualizations.


## Plot Overview
Simple Visualization
<img width="785" height="669" alt="image" src="https://github.com/user-attachments/assets/dd10eb2d-afff-4138-99fc-8687f939685d" />


Billing Amount Distribution
<img width="732" height="575" alt="image" src="https://github.com/user-attachments/assets/fa3d13ee-d1d8-4166-84ef-d15a4ad3e42f" />

Hospital Stay Distribution
<img width="737" height="576" alt="image" src="https://github.com/user-attachments/assets/00993d01-2dc9-45b5-b4bc-741e19e41dca" />



##  Conclusion

This project demonstrates how Python and Pandas can be used to perform basic healthcare data cleaning and exploratory data analysis. The analysis helps identify patient patterns, admission categories, billing information, hospital stay duration, and demographic differences across medical conditions.

##  Author

**Kasthuri T**

BCA Student
