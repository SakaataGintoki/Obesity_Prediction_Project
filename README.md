# Obesity Prediction

# Overview
Develop a robust Machine Learning model capable of accurately predicting obesity prevalence, incorporating essential variables including age, gender, height, weight, body mass index (BMI), physical activity level, and obesity category(Whether the person is Normal Weight, Obese, Overweight, Underweight).

# Problem Statement
The problem is to predict whether the person is Normal Weight ,Obese,Overweight,Normal Weight,there are some independent Variable are givem like Age,Gender,Height,Weight,BMI,physical Activity Level based on this several factor we need to create a Machine Learning Model.

# Dataset
- Age: The age of the individual expressed in years.
- Gender: Gender of individual categorized as male or female.
- Height: Height of a person in centimeters.
- Weight: Weight of a individual person in Kilograms (Kg).
- BMI: Body Mass Index (BMI) is a person's weight in kilograms divided by the square of height in meters.
- Physical Activity Level: A person individual level of physical activity.
- Obesity Category: Different obesity categories like Normal Weight, Obese, Overweight, Underweight based on their BMI.
  
# Libraries
- Pandas: To Process the data as the data was in CSV format.
- Matplotlib and Seaborn : It is commonly used for data visualization and creating various types of charts and plots.
- Scikit-learn: Scikit-Learn, also known as Sklearn is a python library to implement machine learning models and statistical modelling.

# EDA Pre-Processing

To perform EDA is one of the most important thing to do before applying any Machine Learning Model .It make sures that data is been validate and no outliers are present
Eda and pre procession steps -
a) handling the missing value
b) converting categorial to numeric
c) feature scaling(Standard scaling)
d) Handling outliers (value more than IQR is outliers)
e) train test split


# Machine Learning Model
Based on Independent Variables the problem is Multi Classification we will use 3 Algorithm (i.e)
- Naive Bayes Algorithm
- Support Vector Machine
- Decision Tree Classifier.

# Naive Bayes Algorithm
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/6f5a1eb1-cd5d-4647-8069-d721c4dbd2cb)
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/5f4fc3b4-3a97-4c96-b1ae-fc084f182715)

# Evaluation
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/24df476a-01e9-4591-ae7b-e1a80cf6e92f)

# Support Vector Machine (Classifier)
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/2945e054-0d93-4d8c-9306-37b3a4c2ede6)
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/7adb7686-d49d-4753-909a-54ccee9234ad)

# Evaluation 
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/76037ca9-93db-4403-9fb1-afba6015a753)

# Decision Tree Classifier
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/e51a7d62-76f8-452f-93fb-d20f44a9bb4e)
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/3a849333-4abd-472b-bc71-9220ca39f282)
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/30e10811-d543-4b53-ae97-6c637de566ea)

# Evaluation
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/a6d13d73-3450-4766-8185-c5eacaa5c6cc)

# Comparision and Results
![image](https://github.com/SakaataGintoki/Obesity_Prediction_Project/assets/107795560/7ef168e0-faa3-48f5-b3b9-e52fcd6d776b)













