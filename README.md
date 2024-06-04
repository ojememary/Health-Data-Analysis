# Health-Data-Analysis
Health Sector Analysis


<img width="949" alt="health dashboard" src="https://github.com/ojememary/Health-Data-Analysis/assets/155962114/bfbc1f06-cae7-4998-847c-7e02c1a6d997">


## Data cleaning

The tool I use for this analysis is Ms Excel and power query.
There were missing values in the age, gender, cholesterol, hour of sleep and covid columns. I created a new worksheet and use the count blank function to locate all the missing values. 

![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/0948f062-8e80-4523-be03-aac8cd2a988e)

## Handling Missing values


I use simple statistics to find the median of the age column using the analysis tool pack in Excel. The median age is 38

![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/9ba0f4d7-2a09-433c-b012-186b5cdf18bf)


## Data cleaning using power query

The number of rows were 48.
I use the fill down function to fill the blank in the age and gender, hour of sleep column.
I used replace value function to fill in the blank space in the covid Column.
I changed the data type of appointment from decimal to date.
I joined some terms in the medical column together using replace value e.g. flu and cold, Hypertension and Hyperten1on, migraine and migrain3 etc.
I use the conditional column to create Age range.
I deleted the cholesterol column , hour of sleep, water intake, hour of exercise because they will not be needed in my analysis.
I created a year and name of day column from the appointment date column.

## DIRTY DATA


![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/bdbf28e8-f82a-43cc-a506-048886b35e22)

## CLEANED DATA

![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/4a5bac7f-ed3a-45f7-9dfe-c4ad6bbd3a0b)

## Findings

Gender Distribution:

Male: 22

Female: 26

There are more female patient
than male.

![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/8fe7e2da-6c87-48a0-8d1c-e2730ff6f0b4)

Referral

The dataset reveals that 20 patients were referred by physicians, indicating professional recommendations for further medical attention. Additionally, 28 patients opted for self-referral, showcasing proactive healthcare-seeking behavior, while 2 cases were emergencies, involving immediate medical attention for urgent issues

![image](https://github.com/ojememary/Health-Data-Analysis/assets/155962114/4ae46f16-6c93-49f5-8709-a738a9c10aad)


## Summary Statistics

Age:
Mean age: 39 years
Minimum age: 26 years
Maximum age: 56 years

Blood Pressure (Systolic/Diastolic):
Mean: 131.1/85.3 mmHg
Minimum: 115/70 mmHg
Maximum: 144/92 mmHg
Duration of Illness:

Mean: 14.4 days
Minimum: 7 days
Maximum: 26 days
Cost of Treatment:

Mean: $492.9
Minimum: $170
Maximum: $1150

## Insight

Hypertension is the most common diagnosis in the dataset.
Most patients are satisfied with their treatment.
There is a mix of self-referrals and physician referrals.
The average age of patients is around 39.5 years.
Blood pressure readings are generally within the normal range, but some patients have high readings.
The cost of treatment varies, with some outliers.

## RECOMMENDATION

- Prioritize hypertension awareness campaigns for early detection and effective management.
  
 - Maintain high-quality and patient-centric services to sustain overall patient satisfaction.
   
-  Streamline referral processes to enhance coordination between self-referrals and physician referrals.
  
 - Implement targeted health screenings for the 36-40 age group based on the dataset's average age.
  
 - Intensify monitoring and interventions for patients with high blood pressure readings within the normal range.

 - Conduct a thorough review of treatment costs, standardize pricing, and ensure fair and consistent billing practices.
   
-  Enhance transparency and offer financial counseling to address patient concerns related to treatment costs.
  
-  Continuously analyze data, patient feedback, and treatment outcomes for ongoing quality improvement in healthcare services.































