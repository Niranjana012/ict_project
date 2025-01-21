# Employee Resignation Prediction   

This project focuses on developing a machine learning model to predict employee resignations based on historical workforce data. The dataset includes 20 features that capture demographic, professional, and performance-related aspects of employees, such as age, department, job title, monthly salary, education level, performance score, and satisfaction rating. The target variable is a boolean indicator, Resigned, denoting whether an employee has resigned or not.   

The primary objective is to leverage predictive analytics to identify employees at risk of resignation, enabling proactive retention strategies. The Random Forest Classifier was chosen as the primary algorithm for its robustness and ability to handle complex datasets with mixed data types. The workflow involves data preprocessing steps like encoding categorical variables using Ordinal Encoder and OneHot Encoder, scaling numerical features with MinMaxScaler, and addressing class imbalance using techniques like SMOTE and Random Oversampling.   

The project incorporates exploratory data analysis (EDA) to understand key factors influencing resignation and evaluates model performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrix. Libraries such as pandas, scikit-learn, Seaborn, Matplotlib, and XGBoost were utilized to implement and optimize the predictive pipeline.    

This project demonstrates how data-driven insights can be used to mitigate employee turnover, improve workforce satisfaction, and reduce operational disruptions.    
