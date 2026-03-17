# Heart Disease Detection 
## Overview 
The project aims to whether the patient has Heart disease or not using machine learning models.
The dataset has many medical features of the patient such as Age, Sex, Resting bp, Cholesterol, Max heart rate, ST slope and many more.
Different Classification algorithms are used and Recall & Precision metrics are used for model evaluation.

<img width="900" height="1350" alt="image" src="https://www.southcoasthealth.com/assets/upload/695693f2-a879-4a36-aab5-386916191104/heart-attack-concept.jpg" /> 


---


## Dataset
- Entries : 1190 entries
- Features : 11 Numerical features
- Target/Output Column :
  - `0`- Normal
  - `1`- Heart Disease
    

---

  

## Technologies
- Python
- Pandas
- Numpy
- Matplotlib/Seaborn
- Scikit-learn:
  - Train-test split
  - Standard Scaler
  - Logistic Regression
  - Decision Tree Classifier
  - GridSearch CV
  - Random Forest Classifier
 
---


## Data Preprocessing
- Checked for missing values  
- Filled the null values.  
- Split dataset into training and testing sets

## Exploratory Data Analysis (EDA)
Performed:
- Class distribution analysis  
- Visualization of key features  
- Identification of the most influential attributes


## Models Used
### Logistic Regression
- Baseline model for classification tasks  
- Needs encoded numerical features  
- Gave good accuracy compared to Decision tree.
  
### Decision Tree Classifier
- Handles categorical features well  
- Easy to interpret
- overfitting
- Achieved lower accuracy compared to the Logistic regression.

### Random Forest Classifier
- Ensemble technique  
- Achieved high accuracy - 85.86%
- Hyperparameters tunned


## Model Evaluation
| Model               |  Accuracy     |     Recall     |  Precision   |   F1 score    | 
|--------------------|----------------|----------------|--------------|---------------|
| Logistic Regression | 82.60%        |   83%          |   85%        |   84%         |
| Decision Tree       | 75.55%        |   76%          |   80%        |   78%         |
| Random Forest       | 85.86%        |   88%          |   87%        |   88%         |



## Future Work
- Can build an web application.
- deploy for real time predictions.
