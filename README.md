
⸻

💤 Social Media & Sleep Quality: A Causal Inference Analysis

📌 Project Overview

In today’s digitally connected world, understanding the impact of social media on well-being is critical. This project explores the relationship between social media engagement and sleep quality, using a dataset of over 300,000 individuals.

We aim to not only predict sleep quality using machine learning models, but also to infer causal effects—answering the question: “Does more time on social media actually worsen sleep quality?”

🎯 Objectives
	•	Analyze behavioral and demographic data related to digital habits.
	•	Build predictive models to estimate sleep quality.
	•	Use causal inference techniques to estimate the effect of social media usage on sleep quality.
	•	Provide actionable insights that can inform wellness-focused interventions.

⸻

📂 Project Structure
'''
📁 social-media-sleep-quality/
│
├── Social_Media_Prediction.ipynb   # Main analysis notebook
├── README.md                       # Project overview and documentation
└── data/                           # (Optional) Folder for raw and processed datasets'''

🧠 Key Features
	•	🧹 Data preprocessing and feature engineering
	•	🔍 Exploratory Data Analysis (EDA)
	•	🤖 Sleep quality prediction using machine learning models (Logistic Regression, Random Forest, etc.)
	•	📊 Visualization of feature importances and model performance
	•	🧪 Causal Inference using techniques such as:
	•	Propensity Score Matching (PSM)
	•	Inverse Probability Weighting (IPW)
	•	Average Treatment Effect (ATE) estimation

⸻

🧪 Techniques Used
	•	Python (3.7+)
	•	Scikit-learn, Pandas, Seaborn, Matplotlib
	•	CausalML / DoWhy (for causal inference)
	•	Jupyter Notebook

⸻

📈 Insights & Outcomes
	•	Social media engagement late at night is negatively correlated with sleep quality.
	•	After adjusting for confounders, causal inference techniques reveal a statistically significant causal effect—higher engagement tends to lead to poorer sleep.
	•	The most predictive features include: screen time duration, time of usage, demographic factors, and type of social media platform.

 📚 Future Work
	•	Apply time-series analysis on user-level usage patterns.
	•	Introduce real-time interventions based on predictive signals.
	•	Expand to other dimensions of digital well-being like productivity and anxiety.
