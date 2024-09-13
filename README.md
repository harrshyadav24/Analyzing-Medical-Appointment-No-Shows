
# Analyzing Medical Appointment No-shows

Suppose you are a patient who visited a doctor and scheduled an appointment, but you didn’t attend at the scheduled time. This is known as a medical appointment no-show. If doctors or hospitals can predict which patients are likely to miss their appointments, they can implement a reminder system for those who might forget, leading to better patient health outcomes and improved resource utilization for doctors and hospitals. In this project, we analyze medical appointment no-shows.


## Dataset

The dataset contains information on 110,527 patients, including the following 14 features:

- PatientId
- AppointmentID
- Gender
- ScheduledDay
- AppointmentDay
- Age
- Neighbourhood
- Scholarship
- Hypertension
- Diabetes
- Alcoholism
- Handicap
- SMS_received
- No-show

We also added an additional feature "waiting days," which means the number of days patient has to wait for the appointment. The target variable in our analysis is "No-show," and the remaining features are used to predict whether a patient will miss their appointment.

## Models Used

Ensemble learning is applied to combine the strengths of multiple individual models, resulting in a more accurate and reliable predictive system. The models used in this project include:

Logistic Regression, Decision Tree, Random Forest, Gradient Boost, Extra Tree, Bagging, AdaBoost, Ridge Classifier, K-Nearest Neighbors (KNN), XGBoost, Naive Bayes from these, the top 5 models (based on precision and recall) were selected and ensembled for improved performance.

![App Screenshot](https://github.com/harrshyadav24/Analyzing-Medical-Appointment-No-Shows/blob/main/Screenshot%2024-09-13%103349.png)

## Results

 From our Exploratory Data Analysis we have found the following results:
 - Younger patients tend to be associated with a higher likelihood of no-shows could be attributed to various factors.

![App Screenshot](https://github.com/harrshyadav24/Analyzing-Medical-Appointment-No-Shows/blob/main/Screenshot%202024-09-09%20010854.png)

- The observation that patients with a waiting time of 0 days tend to show up for their appointments suggests that same-day or immediate appointments are associated with higher attendance rates.

![App Screenshot](https://github.com/harrshyadav24/Analyzing-Medical-Appointment-No-Shows/blob/main/Screenshot%202024-09-09%20011143.png)

- Surprisingly, the finding that patients who receive SMS reminders tend to no-show suggests that the effectiveness of SMS reminders might not be as straight forward as assumed.

![App Screenshot](https://github.com/harrshyadav24/Analyzing-Medical-Appointment-No-Shows/blob/main/Screenshot%202024-09-09%20011213.png)