🚢 Titanic Survival Prediction Using Machine Learning
Welcome to my Titanic Survival Prediction project — a beginner-friendly machine learning project based on the classic Titanic dataset from Kaggle.

This project helped me understand the end-to-end process of a data science workflow, including data preprocessing, feature selection, model training, prediction, and CSV submission.

📌 Project Objective
To build a machine learning model that can accurately predict whether a passenger survived or not based on features like passenger class, number of siblings/spouses, and parents/children aboard.

📊 Dataset Overview
The dataset contains passenger data such as:

Pclass – Ticket class (1st, 2nd, 3rd)

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Survived – Target variable (0 = No, 1 = Yes)

⚙️ Tools & Technologies Used
Python

Pandas

Scikit-learn

Google Colab

Random Forest Classifier

Matplotlib / Seaborn (optional for future visualization)

🧠 Machine Learning Model
Used a RandomForestClassifier with 100 estimators and a maximum depth of 5.

python
Copy
Edit
model = RandomForestClassifier(n_estimators=100, max_depth=5, random_state=1)
model.fit(X, y)
📈 Model Evaluation
Although the dataset and testing was basic, this initial model gave a good understanding of:

Feature engineering

Data preprocessing with get_dummies()

Making predictions

Generating CSV submissions for competitions

📁 Output
A submission.csv file is generated with:

PassengerId

Predicted Survived (0 or 1)
