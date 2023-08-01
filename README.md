## Mental Health in Tech Survey - Data Analysis, Visualization, Machine Learning Prediction Analysis

**About**
- This Dataset contains survey data about mental health, completed by people working in Tech Industry
- Used skills:- EDA, Data Analysis & Visualization, and Machine Learning for predicting seeking of 'treatment'
- about_data.png : Provides info on the variables
- __NOTE__: Some plots are made using Plotly, thus will only be visible when actually running the notebook on
the machine. These plots will not be visible on github notebook viewing.

**Implementation**
- The data is fetched into pandas. Basic EDA operations are performed.
- The columns are cleaned of NA values and unwanted features are dropped.
- The Data is preprocessed. Categorical variables are fixed, mis-typed values are fixed, etc.
- Now the data is analysed and visualized, interactive plots are generated for simplicity
and user-friendliness.
- A correlation matrix is specifically generated to also aid in feature selection for predictive
analysis.
- Logistic Regression using sklearn is used for Machine Learning problem of predicting if
treatment was seeked.

**Results**
- Best parameters : 
- - log_reg__C = 0.01
- -	log_reg__penalty = l2
- -	log_reg__solver = 'newton-cg'

**References**
 
Credits to Kaggle Dataset:
https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

 
