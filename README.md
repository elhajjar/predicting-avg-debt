# predicting-avg-debt
In this project, the goal is to predict the average amount of debt using multivariate regression models. To do so, we are given several features describing a credit card owner's profile such as demographics variables (education level, age, gender, ethnicity..) or financial information (credit limit, credit rating, number of credit cards..).

The project is divided into sections based on a machine learning workflow from Data Exploration to Model Interpretation:

# I. Data Exploration
## A. General overview of the dataset
## B. In-depth analysis of numerical features (t-tests, pairplots, Pearson's correlation..)
## C. In-depth analysis of categorical features (ANOVA, univariate regressions, Cramer'V association..)
## D. Analysing relationships between numerical and categorical features
# II. Data Preparation
## A. Handling outliers
## B. Feature selection with statsmodel
## C. Feature engineering with polynomial features
# III. Modeling and Validating with scikit-learn
## A. Presenting the Model validation pipeline
## B. Training and validating the different model candidates
## C. Checking cross-validated results
# IV. Selecting best model and Handling overfitting
## A. Selecting the best model candidate using the test set
## B. Tuning the best candidate with selected regularization technique
## C. Summing up final model decision
# V. Model Interpretation
## A. Interpreting Model's main metrics
## B. Visualizing model's performance
## C. Testing and analysing model's output on new observations
