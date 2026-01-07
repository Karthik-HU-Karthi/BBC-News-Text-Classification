# Project Title
## BBC News Text Classification using NLP
# Project Objective

## The objective of this project is to build an end-to-end Natural Language Processing (NLP) pipeline to classify BBC news articles into predefined categories using TF-IDF feature extraction and supervised machine learning models.

##  Dataset

- **Name:** BBC News Classification Dataset  
- **Source:** Kaggle  
- **Type:** Multi-class text classification  

### Classes:
- Business  
- Entertainment  
- Politics  
- Sport  
- Tech  

### File Details:
- **Format:** CSV  
- **Columns:**
  - `text` – News article content  
  - `category` – Target class label  

The dataset is stored in the `data/` directory for reproducibility.

##  Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**
  - pandas, numpy
  - nltk
  - scikit-learn
  - matplotlib, seaborn
  - Jupyter Notebook



## ⚙️ Methodology

1. **Data Loading & Exploration**
   - Loaded the BBC News dataset
   - Analyzed class distribution and missing values

2. **Text Preprocessing**
   - Lowercasing text
   - Removing punctuation and numbers
   - Stopword removal
   - Lemmatization

3. **Feature Engineering**
   - Converted text into numerical features using TF-IDF
   - Used unigrams and bigrams

4. **Model Training**
   - Multinomial Naive Bayes
   - Logistic Regression
   - Support Vector Machine (LinearSVC)

5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

##  Results

| Model | Accuracy |
|------|---------|
| Naive Bayes | ~96% |
| Logistic Regression | ~97% |
| Support Vector Machine (SVM) | ~98% |

The Support Vector Machine (LinearSVC) achieved the best performance and was selected as the final model.

##  How to Run the Project

 Clone the repository:
   ```bash
   git clone https://github.com/your-username/BBC-News-Text-Classification.git

   Navigate to the project directory:
   cd BBC-News-Text-Classification
Install dependencies:
      pip install -r requirements.txt
jupyter notebook

---

# Author

```markdown
##  Author

**Karthik Kumar Honnapura Umashankar**  
Machine Learning | Natural Language Processing | Data Science

