# **Personality Prediction Using Behavioral Data 🧠✨**

This project predicts personality traits (Introvert vs Extrovert) based on behavioral features collected from a survey dataset using Logistic Regression

-------------------------------------------
## **Dataset 📊**
The dataset contains 2900 rows and 8 columns including features such as:

🕒 Time spent alone

😨 Stage fear

🎉 Social event attendance

🚶 Going outside frequency

😴 Feeling drained after socializing

👥 Friends circle size

📱 Social media post frequency

🧑‍🤝‍🧑 Personality label (target variable)
-------------------------------------------
## **Data Processing 🛠️**

Checked and handled missing values and duplicates (no missing data found).

Encoded categorical variables (Stage_fear, Drained_after_socializing, and Personality) using Label & One-Hot Encoding.

Standardized features using StandardScaler to improve model performance.

Removed highly correlated redundant columns to reduce multicollinearity.
-------------------------------------------
## **Modeling 🤖**
Logistic Regression classifier with balanced class weights for handling class imbalance.

Tuned model parameters for optimal accuracy.

Trained and evaluated on train-test split data.
-------------------------------------------
## **Performance Metrics 📈**
Accuracy: 92.07% ✔️

Precision: 91.22% 🎯

Recall: 91.89% 🔄

F1 Score: 91.55% 🏆

Strong results showing accurate personality classification.
-------------------------------------------
## **Visualization 📉**
Correlation heatmaps to analyze feature relationships.

Confusion matrix heatmap to visualize classification results.
-------------------------------------------
## **Experiment Tracking 🧪**

Used MLflow for experiment logging and reproducibility.
-------------------------------------------
## **How to Use ▶️**

Load the dataset (personality_dataset.csv).

Run preprocessing (encoding, scaling).

Train the logistic regression model.

Evaluate and visualize results.

Track experiments using MLflow UI.
-------------------------------------------
## **Libraries 🧰**

Python, Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

MLflow

Polars (efficient dataframe ops)
