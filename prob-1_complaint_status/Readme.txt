Approach ->
Step-1) Preprocessing the text - In this step basic preprocessing is done , converting string to lower case , lemmatization , stemming , removal of rare word etc 
Step-2) Features used -> Complaint summary + Complaint Reason + Transaction Type
Step-3) Converting all the preprocessed text into TFIDF vectors
Step-4) Balancing the dataset using SOMTE approach
Step-5) Applying SVM over the TFID vectors
