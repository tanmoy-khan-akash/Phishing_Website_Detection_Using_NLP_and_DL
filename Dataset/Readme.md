
# Phishing_Website_Detection_Using_NLP_and_DL 
#### This project implements an end-to-end text classification pipeline to classify URLs as phishing (0) or legitimate (1) using traditional Deep Learning techniques and clean NLP preprocessing. It includes dataset exploration, preprocessing, TF-IDF vectorization, multiple model training, evaluation, and a production-ready prediction system with model + vectorizer saving.
------------------------------------------------------------------------------------------------------------------------------------------

### Steps by Step Dataset Overview 

### Dataset
[The dataset](https://github.com/tanmoy-khan-akash/Phishing_Website_Detection_Using_NLP_-_DL/blob/main/Dataset/phishing_dataset.csv) contains three columns:

| Column | Description |
|--------|-------------|
| `title` | Small title |
| `URL` | Raw url content |
| `---` | --------- |
| `---` | --------- |
| `label` | 0 = phishing, 1 = legitimate |

#### The dataset was cleaned, null values replaced, and text normalized.
------------------------------------------------------------------------------------------------------------------------------------------

### Text Preprocessing Steps
1. Remove punctuation  
2. Remove stopwords  
3. Convert text to lowercase  
4. Tokenize  
5. Lemmatize each token  
6. Reconstruct cleaned text

#### This ensures the model trains on high-quality and normalized input.
------------------------------------------------------------------------------------------------------------------------------------------

### Model Training
Four models were trained and evaluated:
- **Linear Kernel**
- **RBF Kernel**
- **Polynomial Kernel**
- **Sigmoid Kernel**
- **Hybrid Model**
- **Linear Kernel** ← Best performing
------------------------------------------------------------------------------------------------------------------------------------------

### Best Model

#### **Linear Kernel** achieved the highest performance.  
#### This model was selected for production use.
------------------------------------------------------------------------------------------------------------------------------------------

### Model Saving

#### The trained Linear Kernel model is saved.
------------------------------------------------------------------------------------------------------------------------------------------
