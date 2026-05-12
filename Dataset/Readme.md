# Phishing_Website_Detection_Using_NLP_and_DL 
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
