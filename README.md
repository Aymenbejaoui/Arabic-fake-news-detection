# Arabic-fake-news-detection
Text classification (real or undecided news) with NLP Technics and machine learning algorithms.


Setup 1 : The dataset is downloaded via the API link from Kaggle dataset.
Link of AFND dataset : https://www.kaggle.com/datasets/murtadhayaseen/arabic-fake-news-dataset-afnd.
(Setups are more detailed in the ipynb file) 


Setup 2 : Data preparation 
*Opening and transforming json file into dataframes.
*Parsing the articles and their sources. 
*Function to Concat all sources into one dataframe. exp : concat(1,20) will concat the first 20 sources.
*Text processing ( remove punctuations ,stopwords , stemming, normalizing words ...)

Setup 3 : Vectorization of text and encoding the labels
*TF-IDF  used to reveal the real importance of a word.
*Transform labels (Fake or undecided) into numeric numbers because the ML model interpret classes as number or dummies.


Setup 4 : Machine learning approach 
* Shuffle the data : Very important step to make data points random and indepandant and  helps  avoid overfitting.
* Call machine learning algorithms and metrics for evaluation.
