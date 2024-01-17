# Sentiment Analysis Project

## Step 1: Gathering Data
   - I can get three Dataset each dataset one col uis common review i can extract the revoew col and make a new dataframe and working on this new datafrane.
## Step 2: Get the Sentiment of Each Review
   - Use a sentiment analysis NlTK the nost popular natural language processing to get the sentiment of each review .

## Step 3: Convert Sentiment to Positive, Negative, or Neutral
   - Convert the  sentiment scores into distinct classes, such as Positive, Negative, or Neutral, based on a threshold.

## Step 4: Data Preprocessing
   - Perform essential text preprocessing steps:
      - Remove stop words.
      - Remove punctuation.
      - Stem the words.
      - Convert text to vector.

## Step 5: Split the Data into Training and Testing Sets
   - Divide your dataset into two subsets: one for training the model and the other for testing its performance.

## Step 6: Balance the Data
   - Data should be completle unbLnace so we can balance the data uisng imblearn library.
## Step 7: Train the Model
   - Train on three different models.
       - Logistic Regression
       - SVC
       - MultiNaivebase

## Step 8: Test the Model
   - Evaluate the trained model on the testing dataset to assess its performance metrics, such as accuracy, and also find the cross val score.

## Overall Performance
  - Over all Logistic Regression is perform best so we chose the Logistic Regression. After Training the model i can convert thie model into production ready.
