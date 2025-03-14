#SENTIMENT ANALYSIS USING NLP

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : ANAPARTHI BHASKARA VENKATA DURGA BHIMESH

*INTERN ID* : CT08WNA

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH


Project Description : 

-The task is to implement NLP on IMDB Dataset

  (1) Choosing Dataset : 

    - The dataset is taken from the kaggle " IMDB 50,000 Reviews ".
    
    - The dataset consists of two columns : (1) Text  (2) Type of Text
    
    - First column contains 50,000 sentences and Second column contains the type : if the sentence is positive or negetive

    - Now our task is to implement this and then the model should evaluate the text and classify it as positive or negative.

  (2) Processing the Dataset :

    - Now every row consist of a sentence.

    - The Sentence will be processed by removing stoping words like 'and','the','is', etc..

    - These words are unnecessary and won't help in Classification of the Text .

    - First we remove the special characters like "!@#$%^&*" which does nothing.

    - Next we then Tokenize the Sentences means the text is converted into words.

    - Now we Apply "Lemmatization" on the words.

    - Lemmatization means removing the suffix of the words like : running ---> run , gone ---> go .

  (3) Applying TF-IDF VECTORIZER :

    - TF-IDF is called Term Frequency and Inverse Document Frequency .

    - Words are given weights by calculating the frequency of the word in the Document.

    - term Frequency calculated by the frequency of the word in the sentence to Number of words in the Sentence.

    - We take max_features upto 5000.

    - And now we intialize the cleaned Reviews to Input Data 'X'.

  (4) Converting and Splitting the Data : 

    - The Class or the Output is in Categorical Values i.e., Positive and Negative .

    - Now the Positive is denoted as '1' and Negative as '0' .

    - After converting the output , it is ready to be trained .

    - The data is splitted into 80% Training data and 20% Testing data .

    - We use Random state to sure the order of picking the data will always Shuffled.

  (4) Training the Model ( LOGISTIC REGRESSION ) : 

    - Now we use Logistic Regression as our Model .

    - As it is used for Categorical data .

    - Now we Train the model with the training_data .

    - We use Testing_data to predict hte outputs and compare with the original one's .

  (5) Evaluation Metrics :

    - As this dataset is Classification , we use Accuracy Score as our Evaluation Metric .

    - For my model i got Accuracy of " 88.45 % ".

    - And also I Evaluate 'Confusion Matrix' , the report is shown in the image below .

  (6) Plotting HeatMap of Confusion Matric : 

    - The map is plotted between the predicted and actual testing Values .

    - The Heat map is shown as in the image below .


















    
