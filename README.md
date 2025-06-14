# KikkaBoo Demand Forecasting Model

> A predictive inventory model for baby strollers based on real-world sales data from 2023 to 2025.

This project is a personal data science initiative aimed at helping **KikkaBoo** improve inventory planning by forecasting stroller demand. 

---

## 🧠 Project Goals

- Forecast monthly demand for baby strollers.
- Avoid out-of-stock situations for fast-selling products.
- Based on some inputs like average last three months sale, current quantities, etc. -> the model to give a number to be ordered 

---

## 📊 Data Used: 2 Datasets

- **Sales Data**: Transactions (Invoices) from 01.01.2023 to 01.01.2025.
- **Product Details**: Includes SKU, name, weight, price, and manufacturer info.


---

## 🔁 Iterative Approach

| Iteration | Description |
|----------|-------------|
| **0**     | Baseline model with binary output (Buy / Don't Buy). Uses only past sales data. |
| **1**     | Forecasting per-product demand for the next 3–6 months. |
| **2**     | Includes current stock levels and estimates surplus/deficit. |
| **3**     | Adds seasonality, trends, and promotion effects. |
| **4**     | Final model — generates quantity recommendations with confidence intervals. |

---

## 🛠️ Tech Stack

- **Python 3.11**
- **pandas / numpy**
- **scikit-learn**
- **matplotlib / seaborn**
- **Jupyter Notebook**

---

## 🧪 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/kikkaboo-demand-forecast.git
   cd kikkaboo-demand-forecast
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
