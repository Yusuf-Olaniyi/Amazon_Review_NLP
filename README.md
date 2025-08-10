# Amazon_Review_NLP

This repository contains the analysis of the customer reviews for Amazon food project, implemented in Python.  
It covers dataset loading, preprocessing, and modular solutions for different subtasks.

---

## **Setup Instructions**

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/Amazon_Review_NLP.git
    cd amazon_review
    ```

2. **Create and activate a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate    # Linux/Mac
    venv\Scripts\activate       # Windows
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

---

## **Dataset Sources**

The dataset used in this project is sourced from **[Amazon Fine Food Review on Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)**.  
You should download the dataset and place it inside the `data/` directory before running the scripts.

---

## **Preprocessing Description**

The preprocessing steps include:
- Reading the dataset using **pandas**.
- Handling missing values by dropping or filling them.
- Converting categorical variables to numeric codes.
- Removing stopwords and punctuation from text fields.
- Tokenizing words and counting frequencies using **collections.Counter**.

