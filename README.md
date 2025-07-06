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
### Data Acquisition & Preprocessing

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

1. S. Bose and S. Sarkar, “Assessment of clean energy transition potential in major power-producing states of India using multi‑criteria decision analysis,” *Sustainability*, vol. 14, no. 3, p. 1166, 2022. DOI: 10.3390/su14031166 

2. M. Kumar, R. P. Saini, and M. P. Sharma, “Analysis of multi‑renewable energy potential sites in India using spatial characteristics: A GIS and hybrid MCDM approach,” *Energy, Ecology and Environment*, vol. 9, pp. 1–18, 2024. DOI: 10.1007/s41660‑024‑00441‑3 

3. S. Kumar and R. Singh, “Renewable energy prediction: A comparative study of deep learning models for complex dataset analysis,” *arXiv preprint*, arXiv:2501.15731, 2024. 

4. M. Tufail and S. Ahmad, “Predicting energy production in renewable energy power plants using deep learning,” *Procedia Computer Science*, vol. 170, pp. 626–633, 2020. DOI: 10.1016/j.procs.2020.03.142 

5. S. Ghimire and Y. Kim, “Forecasting solar energy production using machine learning,” *Energies*, vol. 11, no. 7, p. 1825, 2018. DOI: 10.3390/en11071825 

6. H. Almazrouei and A. Alshamsi, “Energy consumption prediction by using machine learning,” *Materials Today: Proceedings*, vol. 45, pp. 5686–5691, 2020. DOI: 10.1016/j.matpr.2020.11.110 

7. M. A. Al Mamun and M. S. I. Sohel, “Renewable energy consumption forecasting using machine learning models,” *Energies*, vol. 14, no. 14, p. 4171, 2021. DOI: 10.3390/en14144171 

