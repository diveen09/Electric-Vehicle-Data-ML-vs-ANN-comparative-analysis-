# Electric-Vehicle-Data-ML-vs-ANN-comparative-analysis-
This study uses a comparative analysis to evaluate which models are most suited for certain activities, providing insights into their strengths and limits. The findings are likely to increase forecast accuracy, classification approaches, and anomaly detection frameworks, hence promoting the adoption of sustainable transportation solutions.

**Electric Vehicle Data Analysis **
This project is part of my MSc Data Science thesis, where I explored how machine learning (ML) and deep learning (DL) models can be applied to real-world electric vehicle (EV) data. The goal was to understand how these technologies can support sustainable transportation through better predictions, smarter classification, and proactive anomaly detection.

🔍 What This Project Does
Using a large dataset (~210,000 entries) from the Washington State Department of Licensing, this analysis focuses on:

Predicting electric range of EVs using both classical regression models (like Random Forest Regressor) and deep neural networks

Classifying vehicles for Clean Alternative Fuel Vehicle (CAFV) eligibility — essentially deciding if a vehicle meets green energy policy standards

Detecting anomalies in the dataset (e.g., faulty records or data inconsistencies) using Isolation Forest

All of these are tackled through a structured data pipeline: starting with feature exploration and cleaning, followed by model selection, training, and evaluation using performance metrics like RMSE, F1-score, ROC-AUC, and more.

⚙️ Tech Stack & Tools
Python, Scikit-learn, TensorFlow/Keras

Google Colab (with GPU acceleration)

Pandas, Matplotlib, Seaborn

SMOTE for class balancing

📈 Key Insights and Contributions
Random Forest and XGBoost performed well for classification, but FNNs and DNNs captured more nuanced, non-linear patterns in regression.

Class imbalance was handled effectively using SMOTE, especially in CAFV classification.

Anomaly detection helped flag noisy records that could have skewed model performance.

I also incorporated standard practices like feature scaling, label/one-hot encoding, and train-test splits. Care was taken to avoid overfitting by applying cross-validation and regularization where needed.

🧠 Why This Matters in the Real World
Range anxiety is still a major blocker to EV adoption. By accurately predicting electric range based on historical data and vehicle characteristics, this project supports better decision-making for both consumers and manufacturers.

Likewise, reliable classification of vehicles for CAFV incentives can help governments allocate benefits more accurately, and fleet operators can use anomaly detection for cleaner data-driven decisions.

In short, this project demonstrates how applied ML/DL can directly support the growth of sustainable transportation systems.

📂 What You’ll Find in This Repo
Preprocessing/: scripts for cleaning and encoding the data

Models/: training notebooks for RF, XGBoost, FNN, DNN

Evaluation/: visualizations and performance comparisons

Documentation/: Project report
