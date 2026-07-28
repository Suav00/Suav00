# Hey, I'm Shuaib 👋

🎓 Data Science student at the **University of Texas at Arlington** (Class of 2027)
📊 Focused on **machine learning, forecasting, and risk modeling**
🌱 Currently exploring Data Science and ML
📫 Reach me at Shuaibjama96@gmail.com | [LinkedIn](http://linkedin.com/in/shuaib-jama-80219925b)

I build end-to-end ML projects — from raw data to a deployed, interactive dashboard — across healthcare, finance, and energy. Below is a walkthrough of what I've built and what I learned from each one.

---

## 🚀 Featured Projects

### ⚡ Multi-Horizon Electricity Demand Forecasting
**Time Series ML | LightGBM | 50,000 hours of German grid data**

I built a forecasting system that predicts electricity demand across 24-hour, 72-hour, and 7-day horizons — and benchmarked it directly against ENTSO-E, the official European grid operator standard.

- 📉 Beat the industry benchmark by **44.6%** (MAPE 2.02% vs. 3.52%)
- 🛠️ Engineered 34 time-series features and applied STL decomposition to separate trend, seasonality, and noise
- 🔍 Used SHAP to explain *why* the model predicted what it predicted, not just what it predicted
- 📏 Built conformal prediction intervals (81% verified coverage) so the model reports its own uncertainty
- 🦠 Studied how the model's accuracy broke down during the COVID-19 demand shock, and used that to recommend a retraining cadence for production

🔗 [Live Demo](https://multi-horizon-electricity-forcasting.netlify.app/)

---

### 🕵️ Fraud Detection Classification Model
**Capstone Project | scikit-learn | Explainable AI**

My capstone project: a full pipeline to catch fraudulent transactions hidden in a heavily imbalanced dataset.

- 🧹 Cleaned and engineered features from raw transaction data
- ⚖️ Applied class imbalance handling techniques to stop the model from just predicting "not fraud" every time
- 🧠 Used SHAP to interpret *which* transaction features actually drove each fraud flag
- 📈 Evaluated with precision, recall, F1, and ROC-AUC — because accuracy alone lies to you on imbalanced data

🔗 [Live Demo](https://datacapstone.netlify.app/)

---

### 💰 JPMorgan Chase & Co. — Quantitative Research Virtual Experience
**Forage | Python | Dynamic Programming | Regression**

A 4-part simulation into how a real quant research desk prices commodities and models credit risk.

- 📈 Modeled natural gas prices using trend + seasonal regression, and used it to price commodity storage contracts
- 🏭 Built a generalized pricing engine handling multiple injection/withdrawal dates, storage limits, and holding costs
- 🏦 Trained a logistic regression model to estimate probability of default from a loan book, and converted that into expected loss
- 🧮 Implemented a **dynamic programming algorithm** to optimally bucket FICO scores by maximizing log-likelihood — and validated it exactly against JPMorgan's own reference solution

---

### 🩺 TruBridge — Healthcare Data Analytics Externship
**Remote | 4-Month Program**

- 🔬 Analyzed a CDC health dataset with multiple predictive models to identify diabetes prevalence trends and risk factors
- 📊 Built an interactive dashboard so stakeholders could explore health indicators in real time
- 💡 Turned model outputs into actionable recommendations for community health interventions

🔗 [Live Dashboard](https://trubridgeexternship.netlify.app/)

---

## 🛠️ Tech Stack

**Languages:** Python, SQL, R, SAS
**ML/Data:** Pandas, NumPy, Scikit-learn, TensorFlow, PyTorch, LightGBM, SHAP
**Visualization:** Matplotlib, Seaborn, Tableau, Power BI
**Tools:** Jupyter Notebook, Google Colab, Git, GitHub, VS Code

## 📜 Certifications
DeepLearning.AI · IBM Data Science Methodology · Google Generative AI

## 🌍 Languages
English, Arabic, Somali

---

⭐️ If any of these projects are useful to you, feel free to star the repo — and reach out if you want to talk data science, forecasting, or quant finance!
