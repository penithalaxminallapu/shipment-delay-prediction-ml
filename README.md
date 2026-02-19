# shipment-delay-prediction-ml
A machine learning project using XGBoost to predict logistics delays based on customer behavior and shipment data.
# Shipment Delay Prediction 

### Project Overview
This project focuses on predicting whether a shipment will arrive on time or be delayed using a dataset of 10,999 observations. By identifying late shipments early, businesses can proactively manage logistics and improve customer satisfaction.

### Key Features
- **Model:** Tuned XGBoost Classifier.
- **Accuracy:** 67.59%.
- **High Recall for Late Shipments:** 98% (Ensures almost all delays are caught).
- **Techniques:** SMOTE for class imbalance, GridSearchCV for hyperparameter tuning.

### Insights Found
- **Discounts Offered:** The highest predictor of delay; large promotions often strain logistics.
- **Weight:** Heavier items correlate with higher handling times.
- **Prior Purchases:** Loyal customers show different processing patterns.

### How to Run
1. Clone the repo: `git clone https://github.com/penithalaxminallapu/shipment-delay-prediction-ml.git`
2. Open `Shipment_Delay_Analysis.ipynb` in Jupyter or Google Colab.
