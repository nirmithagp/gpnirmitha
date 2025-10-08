🌾 Loan Recommendation System for Farmers
📘 Overview

The Loan Recommendation System is a machine learning-based project designed to recommend the most suitable loan or subsidy schemes for farmers.
Based on key inputs such as land type, crop name, annual income, and location, the system predicts and recommends:

✅ The best-matched loan scheme

⭐ Two alternative top loan options

This helps farmers make informed financial decisions quickly and efficiently.

⚙️ Tech Stack

Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Environment: Jupyter Notebook

🧠 Project Workflow

Data Collection:
The dataset includes farmer-related attributes such as:

Land type

Crop name

Annual income

Location

Previous loan history (if available)

Data Preprocessing:

Handling missing or inconsistent entries

Encoding categorical features (like crop name and location)

Normalizing numerical data

Model Building:
Machine learning algorithms such as Decision Tree, Random Forest, or Logistic Regression are trained to classify and rank suitable loan options.

Recommendation Logic:

Predicts loan eligibility based on farmer inputs.

Ranks the top 3 most suitable loans — one best and two alternatives.

Model Evaluation:
Metrics like accuracy, precision, recall, and F1-score are used to ensure reliable predictions.

🚀 How to Run Locally

Clone the repository

git clone https://github.com/<your-username>/loan-recommendation-system.git
cd loan-recommendation-system


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook "loan_recomm (1).ipynb"


Provide Inputs

Enter farmer details like:

Land Type

Crop Name

Annual Income

Location

View Output

The notebook displays:

🥇 Best Recommended Loan

🥈 Top 2 Alternative Loans

📊 Sample Output
Input	Best Loan Recommendation	Top 2 Alternatives
Land: Irrigated, Crop: Paddy, Income: ₹3,00,000, Location: Karnataka	Agricultural Loan Scheme - A	Crop Development Loan, Kisan Credit Yojana
Land: Dry, Crop: Cotton, Income: ₹2,00,000, Location: Maharashtra	Rural Support Loan	Agri Growth Scheme, Farmer Welfare Fund
🔮 Future Enhancements

Develop a Streamlit web app for real-time farmer interaction.

Add geographical and weather-based recommendations.

Integrate government scheme updates through APIs.

Connect to a cloud database (Firebase / MongoDB) for real-time data storage.
