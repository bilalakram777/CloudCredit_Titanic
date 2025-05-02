Titanic Survival Prediction
This project uses machine learning models to predict the survival of passengers aboard the Titanic. The dataset used is the Titanic Dataset, which includes various passenger features such as age, gender, class, and embarked location.

Key Steps:
Data Preprocessing:

Dropped irrelevant columns (Name, Ticket, Cabin).

Handled missing values by filling missing Age with the median and Embarked with the mode.

Encoded categorical features (Sex, Embarked) using LabelEncoder.

Model Building:

Trained two models: Logistic Regression and Random Forest Classifier.

Logistic Regression was scaled using StandardScaler for better convergence.

Evaluated both models using accuracy, precision, recall, and classification report.

Model Evaluation:

The models were evaluated on the test set and compared to assess their performance.
