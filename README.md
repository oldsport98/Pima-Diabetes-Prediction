# Pima-Diabetes-Prediction

##### Using different ML models for diabetes prediction then with the help of ensemble method for increasing the accuracy.
Data Preprocessing
---
Shape of dataset : (768,9)

Features:
* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

Whether a patient has diabetes or not.

As Glucose ,BloodPressure , SkinThickness , Insulin and BMI cannot have zero values, so I have replaced them with mean of respective columns but Pregnancies can have a zero values so it is kept the same.

Models
---
Different models are used to compare accuracy then VotingClassifier is used to combine their results and increase the accuracy.

Final accuracy is **78.57%**
