
# Phishing_Website_Detection_Using_NLP_and_DL 
#### This project implements an end-to-end text classification pipeline to classify URLs as phishing (0) or legitimate (1) using traditional Deep Learning techniques and clean NLP preprocessing. It includes dataset exploration, preprocessing, TF-IDF vectorization, multiple model training, evaluation, and a production-ready prediction system with model + vectorizer saving.
------------------------------------------------------------------------------------------------------------------------------------------

### Project Overview 
There are some specific objectives for this project, which are as follows:

- To analyze suspicious patterns in the URL.
- To develop a robust model for accurately identifying phishing websites.
- To investigate the accuracy and performance of the proposed model.

### Steps by Step
- Exploratory Data Analysis (EDA)
- Text cleaning and preprocessing
- Lemmatization using WordNetLemmatizer
- Train–test split 80% and 20%
- TF-IDF vectorization on training data only
  
#### Model training:
  - Linear Kernel 
  - RBF Kernel 
  - Polynomial Kernel
  - Sigmoid Kernel &
  - Hybrid Model 
- Evaluation: Accuracy.
- Saving and loading:
  - Trained model
------------------------------------------------------------------------------------------------------------------------------------------

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
