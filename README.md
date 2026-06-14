\# ML-Based Attendance Certification System



\## Overview



This project implements an Attendance Certification System using Machine Learning and Data Analytics techniques. The system processes attendance records of 980 students across 40 training sessions and determines certification eligibility based on attendance criteria.



The project includes data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), machine learning model training, and certification generation.



\---



\## Problem Statement



An internship program conducted 40 sessions for 980 students.



Certification criteria:



\* Total Sessions: 40

\* Session Duration: 120 Minutes

\* Minimum Attendance per Session: 90 Minutes

\* Minimum Attendance Requirement for Certification: 80%



A student is considered certified if they attend at least 32 out of 40 sessions.



\---



\## Dataset



\### Student Master Sheet



Contains:



\* Student\_ID

\* Student\_Name

\* Email



\### Session Sheets



40 attendance sheets:



\* Session\_01

\* Session\_02

\* ...

\* Session\_40



Each session contains:



\* Student\_ID

\* Student\_Name

\* Email

\* Attendance\_Minutes



\### Final Attendance Summary



Generated after processing:



\* Student\_ID

\* Student\_Name

\* Email

\* Sessions\_Attended

\* Attendance\_Rate

\* Certification\_Status



\---



\## Data Cleaning



The following preprocessing steps were performed:



\* Removed duplicate records

\* Filled missing email values

\* Standardized student names

\* Corrected attendance outliers

\* Generated attendance flags



Attendance Rule:



Attendance\_Minutes >= 90 → Present



Attendance\_Minutes < 90 → Absent



\---



\## Feature Engineering



Generated features:



\* Sessions\_Attended

\* Attendance\_Rate

\* Missed\_Sessions

\* Consistency



Target Variable:



\* Certified

\* Not Certified



\---



\## Exploratory Data Analysis



Performed:



\* Attendance distribution analysis

\* Certification statistics

\* Correlation analysis

\* Attendance pattern visualization



\---



\## Machine Learning Models



Implemented and evaluated:



1\. Logistic Regression

2\. Decision Tree Classifier

3\. Random Forest Classifier



Evaluation Metrics:



\* Accuracy

\* Confusion Matrix

\* Classification Report



\---



\## Project Workflow



1\. Load Dataset

2\. Clean Attendance Data

3\. Handle Missing Values

4\. Remove Duplicates

5\. Generate Attendance Matrix

6\. Perform Feature Engineering

7\. Conduct EDA

8\. Generate Certification Labels

9\. Train ML Models

10\. Compare Performance

11\. Export Final Certified Student List



\---



\## Technologies Used



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Scikit-learn

\* Jupyter Notebook

\* OpenPyXL



\---



\## Output



Generated file:



\- ML\_Attendance\_Report.xlsx



The workbook contains:

\- Student\_Master

\- Final\_Attendance\_Summary	

\- Session\_01 to Session\_40



The Final\_Attendance\_Summary sheet displays:

\- Sessions\_Attended

\- Attendance\_Rate

\- Certification\_Status

The final report contains certification status for every student.



\---



\## Future Improvements



\* Real-time attendance tracking

\* Web dashboard for students and administrators

\* Automated certificate generation

\* Attendance prediction using advanced ML models



\---



\## Author



Manish D



B.Tech Computer Science Engineering (AI \& ML)



