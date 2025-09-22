🎬 Cinema Sales Analysis Project 📊

Data science and machine learning project built as part of the Tuwaiq Academy – Week Two Bootcamp Project.
The project focuses on analyzing a cinema ticket sales dataset, performing exploratory data analysis (EDA), applying statistical tests using StatsModels, and building predictive models to estimate sales performance.
An interactive Streamlit dashboard allows users to visualize insights and interact with predictions.

⸻

👥 Team Members
	•	Shams – EDA, Data Cleaning, Presentation
	•	Rawan – Statistical Analysis (StatsModels), Presentation
	•	Areen – Model Development, Dashboard Design, Presentation

⸻

📌 Project Overview
	•	Exploring cinema sales dataset (cleaning, handling missing values/outliers).
	•	Performing EDA with visualizations to uncover sales patterns.
	•	Applying statistical analysis with StatsModels:
	•	Descriptive statistics (mean, median, std).
	•	Hypothesis testing (T-test: weekend vs weekday).
	•	Correlation analysis (ticket price vs total sales).
	•	Building Linear Regression (OLS) model.
	•	Residual analysis (model diagnostics).
	•	Building predictive models for ticket sales.
	•	Deploying an interactive dashboard with Streamlit.
	•	Delivering results in a clear and practical interface.

⸻

🛠 Built With
	•	Python → pandas, numpy, matplotlib, seaborn, scipy, statsmodels, scikit-learn
	•	Streamlit → interactive app & dashboard
	•	Machine Learning → Linear Regression, OLS
	•	Google Colab → analysis & experimentation

⸻

📊 Dataset
	•	Source: Cinema: (https://www.kaggle.com/datasets/arashnic/cinema-ticket )
	•	Before Cleaning: 142,524 rows, 16 features
	•	After Cleaning: 53,794 rows, 16 features
	•	Key Features: total_sales, tickets_sold, ticket_price, capacity, occu_perc, show_time, is_weekend

⸻

🔍 Key Insights
	•	Strong seasonality: Sales peak in Q1 & Q4, drop in Q3.
	•	Sales concentration: A few films & cinemas generate most of the revenue.
	•	Low occupancy: Theaters are often under-utilized (avg ~20%).
	•	Statistical findings:
	•	Weekends significantly increase sales (p = 0.032).
	•	Tickets sold, price, and capacity strongly affect total sales.
	•	Model results: Improved OLS model with R² = 0.873, showing strong predictive power.

⸻

📈 Outcomes

✅ Clean & reliable dataset ready for analysis.
✅ Predictive model (Linear Regression) with good accuracy.
✅ Insights on sales drivers: genre, time, day of week, and occupancy.
✅ Interactive Streamlit dashboard for visualization & prediction.
✅ Business value: better planning for scheduling, pricing, and maximizing cinema revenue.

⸻

🚀 Next Steps
	•	Improve predictive models using advanced algorithms (XGBoost, Random Forest, LSTM).
	•	Integrate external datasets (holidays, new releases, promotions).
	•	Enhance dashboard with richer KPIs & forecasting features.
