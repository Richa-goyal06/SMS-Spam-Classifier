# SMS-Spam-Classifier

This Project is done using Natural Language Processing (NLP) Techniques. Python libraries like Pandas (for Data Cleaning/Handling), NLTK, TextBlob, Scikit-learn (for text preprocessing) and Naive Bayes (for model building)
## Dataset 
- <a href="https://github.com/Richa-goyal06/SMS-Spam-Classifier/blob/main/spam.csv">Dataset</a>

## Pipeline
1.Exploratory Data Analysis (EDA)

-Performed EDA using Matplotlib and Seaborn

-Created new features such as:

     -Number of characters in each message
     
     -Word count and sentence length
     
-Visualized data using:

     -Histograms and distribution plots
     
     -Pair plots to analyze relationships between features
     
     -Heatmap to identify correlations among numerical features.

2. Applied text preprocessing: lower casing, tokenization, stopword removal, and performed stemming to reduce words to root form using NLTK.
   
3. Generated WordClouds to identify frequently occurring words in spam and non-spam messeges.
   
4. Converted text into numerical features using Bag-of-Words and TF-IDF.
   
5. Trained multiple Naive Bayes models: Gaussian NB, Multinomial NB, Bernoulli NB.
   
6. Compared models based on accuracy and precision
   
   -Best Model: TF-IDF + Multinomial Naive Bayes
   
   -Achieved: Accuracy: 95% and Precision: 1.00 


    -Using TF-IDF vectorization.
    
Final model achieved 89% accuracy on test data.
