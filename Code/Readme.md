# Phishing_Website_Detection_Using_NLP_and_DL 
------------------------------------------------------------------------------------------------------------------------------------------

### Code Overview 

### Steps
- Exploratory Data Analysis (EDA)
- Text cleaning and preprocessing
- Lemmatization using WordNetLemmatizer
- Train–test split 80% and 20%
- TF-IDF vectorization on training data only
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
