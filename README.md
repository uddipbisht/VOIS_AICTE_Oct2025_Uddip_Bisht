# Airbnb Booking Analysis - VOIS AICTE Internship Project

An exploratory data analysis (EDA) of the New York City Airbnb Open Data dataset. This project was completed as part of the "Conversational Data Analytics with LLMs" internship program by Edunet Foundation, in collaboration with VOIS and Vodafone Idea Foundation.

## 📋 Project Overview

The goal of this project is to analyze the Airbnb dataset to uncover key insights into booking patterns, pricing strategies, host performance, and guest preferences. By using Python's data science libraries, we can identify trends and relationships that provide valuable information for hosts, guests, and the Airbnb platform itself.

---

## 🔍 Key Questions Answered

This analysis delves into the data to answer several key questions:
- What are the most common property types available?
- Which neighborhood groups have the most listings?
- How do average prices vary across different neighborhood groups?
- Is there a relationship between property construction year and price?
- Who are the top 10 hosts with the most listings?
- Does host identity verification impact guest review scores?
- What is the correlation between the listing price and the service fee?
- How do review rates vary by room type and neighborhood?

---

## 🛠️ Tools and Libraries Used

* **Language:** Python 3.x
* **Libraries:**
    * **Pandas:** For data manipulation and cleaning.
    * **NumPy:** For numerical operations.
    * **Matplotlib & Seaborn:** For data visualization.
* **Environment:** Google Colab / Jupyter Notebook

---

## 🚀 How to Run this Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/uddipbisht/VOIS_AICTE_Oct2025_Uddip_Bisht.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd VOIS_AICTE_OCT2025_Uddip_Bisht
    ```
3.  **Ensure you have the dataset** (`1730285881-Airbnb_Open_Data.xlsx`) in the same folder.
4.  **Open and run the Jupyter Notebook** (`YourNotebookName.ipynb`) in an environment with the required libraries installed.

---

## 📊 Summary of Findings

* **Property & Location:** `Entire home/apt` is the most common listing type. **Manhattan** and **Brooklyn** are the clear leaders in the number of listings.
* **Pricing:** There is a near-perfect positive correlation between `price` and `service_fee`. Surprisingly, **Queens** has the highest average listing price despite having fewer listings than Manhattan or Brooklyn.
* **Host Performance:** A few hosts manage a very large number of properties, indicating a professionalized market. Host verification status shows no significant impact on guest review scores.
* **Guest Satisfaction:** Review scores are fairly consistent across all locations and room types, typically averaging around **3 out of 5**.

---

## 👨‍💻 Author

* **Name:** UDDIP BISHT
* **Internship ID:**  INTERNSHIP_17546440516895be537820f
