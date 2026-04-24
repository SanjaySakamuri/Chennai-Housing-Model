# Chennai Housing Price Prediction using XGBoost

*A machine learning pipeline for predicting housing prices in Chennai using gradient boosting techniques.*

---

## Overview

This project presents an end-to-end regression pipeline for predicting real estate prices in Chennai based on property attributes such as area, locality, number of rooms, and amenities. The model leverages the XGBoost algorithm to achieve strong predictive performance while maintaining interpretability through feature importance analysis.

This work is designed as part of a machine learning portfolio, demonstrating practical competence in regression modeling, data preprocessing, and evaluation workflows.

---

## Key Features

- Comprehensive preprocessing pipeline including missing value handling, encoding, and scaling  
- Model training using XGBoost Regressor  
- Evaluation using Mean Squared Error (MSE) and R² score  
- Feature importance visualization for interpretability  
- Support for custom input predictions on unseen data  
- Implemented in a Jupyter/Colab environment  

---

## Repository Structure

```
chennai-housing-xgboost/
│
├── main.ipynb # Data processing, modeling, and visualizations
├── Chennai housing sale.csv # Dataset
├── requirements.txt # Dependencies
├── feature_graph.png # Feature importance visualization
└── README.md # Documentation
```

---

## Dataset Information

- Source: Kaggle – Chennai Housing Prices  
- Features: Area type, location, square footage, BHK, amenities, sale price, etc.  
- Note: The dataset was last updated in 2022 and may not reflect current market trends  

---

## Setup Instructions

### Running on Google Colab (Recommended)

1. Open `main.ipynb` in Google Colab  
2. Upload the dataset file when prompted  
3. Execute all cells  

### Running Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/Sanjaykumar030/Chennai-Housing-Model.git
    cd Chennai-Housing-Model
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open `main.ipynb` and run all cells  

---

## Workflow

| Step                | Description                                                   |
|---------------------|--------------------------------------------------------------|
| Data Exploration    | Inspect dataset structure and distributions                  |
| Data Cleaning       | Handle missing values and remove irrelevant features         |
| Encoding            | Convert categorical variables into numerical representations |
| Scaling             | Normalize continuous variables                              |
| Model Training      | Train XGBoost regression model                              |
| Evaluation          | Compute MSE and R²; compare predicted vs actual values       |
| Prediction          | Generate predictions for custom input data                  |
| Interpretation      | Analyze feature importance                                  |

---

## Sample Output


Mean Squared Error: 4,825,614.23
R² Score: 0.9945

Predicted Price for Custom Input: ₹62,15,000.00


---

## Limitations

- The dataset reflects housing data only up to 2022  
- External factors such as economic trends and interest rates are not included  
- Location encoding may not fully capture locality-specific pricing dynamics  

---

## Future Work

- Integration with live real estate APIs for dynamic predictions  
- Deployment as a web application using Flask or Streamlit  
- Exploration of ensemble or hybrid modeling approaches  
- Incorporation of geospatial features for location-aware predictions  

---

## Contact

- Email: sksanjaykumar010307@gmail.com  
- LinkedIn: https://linkedin.com/in/sanjay-kumar-sakamuri-kamalakar-a67148214  
- ORCID: https://orcid.org/0009-0009-1021-2297  

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
