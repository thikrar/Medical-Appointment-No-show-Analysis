Medical Appointment No-show Analysis

Overview

This project analyzes a medical appointment dataset to identify factors associated with patient no-shows. The analysis focuses on understanding attendance patterns and providing insights that could help healthcare providers improve appointment management.

Dataset
Source: Kaggle
https://www.kaggle.com/datasets/joniarroba/noshowappointments

Records: 110,000+ medical appointments

Features: Patient demographics, appointment details, health conditions, SMS reminders, and attendance status.




Objectives:

Explore the overall no-show rate.

Analyze the relationship between age, gender, waiting time, SMS reminders, and attendance.

Identify factors associated with missed appointments.

Present findings through clear visualizations and business insights.


Tools Used:

-Python

-Pandas

-Matplotlib

-Plotly

-Google Colab



Data Cleaning:

The dataset was prepared by:

Converting date columns to datetime format.

Removing invalid age values.

Checking for missing values.

Checking for duplicate records.

Creating new features such as WaitingDays and WaitingGroup.



Key Findings:

Around 20% of appointments resulted in no-shows.

Waiting time showed the strongest association with missed appointments.

Same-day appointments had the lowest no-show rate.

Gender, diabetes, and scholarship status showed only small differences in attendance.

SMS reminders alone were not associated with lower no-show rates.






Recommendations:

Reduce appointment waiting times whenever possible.

Monitor patients with long waiting periods.

Review reminder strategies for high-risk appointments.

Continue tracking attendance trends to support scheduling decisions.




Project Structure:

medical-appointment-no-show-analysis/

│

├── medical_appointment_no_show_analysis.ipynb

├── README.md


└── images/

Author

Thikra Albadrani

Health Informatics Student


