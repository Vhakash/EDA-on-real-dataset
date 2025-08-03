# Exploratory Data Analysis (EDA) on a Brazilian E-Commerce Dataset

## 📖 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Brazilian E-Commerce Public Dataset by Olist. The primary goal is to dive deep into the data to uncover patterns, identify trends, and extract actionable insights related to customer behavior, product popularity, and logistical efficiency.

This repository documents the entire process, from data loading and cleaning to visualization and interpretation, serving as a practical guide for conducting EDA on a complex, multi-table real-world dataset.

---

## 🎯 Key Objectives & Questions Answered

The analysis is driven by key business questions to provide a clear focus. This EDA seeks to answer:

#### Customer-Centric Insights:
* What is the geographical distribution of customers across Brazil?
* What is the trend of customer acquisition over time?

#### Product & Category Insights:
* What are the top-selling product categories?
* How are product prices distributed? Is there a relationship between product characteristics (like photo quantity) and sales?

#### Order & Logistics Insights:
* What are the busiest times of day, days of the week, and months for placing orders?
* Which payment methods are most popular among customers?
* How does the actual delivery time compare to the estimated delivery time? Are there significant delays?

---

## 📊 Dataset

The dataset used is the **Brazilian E-Commerce Public Dataset by Olist**, sourced from Kaggle. It is a relational dataset comprised of multiple `.csv` files, providing a holistic view of the e-commerce operations.

-   **Source:** [Kaggle - Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

**Note:** The raw data files are not included in this repository due to their size. Please download them from the source link above and place them in a `data` sub-directory to run the analysis notebook.

---

## 🛠️ Technologies & Libraries Used

* **Language:** Python 3.x
* **Core Libraries:**
    * `pandas` for data manipulation and merging.
    * `numpy` for numerical operations.
* **Visualization Libraries:**
    * `matplotlib` for foundational plotting.
    * `seaborn` for creating visually appealing statistical graphics.
* **Environment:**
    * `Jupyter Notebook` for interactive analysis and documentation.

---

## 🚀 How to Run This Project

To replicate this analysis on your local machine, please follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Vhakash/EDA-on-real-dataset.git](https://github.com/Vhakash/EDA-on-real-dataset.git)
    cd EDA-on-real-dataset
    ```

2.  **Set Up a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file by running `pip freeze > requirements.txt` in your local environment after installing the libraries mentioned above.)*

4.  **Download the Data:**
    * Download the dataset from the [Kaggle link](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
    * Unzip the files and place all `.csv` files into a `data/` folder within the project directory.

5.  **Launch the Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the main analysis notebook (`.ipynb` file) and run the cells sequentially.

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details on what this entails.
