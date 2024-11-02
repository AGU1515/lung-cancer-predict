# lung-cancer-predict
Created a Logistic Regression model to predict Lung Cancer status of patients based off these factors: Gender, Age, Smoking, and the status of these conditions: Smoking, Yellow Fingers, Anxiety, Peer Pressure, Chronic Disease, Fatigue, Allergy, Wheezing, Alcohol Consuming, Coughing, Shortness of Breath, Swallowing difficulty, and Chest Pain. 

The model performed relatively well but there wasn't enough data to substantiate that this is a proper model - most of the cases were of people who did have lung cancer and there wasn't a good balance, so the model could just predict that the patient had lung cancer every time and still come down with a good accuracy. That being said, the model did have 100% precision on cases without lung cancer, which  may show that the model, despite its lack of data, was trained very well and can identify cases without lung cancer very well. Still, a better dataset is needed.

The Accuracy and classification report are at the bottom of the code. 

Dataset used: https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer/data
