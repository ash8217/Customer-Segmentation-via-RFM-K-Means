# Customer Segmentation

## Overview
This project focuses on **customer segmentation** using the **RFM method** combined with **K-Means clustering**.  
The dataset includes retail sales data spanning three years, sourced from Kaggle.  
Two approaches to segmentation were implemented:

1. **RFM scoring (assigned RFM score) + K-Means clustering**  
2. **Raw RFM variables + K-Means clustering**

---

## Dataset
- The dataset contains **sample sales data** based on retail analytics.  
- Covers **three years of sales history**.  
- Source: [Kaggle](https://www.kaggle.com/)  

---

## Motivation
Customer segmentation is an effective method for understanding clients and addressing their varied needs.  
Almost every company storing purchase data can leverage it to:  
- Execute customer segmentation  
- Design **personalized marketing campaigns**  
- **Increase sales performance**  

One of the most widely used approaches is **RFM analysis**, which helps design special offers tailored to customer behavior.

### RFM Method
RFM stands for **Recency, Frequency, Monetary Value**, and segments customers based on transaction history:

- **Recency** – Days since the customer’s last purchase/order  
- **Frequency** – Total number of purchases made by the customer  
- **Monetary Value** – Total money the customer spent per order  

---

## Project Contents
- **Part 1**: First approach – `Customer_segmentation.ipynb`  
- **Part 2**: Second approach – `Segmentation_Kmeans.ipynb`  
- **Python Script**: `customers_segments.py`  

---

## Technologies
- **Python 3.6**  
- Libraries: `pandas`, `numpy`, `sklearn`, `scipy`, `seaborn`, `matplotlib`  

---

## Running the Project
You can run this project using **Jupyter Notebook** or **Google Colab**.  

Alternatively, run the script in the terminal:  
```bash
python customers_segments.py
