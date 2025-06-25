# 🏠 Chennai Housing Price Prediction using XGBoost

> _A machine learning pipeline to predict housing prices in Chennai using gradient boosting techniques._

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)  
[![XGBoost](https://img.shields.io/badge/Model-XGBoost-success?logo=fastapi)](https://xgboost.readthedocs.io/en/stable/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📌 Overview

This project builds an end-to-end regression model to **predict real estate prices in Chennai** based on various property features such as area, locality, number of rooms, and amenities. It uses the **XGBoost** algorithm to achieve high predictive accuracy and interpretability, visualizing key drivers of price fluctuations.

> ✅ Created as part of a personal machine learning portfolio to demonstrate regression workflows and model deployment readiness.

---

## 🚀 Highlights

- ✅ Preprocessing pipeline with null handling, encoding, and scaling  
- 🧠 Model training using **XGBoost Regressor**  
- 📈 Evaluation metrics (MSE, R²) and **feature importance visualization**  
- 🔮 Supports custom input prediction for unseen properties  
- 🧪 Built entirely in a **Colab / Jupyter Notebook** environment

---

## 📂 File Structure

```
chennai-housing-xgboost/
│
├── main.ipynb                # All data processing, modeling, and visual output
├── Chennai housing sale.csv  # Original dataset from Kaggle
├── requirements.txt          # Required libraries
├── feature_graph.png         # Bar plot showing most influential features
└── README.md                 # Project documentation
```

---

## 📊 Dataset Info

- 📄 **Source**: [Kaggle - Chennai Housing Prices](https://www.kaggle.com/datasets/kunwarakash/chennai-housing-sales-price)  
- 🏷️ **Columns**: Area type, location, square footage, BHK, amenities, sale price, etc.  
- 📅 **Note**: Dataset was last updated in 2022 and may not reflect current prices

---

## 🛠️ Setup Instructions

### 👉 Run on Google Colab (Recommended)
- Open `main.ipynb` in [Google Colab](https://colab.research.google.com/)
- Upload the `Chennai housing sale.csv` file when prompted
- Run all cells

### 💻 Run Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/Sanjaykumar030/Chennai-Housing-Model.git
    cd Chennai-Housing-Model
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Launch Jupyter:
    ```bash
    jupyter notebook
    ```
4. Open `main.ipynb` and run all cells

---

## 🔁 Workflow Overview

| Step                | Description                                               |
|---------------------|----------------------------------------------------------|
| 🔍 Data Exploration | Load and inspect features & distributions                 |
| 🧹 Cleaning         | Handle missing values, drop noisy or unused columns       |
| 🔄 Encoding         | Convert categorical variables to numerical format         |
| 📏 Scaling          | Apply standard scaling to continuous variables           |
| 🧠 Model Training   | Train an XGBoost Regressor on cleaned data               |
| 📈 Evaluation       | Report MSE, R², and plot predicted vs actual prices      |
| 🔮 Prediction Util. | Manually input a new house’s specs to estimate price     |
| 📊 Feature Import.  | Visualize top factors influencing model decisions        |

---

## 📌 Sample Output

```
Mean Squared Error: 4,825,614.23
R² Score: 0.9945

Predicted Price for Custom Input: ₹62,15,000.00
```

<img src="feature_graph.png" width="600"/>

---

## ⚠️ Limitations

- 📆 The model is trained on data up to 2022; predictions may not reflect 2025 market conditions
- 🌍 Does not include economic trends, interest rates, or external market factors
- 🏷️ Location encoding may flatten locality-wise price variation

---

## 💡 Future Improvements

- Integrate live real estate APIs for dynamic pricing
- Deploy as a web app using Flask or Streamlit
- Explore ensemble models for robustness
- Add geospatial data and map-based pricing insights

---

## 📬 Contact

Feel free to reach out to me:

- 📧 Email: sksanjaykumar010307@gmail.com
- 🔗 LinkedIn: [linkedin.com/in/sanjay-kumar-sakamuri-kamalakar-a67148214](https://linkedin.com/in/sanjay-kumar-sakamuri-kamalakar-a67148214)
- 🧪 ORCID: [https://orcid.org/0009-0009-1021-2297](https://orcid.org/0009-0009-1021-2297)

---

## 📄 License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for full details.

