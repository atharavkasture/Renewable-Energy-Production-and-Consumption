# Renewable Energy Production and Consumption Analysis

> **Note:** This repository contains the Jupyter Notebook (`.ipynb`)  

---

## 📖 Table of Contents

1. [Project Overview](#project-overview)  
2. [Authors](#authors)  
3. [Repository Structure](#repository-structure)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
5. [Usage](#usage)  
6. [Methodology Summary](#methodology-summary)  
7. [Results & Discussion](#results--discussion)  
8. [References](#references)  
 

---

## Project Overview

This project investigates and compares six classification models (Logistic Regression, K‑Nearest Neighbors, Support Vector Machine, Decision Tree, Random Forest, LSTM) and four regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor, LSTM Regressor) on renewable energy datasets, as well as ARIMA time‑series forecasting and Multi‑Criteria Decision‑Making methods (TOPSIS, MOORA, AHP‑TOPSIS, AHP‑MOORA). The goal is to provide actionable insights for selecting appropriate forecasting systems for sustainable power grid integration and planning.

---

## Authors

- **Sangita Jaybhaye** — sangita.jaybhaye@vit.edu  
- **Ameya Kasetwar** — ameya.kasetwar23@vit.edu  
- **Kaustubh Karne** — kaustubh.karne23@vit.edu  
- **Atharav Kasture** — atharav.kasture23@vit.edu  
- **Kartik Mehta** — kartik.mehta23@vit.edu  

---

## Repository Structure

├── README.md

├── Renewable_Energy_Analysis.ipynb # Main Jupyter Notebook

├── data/

│ ├── solar.csv

│ ├── wind.csv

│ ├── hydro.csv

│ └── consumption.csv

├── requirements.txt # Python dependencies

└── figures/

├── workflow.png

├── model_performance.png

└── time_series_forecast.png



---

## Getting Started

### Prerequisites

- **Python 3.8+**  
- **Jupyter Notebook** or **JupyterLab**  
- **pip** (package installer)

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your‑username>/renewable‑energy‑analysis.git
   cd renewable‑energy‑analysis
   
2. Create a virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

---

## Usage
Launch Jupyter Notebook
jupyter notebook Renewable_Energy_Analysis.ipynb
Execute cells in order to reproduce data preprocessing, model training, evaluation, and visualization.

---

## Methodology Summary
Data Acquisition & Preprocessing

Combined and balanced solar, wind, and hydro datasets (∼180K entries).

Preprocessed consumption data (1985–2024).

### Classification Models

Logistic Regression, Decision Tree, Random Forest, KNN, SVM, LSTM.

### Regression Models

Linear Regression, Decision Tree Regressor, Random Forest Regressor, LSTM Regressor.

### Time‑Series Forecasting

ARIMA(1,1,1) for 3‑month renewable consumption forecast.

### Multi‑Criteria Decision‑Making

TOPSIS, MOORA, AHP‑TOPSIS, AHP‑MOORA for site suitability ranking.

---

## Results & Discussion
Classification: Random Forest achieved highest multiclass accuracy (99.58 %) and binary potential prediction (99.13 %).

Regression: Random Forest Regressor led with R² ≈ 0.98.

Time Series: Forecast shows growth from 712 to 735 units over the next quarter (95 % CI ± 22–25).

MCDM: Hybrid AHP‐TOPSIS and AHP‐MOORA rankings remained stable across weighting schemes.

---

## References
Please refer to the end of Energy_Production_Consumption_Analysis.pdf and the notebook for a complete list of references. Key citations include:

D. Kumar et al., “Analysis of Multi‑Renewable Energy Potential Sites in India …” 

S. Kumar and R. Singh, “Renewable Energy Prediction: A Comparative Study of Deep Learning Models …”
