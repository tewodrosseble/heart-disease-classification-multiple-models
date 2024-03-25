# Multiple models on heart disease classification. 

On this project I was working on training multiple deeplearning and machine learning algorithms for heart diesease classification based on the values of: 


1. **Age:** Represents the age of the individual in years. Age is a significant risk factor for cardiovascular diseases; the risk increases as one gets older.

2. **Sex:** Indicates the biological sex of the individual (1 = male; 0 = female). Research shows that males are at a higher risk of developing heart disease at a younger age compared to females.

3. **Cp (Chest Pain Type):** Describes the type of chest pain experienced. It's typically categorized into several types, indicating different potential heart conditions or other causes.

4. **Trestbps (Resting Blood Pressure):** The blood pressure reading taken in a resting state, in millimeters of mercury (mm Hg), upon admission to the hospital. High resting blood pressure is a risk factor for heart disease.

5. **Chol (Serum Cholesterol):** Measured in milligrams per deciliter (mg/dL), it indicates the level of cholesterol in the blood. High cholesterol levels can lead to atherosclerosis, a condition that increases the risk of heart disease.

6. **Fbs (Fasting Blood Sugar):** Indicates if the fasting blood sugar level is greater than 120 mg/dL (1 = true; 0 = false). High fasting blood sugar levels can be a sign of diabetes, which is a risk factor for heart disease.

7. **Restecg (Resting Electrocardiographic Results):** Shows the electrical activity of the heart at rest and can indicate various heart conditions.

8. **Thalach (Maximum Heart Rate Achieved):** The highest heart rate achieved during a stress test. Lower maximum heart rates can indicate potential heart disease or poor cardiovascular fitness.

9. **Exang (Exercise-Induced Angina):** Indicates whether exercise induces angina (chest pain or discomfort) (1 = yes; 0 = no). Angina during exercise can be a sign of significant coronary artery disease.

10. **Oldpeak (ST Depression Induced by Exercise Relative to Rest):** Measures the amount of ST-segment depression (a specific change on an ECG) induced by exercise compared to rest. ST depression can indicate ischemia, a condition where the heart muscle is temporarily deprived of adequate blood supply.

11. **Slope (The Slope of the Peak Exercise ST Segment):** Refers to the slope of the ST segment during peak exercise. The ST segment slope can help in assessing the severity of ischemia.

12. **Ca (Number of Major Vessels Colored by Fluoroscopy):** Indicates the number of coronary arteries that have been significantly narrowed (0-3). A higher number suggests more severe coronary artery disease.

13. **Thal (Thallium Stress Test Result):** Thallium stress testing is a diagnostic method used to evaluate the blood flow to the heart muscle during exercise. It's categorized as 3 = normal, 6 = fixed defect (an area that doesn’t absorb thallium, indicating scar tissue from a previous heart attack), and 7 = reversible defect (an area with reduced blood flow at rest that improves with exercise, indicating potential for improvement in blood flow).

14. **Target:** Indicates the presence of heart disease (1 = yes, 0 = no). This is typically the outcome variable in studies aiming to predict cardiovascular disease risk.

These features are commonly used in datasets for machine learning models aimed at predicting the risk of heart disease. Each of these features can provide valuable insights into an individual's cardiovascular health and help in the early detection and prevention of heart conditions.

## Deep learning Sequential model 
This model is trained with around 38,000 parameters and give less accuracy because of the size and the type of data. 
the following image shows the summary of the deep learning model 

<img src="https://github.com/tewodrosseble/heart-disease-classification-multiple-models/blob/main/model.png">


## Algorithms 
The following image shows the neural network structure of the deep learning model with mathematical expression for forward propagation data fitting. And the cost function of the model.

<img src="https://github.com/tewodrosseble/heart-disease-classification-multiple-models/blob/main/algorithms.png">

## Scatter Plot for data representaion 
To avoid bias and discrimination the data must be equally distributed ( interms of quantity) therefore the following image shows the scatter plot of the labels. 

<img scr="https://github.com/tewodrosseble/heart-disease-classification-multiple-models/blob/main/scatter.png">

## Heart disease and Age 
The following image shows a simple reprentation of the age and heart disease relationship. 

<img src="https://github.com/tewodrosseble/heart-disease-classification-multiple-models/blob/main/heartDiseaseAndAges.png">

## Confusion matix 

After training the models using different algorithms we can compare them using the following confusion matrix

<img src="https://github.com/tewodrosseble/heart-disease-classification-multiple-models/blob/main/confusion.png">


## Tewodros Seble 
## @ 2022
