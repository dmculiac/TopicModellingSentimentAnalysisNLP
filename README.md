# Topic modeling, topic assignment and sentiment analysis


Most of the data on the web is in some form of free format. This means it's both unstructured and unlabeled, making it challenging to process and analyze. Furthermore, processing it might involve labeling data one document, one text bit, one comment at a time, which is labor intensive, time consuming and not something we're looking forward to.
This project will demo techniques that perform unsupervised learning on a large corpus of unstructured text:

1.  will determine the clusterings topics using NMF (Non-negative Matrix Factorization). The topics will be represented as numbers. They will provide the most common words associated with that clustering. It will be up to us to name that topic something meaningful. This is the only work involving human judgement. It's not necessary - it will only help with the readability and also with judging the quality of unsupervised machine topic modelling.

2.  after the clustering, will do the topic assignment for each comment in the corpus

3.  last step involves analyzing each comment for polarity sentiment and intensity of emotion using an NLTK library called VADER - Valence Aware Dictionary for sEntiment Reasoning
