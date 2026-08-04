# Student Study Hours Prediction

This project uses machine learning techniques to analyze and predict study hours based on dataset features.

##Dataset
500 student records
Features: 
Age, Gender, University Year, Sleep Duration, Screen Time, Caffeine Intake, Physical Activity, Sleep Quality, and sleep timing variables

## Technologies Used
- Python
- Pandas
- Scikit-learn(Linear Regression, Logistic Regression, preprocessing)
- Matplotlib & seaborn(visualizations)
- SciPy(statistical testing)

## Steps
- Data preprocessing & cleaning
- Exploratory Data Analysis (distributions, correlations, outliers)
- Hypothesis testing (Chi-square, T-test)
- Encoding categorical variables
- Feature normalization (StandardScaler)
- Train-test split (80/20)
- Model building: Linear Regression & Logistic Regression
- Model evaluation (MSE, R², Accuracy, Precision, Recall, Confusion Matrix)

##Key Findings
- No significant outliers detected (IQR & Z-score methods)
- No significant association between Gender and Physical Activity
- No significant difference in study hours between male and female students
- Logistic Regression achieved 50% accuracy in classifying sleep quality

##How to Run
pip install pandas numpy matplotlib seaborn scikit-learn scipy
jupyter notebook "Student Study Hours Prediction using Machine Learning.ipynb"



