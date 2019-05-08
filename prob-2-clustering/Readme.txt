Approach ->
Step-1) Preprocessing the text - In this step basic preprocessing is done , converting string to lower case , lemmatization , stemming , removal of rare word etc 
Step-2) Load pretrained word2vec model of google
Step-3) Features used -> Headline + description text
Step-4) Get vectors of every word in the document and take a max pool of all the word vector in the document ,in this way we will get fixed dimension word vector for every step
Step-5) Apply TSNE to reduce the dimension of you document vector
Step-6) Perform Gaussian Mixture Model (GMM) clustering on the TSNE vector space
