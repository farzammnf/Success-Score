# ⚽ Success Score: A Data-Driven Metric for Football Performance Evaluation and Match Outcome Prediction

![Project Workflow](Work-Flow.jpg)

## 📌 About This Repository


This repository contains the **code, dataset, and machine learning models** used in our research paper, where we introduce **Success Score**, a novel statistical parameter to measure the quality of a football team. The **Success Score** is calculated as the **sum of expected goals (xG) and actual goals scored** against their opponents and is **scaled to a range of 0 to 10** for easy interpretation.

Our machine learning model is trained using data from **four major European leagues** over four seasons:

🇪🇸 **La Liga**  
🇩🇪 **Bundesliga**  
🇮🇹 **Serie A**  
🏴 **Premier League**  

Additionally, we **tested our model** on **2025 season data**, including 🇫🇷 **Ligue 1**.
---

## 📁 Repository Structure

### 📂 Data
- `Data/` 📊 Contains datasets used for training and testing the model.
  - `Fbref` 📄 extracted data from Fbref.
  - `Sofifa` 🏗️. extracted data from Sofifa.
  - `Molde's data` ⚽  Preprocessed dataset with feature engineering used in our model.

### 📂 Files
- `Pre Process` 📈 Jupyter notebooks for feature engineering and data pre process.
- `Success Score` 📊  Jupyter notebooks for calculation success score and tactical play styles and our model file.
- `Evaluations` 🤖 Script for evaluating model performance.
- `Best Possible Line Up(Problem)` 🛠️ A trial Project for fining best possible line ups using success score.

### 📄 README.md
- 📝 Provides an overview of the project, including methodology and findings.

### 🖼️ Work-Flow.jpg
- 🏗️ Visual representation of the project's workflow.

---

## 📊 Data & Features
We used **two main datasets**, which are available in the `Data/` folder. The features used in our machine learning model include:

- **Team Quality & Prestige**
- **Expected Goals (xG) & Actual Goals**
- **Short-term & Long-term Performance Trends**
- **Match Outcomes (Win/Draw/Loss)**
- **Tactical Playstyles** *(10 main tactics introduced in our paper)*
- **Rolling Averages for Performance Trends**

The dataset is preprocessed with **feature engineering** before being fed into a **fully connected neural network**.

---

## 🛠 Model & Methodology
We trained our model using a **fully connected neural network** on data from **four consecutive seasons (2021-2024)**. The training process involved:

✔ **Data Preprocessing**  
✔ **Feature Engineering (10 Tactical Metrics)**  
✔ **Rolling Averages for Performance Stability**  
✔ **Training with Neural Networks**  

The trained model **predicts the Success Score** for a given match and provides valuable insights into **team performance evaluation, match outcome prediction, and over/underperformance detection**.

---

## 🚀 Applications of Success Score
With the **Success Score**, we introduce several useful applications, including:

🔹 **Identifying Overperforming or Underperforming Teams**  
🔹 **Predicting Match Outcomes (Win/Not Win, Lose/Not Lose)**  
🔹 **Evaluating Team Consistency & Tactical Effectiveness**  

We evaluated our model on **unseen 2025 season data** across **five major leagues**, demonstrating its effectiveness in analyzing and predicting match performances.

---


## 📧 Contact
For any questions, feel free to reach out:  
📩 **Email:** f.manafzadeh@gmail.com
🔗 **GitHub:** [farzammnf](https://github.com/farzammnf)

---

### 🔗 Citation
If you find this work useful, please consider citing our paper:
> 

---

## ⭐ If you like this project, please give it a star! ⭐
