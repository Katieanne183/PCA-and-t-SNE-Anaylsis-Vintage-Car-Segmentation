# 🚗PCA-and-t-SNE-Anaylsis-Vintage-Car-Segmentation

## 📋 Project Overview
This project applies **dimensionality reduction techniques**—**Principal Component Analysis (PCA)** and **t-Distributed Stochastic Neighbor Embedding (t-SNE)**—to analyze the **Auto MPG dataset** for a fictional vintage car dealership, **SecondLife**.

The analysis identifies distinct groups of vintage cars, enabling targeted marketing strategies and optimized procurement decisions.

---

## 🎯 Business Objective
SecondLife aims to segment its vintage car inventory based on vehicle features to:
- Target marketing campaigns to specific customer groups
- Optimize vehicle procurement and inventory management
- Enhance operational efficiency

---

## 📊 Dataset Information
The dataset includes **398 vintage cars** with the following features:

| Feature       | Description                                           |
|---------------|-------------------------------------------------------|
| mpg           | Miles per gallon (fuel efficiency)                    |
| cylinders     | Number of cylinders                                   |
| displacement  | Engine displacement (cu. inches)                      |
| horsepower    | Horsepower                                            |
| weight        | Vehicle weight (lbs.)                                 |
| acceleration  | Acceleration (0 to 60 mph time in seconds)            |
| model year    | Model year                                            |
| car name      | Car model name                                        |

---

## 🛠️ Methods Used
- **Data Cleaning:**  
  - Removed `car name` column (not useful for numerical analysis).
  - Handled missing values in `horsepower` by imputing median values.
  - Converted all relevant columns to numeric types.

- **Exploratory Data Analysis (EDA):**  
  - Summary statistics and correlation analysis revealed key relationships between features (e.g., negative correlation between MPG and engine size).

- **Dimensionality Reduction:**  
  - **PCA** reduced dimensionality while preserving variance:
    - **PC1:** Captured size & power attributes.
    - **PC2:** Captured acceleration and model year effects.
    - **PC3:** Captured model year and other characteristics.
  - **t-SNE** provided visual clusters of cars based on feature similarity.

---

## 🔍 Key Findings
Three distinct car segments were identified:

1. **Group 1:**  
   Small, fuel-efficient cars with fewer cylinders  
   *Target audience:* Practical, eco-conscious buyers.

2. **Group**
