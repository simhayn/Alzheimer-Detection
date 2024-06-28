## Doctor, is he sick? does he have Alzheimer's disease? 😯🩺 <br>
Let's see.. <br> 
well, this algorithm can detect if the patient is sick with 94% accuracy <br>
The most **relevant features** for this **xgboost** model are as follows:
1. **Functional Assessment** (ranging from 0 to 10. Lower scores indicate greater impairment)
2. **ADL (Activities of Daily Living** score, ranging from 0 to 10. Lower scores indicate greater impairment)
3. **MMSE (Mini-Mental State Examination** score, ranging from 0 to 30. Lower scores indicate cognitive impairment)
4. **Memory Complaints**
5. **Behavioral Problems**

And there are some more (not so much contributing) features:  

6. Cholesterol HDL
7. Diet Quality
8. Sleep Quality
9. Alcohol Consumption
10. Cholesterol Triglycerides

the model was fit to patients who had normal levels of cholesterol and blood pressure, in the ages of 60-90 years old.

## Binary Classification- Alzheimers
In this project I explored the 🧠 Alzheimers disease dataset downloaded from Kaggle.com
Main steps:

- **Exploratory Data Analysis** (EDA): Visualize features' relationships and distributions.
- **Data Preprocessing**: Scale the cumulative features.
- **Model Training**: Train some models on the preprocessed data. *(Models: SVM, Log. Regression, Rand. Forest, GBoost, Naive Bayes, XGBoost with Randomized searchCV, Neural Networks)*
- **Model Evaluation**: Evaluate the models' performances.

Hope you enjoy this project! 
