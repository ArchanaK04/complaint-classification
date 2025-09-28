# Consumer Complaint Text Classification (Task 5)

This project demonstrates a **text classification pipeline** on the [Consumer Complaint Dataset](https://catalog.data.gov/dataset/consumer-complaint-database).  
The goal is to classify consumer complaints into one of the following categories:

- **0** → Credit reporting, repair, or other  
- **1** → Debt collection  
- **2** → Consumer Loan  
- **3** → Mortgage  

## Project Steps
1. **Exploratory Data Analysis (EDA) & Feature Engineering**  
   - Load and inspect the dataset  
   - Analyze class distribution and text length  
   - Handle missing values and balance dataset  

2. **Text Preprocessing**  
   - Tokenization, stopword removal, lemmatization  
   - Lowercasing and punctuation removal  
   - Transform text into numerical features (TF-IDF / CountVectorizer)  

3. **Model Selection for Multi-Class Classification**  
   - Logistic Regression  
   - Naïve Bayes  
   - Support Vector Machine (SVM)  
   - Random Forest / Gradient Boosting  

4. **Model Comparison**  
   - Compare models using accuracy, precision, recall, and F1-score  

5. **Model Evaluation**  
   - Confusion Matrix & Classification Report  
   - Cross-validation performance  
   - Visualization of results  

6. **Prediction**  
   - Test model on unseen complaint text  
   - Generate predicted category  

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/ArchanaK04/complaint-classification.git
cd complaint-classification
