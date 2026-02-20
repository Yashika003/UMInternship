# UMInternship
UM Internship project code/files

Data Science Projects

This repository contains a collection of data science projects implemented using Python and Jupyter Notebooks.
Each notebook explores a real-world dataset and applies appropriate EDA, preprocessing, modeling, and evaluation techniques.
The projects cover diverse domains including climate analytics, healthcare, finance, customer support, and public health.

Projects Overview

1. Climate Variable Prediction (climate_pred.ipynb)
	•	Objective: Analyze and predict multiple climate indicators — temperature (nasa gistemp), global mean sea level (GMSL), and precipitation (noaa ghcn) — using historical climate data and machine learning models.
	•	Climate Variables Modeled: Temperature trends, Global Mean Sea Level (GMSL), Precipitation patterns
	•	Techniques Used: Data preprocessing and cleaning, Exploratory Data Analysis (EDA), Feature engineering, Linear Regression and Random Forest Regression
	•	Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R²)
	•	Key Focus: Multi-variable climate modeling, non-linear regression, and environmental data analysis for understanding long-term climate trends.
2. Customer Support Ticket Analysis (tickets.ipynb)
	•	Objective: Analyze and model customer support ticket data.
	•	Techniques used:
	  •	Text feature extraction (CountVectorizer)
	  •	Classification & regression models
	  •	Label encoding and scaling
	•	Key focus: NLP basics, customer analytics, supervised learning

3. COVID-19 Clinical Trials Analysis (COVID_trials.ipynb)
	•	Objective: Perform exploratory data analysis on COVID-19 clinical trials data.
	•	Techniques used:
	  •	Data cleaning and EDA
	  •	Statistical summaries
	  •	Visualization
	•	Key focus: Healthcare analytics and insight generation

4. Drug Side Effects Analysis (Drugs.ipynb)
	•	Objective: Analyze drug side-effect datasets to understand patterns and distributions.
	•	Techniques used:
	  •	Exploratory data analysis
	  •	Visualization using Seaborn & Matplotlib
	•	Key focus: Medical data exploration and interpretation

5. Stock Price Modeling – TCS (tcs_ml.ipynb)
	•	Objective: Analyze and model Tata Consultancy Services (TCS) stock data.
	•	Datasets used: Stock action, history, and company information
	•	Techniques used:
	  •	Linear Regression
	  • Time-series-aware feature handling
	•	Evaluation metrics: MSE, R²
	•	Key focus: Financial data analysis and predictive modeling

6. Tobacco & Public Health Analysis (tobacco.ipynb)
	•	Objective: Analyze tobacco-related admissions, fatalities, and prescriptions data.
	•	Techniques used:
	  •	Data preprocessing across multiple datasets
	  •	Feature engineering
	  •	Permutation feature importance
	•	Key focus: Public health analytics and data integration

Tech Stack
	•	Language: Python
	•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
	•	Environment: Jupyter Notebook

Repository Structure

.
├── climate_pred.ipynb
├── tickets.ipynb
├── COVID_trials.ipynb
├── Drugs.ipynb
├── tcs_ml.ipynb
├── tobacco.ipynb
├── README.md
├── .gitignore
└── LICENSE

Data Information
	•	Original datasets are not included in this repository due to:
	•	Size constraints
	•	Privacy considerations
	•	Notebooks assume datasets are available locally.
	•	Sample or synthetic data can be added if required.

Disclaimer

This repository is intended for learning, academic, and portfolio purposes.
The analyses and models are not intended for production or clinical decision-making.

License

This project is licensed under the MIT License.
