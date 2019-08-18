# UDACITY | Data Analyst Nanodegree Program 2019 | Project 2 Investigate Dataset

## Overview

The subject of this analysis is a [Kaggle dataset Medical Appointment No Shows](https://www.kaggle.com/joniarroba/noshowappointments) which describes more than 110,000 medical appointments in health units located within the city of Vitoria, Brazil and 14 features of each appointment).

I analyzed the dataset and then communicated my findings about it. I shared all the steps in the Jupiter Notebook file  [investigate_dataset_medical_appointment_no_shows.ipynb](https://github.com/aquamila/UDACITY_Investigate_Dataset/blob/master/investigate_dataset_medical_appointment_no_shows.ipynb).

## Data and Questions

The dataset is a CSV file [medical_appointment_no_shows.csv](https://github.com/aquamila/UDACITY_Investigate_Dataset/blob/master/medical_appointment_no_shows.csv). 

Data Dictionary:

__PatientId__ - identification of a patient.  
__AppointmentID__ - identification of each appointment.  
__Gender__ - gender of a patient: male or female.  
__ScheduledDay__ - a date on which an appointment was scheduled.  
__AppointmentDay__ - a date of an appointment.  
__Age__ - age of a patient.  
__Neighbourhood__ - a neighbourhood where an appointment took place.  
__Scholarship__ - if a patient has government financial aid Bolsa Familia: yes or no.  
__Hipertension__ - if a patient has high blood pressure: yes or no.  
__Diabetes__ - if a patient has diabetes: yes or now.  
__Alcoholism__ - if a patient is suffering from alcoholism: yes or now.  
__Handcap__ - if a patient has disability: the number of all of them.  
__SMS_received__ - if a patient got a text message appointment reminders: yes or no.  
__No-show__ - if a patient came to an appointment: no for "came" and yes for "didn't come".  

The following questions were investigated:   
 
1. Are patient no-shows related to a patient's personal features such as age, gender, the mentioned diseases, disabilities or getting government financial aid?
2. Do the appointment reminders affect the coming to the appointment?
3. Is the number of days between the date when the appointment was scheduled and the appointment date related to whether the patient come to the appointment or not?
4. Are there neighbourhoods where the patients are more likely not to miss their appointments?

## Technologies Used

- Jupyter Notebook
- Python 
- Python libraries NumPy, pandas, Matplotlib and Seaborn
