
# 📈 Netflix Stock Prediction Dashboard

This repository contains a data science and machine learning project built with R and Shiny to predict Netflix stock prices based on historical trends. Developed as part of an academic submission at FAST National University (CFD Campus), the project aims to deliver analytical insights and forecasting capabilities for the highly dynamic Netflix stock.

---

## Live On

Project Deploy on HuggFace space.
[Live](https://huggingface.co/spaces/mahmad92/netflix-stock-prediction)

---

## 🎯 Project Objective

Predict the future stock prices of Netflix (NFLX) using historical data and regression-based machine learning models. The goal is to support investors and analysts in making informed decisions.

---

## 🧠 Core Features

- 📊 **Data Exploration**  
  View the dataset structure, descriptive summaries, and exploratory plots for key metrics like opening, closing, high, low, and volume.

- 📉 **Visual Analytics**  
  - Line charts to visualize daily price trends over different time frames (full, 365 days, 30 days)  
  - Scatter plots with regression smoothing  
  - Boxplots of closing prices  
  - Histograms of trading volume  

- 🔍 **Statistical Modeling**  
  - Linear regression model to predict closing prices based on opening values  
  - Confidence intervals for both descriptive statistics and regression estimates  
  - Normal distribution assessment of volume data  

- 📦 **Interactive Dashboard**  
  Built using R’s Shiny framework, the app provides an intuitive interface for exploring data, running predictions, and visualizing trends in real time.

---

## 📁 Dataset

- **Source**: Kaggle  
- **Period**: January 2011 – December 2021  
- **Observations**: 2,769 rows  
- **Features**: Date, Open, High, Low, Close, Volume

---

## 🛠️ Technologies Used

- `R`  
- `Shiny` & `shinydashboard`  
- `ggplot2` & `plotly`  
- `dplyr`, `lubridate`, `skimr`  
- Machine Learning via base R’s `lm()`  

---

## 🚀 How to Run

1. Clone this repository  
2. Make sure the dataset `NFLX.csv` is in the project directory  
3. Run `shiny::runApp()` in RStudio  

---

## 📌 Team Members

- Asjid Ali – 21F-9137  
- M. Ahmad – 21F-9195  
- M. Umar – 21F-9291  
- Sultan Arfeen – 20F-0337  

---

## 📬 Feedback & Contribution

Contributions, suggestions, and feedback are welcome! Feel free to fork, raise an issue, or start a discussion.

