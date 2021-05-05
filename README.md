# NaiveBayes

## It is a probabilistc model  for text classification
- ex `P(spam|words) = P(Word1|spam)*P(Word2|spam)*P(W3|spam)......./P(words)` and `(ham|words) = P(Word1|ham)*P(Word2|ham)*P(W3|ham)......./P(words)`
- Note denominator is constant.
- We compare P(spam|words) and P(ham|words) 
- If P(spam|words) is higher then email is Classified as spam
- else it is ham

## Libraries used
1. Numpy
2. Pandas
3. Matplotlib and seaborn
4. Sklearn
5. nltk

# Steps
1. Read data
2. Remove stop words so that the bag of word size becomes smaller
3. After stop words are removed create bag of words
4. Apply Naive Bayes and classify




Kaggle notebook link: <a href="https://www.kaggle.com/msvrao/notebook24f1a2c132">Click here</a>
