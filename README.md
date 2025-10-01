# Michelle's Portfolio
Welcome to my data portfolio! Here, I document a summary of projects I have done.

---
  
## 📑 Table of Contents
- [Natural Language Processing](#-natural-language-processing)
- [Machine Learning](#-machine-learning)
- [Time Series](#-time-series)
- [Bayesian Inference](#-bayesian-inference)
- [Business Intelligence](#-business-intelligence)
- [Recommender Systems](#-recommender-systems)
- [Deep Learning And Computer Vision](#-deep-learning-and-computer-vision)

  
---

## 🧠 Natural Language Processing
| Project Link | Area | Project Description | Libraries |
|--------------|------|----------------------|-----------|
| 🌾 [PSA Translation — English→Swahili](https://github.com/michellekituku/PSA-Translation) | NLP | Built a MarianMT pipeline to translate agricultural PSAs to Swahili; fine-tuned on domain data. BLEU ≈ 61. | `transformers`, `torch`, `datasets`, `seaborn` |
|🔡 [Exploring Language Modeling with N-Gram Sizes & Smoothing](https://github.com/michellekituku/NGram-Language-Modeling) | NLP | Implemented n-gram language models (unigram, bigram) with Laplace, Good-Turing, and Kneser-Ney smoothing. Evaluated using cross-validation and perplexity. Visualized performance trade-offs across methods. | `nltk`, `pandas`, `numpy`, `matplotlib`, `seaborn` |

---

## 🤖 Machine Learning
| Project Link | Area | Project Description | Libraries |
|--------------|------|----------------------|-----------|
| 🩺 [Breast Cancer Classification with Logistic Regression](https://github.com/michellekituku/Breast-Cancer-LogReg) | Classification | Built a logistic regression classifier on the Breast Cancer dataset. Compared effects of regularization (C) on accuracy and coefficients. Achieved >95% test accuracy. Visualized coefficient importance across features. | `scikit-learn`, `pandas`, `matplotlib`, `seaborn` |
| 🏦 [Loan Approval Prediction](https://github.com/michellekituku/Loan-Approval-Prediction) | Classification | Built a classification model to predict whether a loan application will be approved based on applicant details. Compared Logistic Regression, Random Forest, and XGBoost with accuracy & ROC-AUC metrics. | `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn` |

---

## 📈 Time Series
| Project Link | Area | Project Description | Libraries |
|--------------|------|----------------------|-----------|
| 📊 [Retail Sales Forecasting](https://github.com/michellekituku/Retail-Sales-Forecasting) | Time Series Forecasting / Retail Analytics | Generated synthetic 2024 sales data based on 2023 data. Performed decomposition, stationarity testing, and forecasted daily sales using ARIMA, SARIMA, and Holt-Winters. Evaluated models with RMSE/MAE and visualized trends, seasonality, and forecasts. | `tidyverse`, `lubridate`, `forecast`, `tseries`, `ggplot2` |

---

## 🤖 Bayesian Inference

| Project Link | Area | Project Description | Libraries |
|--------------|------|-------------------|-----------|
| 🌆 [Bayesian King County House Sales](https://github.com/michellekituku/Bayesian-Inference) | Bayesian Regression / Housing | Applied Bayesian linear regression to predict house prices using `sqft_living`, `bedrooms`, `bathrooms`, `grade`, and `condition`. Estimated posterior distributions, performed MCMC diagnostics, and generated 95% credible intervals for predictions. | `tidyverse`, `rstanarm`, `bayesplot`, `coda`, `readr` |

---

## 📊 Business Intelligence 

| Project Link | Area | Project Description | Libraries |
|--------------|------|-------------------|-----------|
| 🏢 [BI Maturity & Dashboard for SME](https://github.com/yourusername/BI-Maturity-Dashboard-SME) | Business Intelligence / Dashboard | Assessed BI maturity and developed an interactive dashboard for a SME. Analyzed rent collection, occupancy, tenant behavior, complaints, and retention. Generated actionable insights to optimize revenue and improve services. | `tidyverse`, `lubridate`, `ggplot2`, `plotly`, `shiny`, `readr` |
