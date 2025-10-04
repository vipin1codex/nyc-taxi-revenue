# Maximizing the Revenue of Taxi Drivers

This project analyzes **NYC Yellow Taxi 2020 Trip Data** to explore how **different payment methods** impact **fare amount** and **trip distance**, aiming to identify strategies that can help **maximize taxi drivers' revenue**.

---

## 📑 Table of Contents
- [Project Overview](#Project-Overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Results and Visualizations](#results-and-visualizations)
- [Author](#author)

---

## 📌 Project Overview:
Taxi drivers' income can be influenced by various factors like **payment methods**, **fare amounts**, and **trip distances**.  
In this project, we:
- Analyze the relationship between **payment types** and **fare amount/trip distance**.
- Identify which payment methods are linked to **higher revenues**.
- Provide insights that can help drivers and taxi companies **optimize earnings**.

---

## 📂 Dataset
- **Name:** 2020_Yellow_Taxi_Trip_Data  
- **Source:** [Kaggle](https://www.kaggle.com/)  
- **Description:**  
  The dataset contains detailed trip-level records including:
  - Pickup & Drop-off timestamps  
  - Trip distance  
  - Fare amount  
  - Payment types (Cash, Card, etc.)  
  - Additional charges and taxes  

---

## ⚙️ Technologies Used
The project is implemented using Python with the following libraries:

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
import scipy.stats as st
