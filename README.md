# 🌾 FARM-LOAN-RECOMMENDER

🧠 **AI-Powered Loan Recommendation System for Farmers** 🇮🇳  
An intelligent system that recommends the **best government or private loan schemes** for farmers based on their personal and agricultural details such as land type, crop name, annual income, and location.

Built using **Python**, **XGBoost**, and **Jupyter Notebook**, this model analyzes farmer inputs and provides the **top 3 most suitable loan options** — one best recommendation and two alternatives.

---

## 🚀 Features

### 🌱 Smart Loan Recommendations  
Predicts and ranks the most suitable loan or subsidy schemes using the **XGBoost machine learning algorithm**.

### 📊 Personalized Based on Farmer Inputs  
Recommends schemes by analyzing:  
- Land Type  
- Crop Name  
- Annual Income  
- Location  

### 🤖 Intelligent Ranking System  
Generates:  
- 🥇 **Best Recommended Loan**  
- 🥈 **Top 2 Alternative Loans**

### 🧮 Data-Driven Insights  
Performs feature analysis and evaluates model performance with accuracy, precision, recall, and F1-score.


---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| **Model** | XGBoost (Extreme Gradient Boosting) |
| **Programming Language** | Python |
| **Libraries** | pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn |
| **Environment** | Jupyter Notebook |
| **Visualization** | Matplotlib, Seaborn |

---

## 📦 Installation

1️⃣ Clone the Repository
git clone https://github.com/<your-username>/farm-loan-recommender.git
cd farm-loan-recommender
2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate     # For Windows
# OR
source venv/bin/activate  # For Linux/Mac

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Notebook
jupyter notebook "loan_recomm (1).ipynb"

🌾 Example Usage

Farmer Input Example:
Land Type: Irrigated
Crop Name: Paddy
Annual Income: ₹3,00,000
Location: Karnataka


Model Output:
Best Loan Recommendation	Top 2 Alternatives
Agricultural Loan Scheme - A	Crop Development Loan, Kisan Credit Yojana

Explanation:
The system analyzes the input parameters, predicts eligibility using XGBoost, and ranks the top loan schemes suited for the farmer’s financial and agricultural profile.

##🧪 Model Highlights

Algorithm: XGBoost Classifier
Evaluation Metrics: Accuracy, Precision, Recall, F1-score
Goal: Identify and rank best loan options for farmers efficiently.
Training Data: Contains features related to agriculture, income, and demographics.

##📝 Roadmap / Future Enhancements

🌐 Develop a Streamlit Web Interface for real-time use
🗺️ Integrate location-based recommendations
🧾 Add government scheme API integration for live updates
☁️ Deploy on Render / AWS / Vercel
🗣️ Add multilingual support (e.g., Hindi, Kannada)

