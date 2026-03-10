 Hotel Booking Cancellation Prediction

Overview
A machine learning project to predict whether a hotel booking will be cancelled.
Performed data cleaning, EDA, feature engineering, and trained two ML models.

Tools & Technologies
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

Dataset
- Source: Kaggle — Hotel Booking Demand Dataset
- 119,390 records, 32 features

Project Steps
1. Data Cleaning — handled missing values, dropped irrelevant columns
2. Exploratory Data Analysis — cancellation trends by hotel type, month
3. Feature Engineering — created total_stay, total_children features
4. Model Building — Logistic Regression and Random Forest
5. Evaluation — accuracy, confusion matrix, classification report

Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~81.8% |
| Random Forest | ~88.8% |

 Key Insights
- Random Forest outperforms Logistic Regression
- Lead time and deposit type are the strongest predictors of cancellation
- City hotels have higher cancellation rates than Resort hotels
- Bookings made far in advance are more likely to be cancelled
