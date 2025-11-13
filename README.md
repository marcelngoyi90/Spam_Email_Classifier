# Spam_Email_Classifier
A machine learning project that classifies emails as **spam** or **ham (not spam)** using Natural Language Processing (NLP) and a **Naive Bayes** classifier.   The project includes a dataset (`emails.csv`), exploratory analysis, preprocessing, model training, and evaluation.

## Dataset

This repository **includes the dataset** used to train and test the model:

- **emails.csv**
- Columns:
  - `text` → the email message
  - `spam` → label  
    - **1 = spam**  
    - **0 = ham**

The dataset is provided for learning and demonstration purposes.

---

## Project Overview

This project demonstrates a complete text-classification workflow:

- Load and explore a dataset of email messages  
- Visualize spam vs ham distribution  
- Convert text to numerical features (Bag-of-Words)  
- Train a **Multinomial Naive Bayes** classifier  
- Evaluate performance using confusion matrices and classification metrics  

The project is implemented in a Jupyter Notebook for clear step-by-step explanation.

---

##  Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

##  Methodology

### **1. Exploratory Data Analysis**
- View basic statistics  
- Check dataset shape and structure  
- Calculate spam/ham percentages  

### **2. Preprocessing & Vectorization**
- Convert raw email text into numerical features  
- Use **CountVectorizer** (Bag-of-Words)  
- Train/test split for evaluation

### **3. Model Training**
- Train a **Multinomial Naive Bayes** classifier  
- Predict on training and test sets  

### **4. Evaluation**
- Confusion matrix heatmaps  
- Accuracy  
- Precision, Recall, F1-Score  
