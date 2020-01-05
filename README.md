# Topic modeling, topic assignment and sentiment analysis

<p align = "center">
  <img src = "https://blog-assets.hootsuite.com/wp-content/uploads/2024/02/Screen-Shot-2019-04-03-at-9.51.49-AM.png">
</p>


Most of the data on the web is in some form of free format. This means it's both unstructured and unlabeled, making it challenging to process and analyze. Furthermore, processing it might involve labeling data one document, one text bit, one comment at a time, which is labor intensive, time consuming and not something we're looking forward to.
This project will demo techniques that perform unsupervised learning on a large corpus of unstructured text:

1.  will determine the clusterings topics using NMF (Non-negative Matrix Factorization). The topics will be represented as numbers. They will provide the most common words associated with that clustering. It will be up to us to name that topic something meaningful. This is the only work involving human judgement. It's not necessary - it will only help with the readability and also with judging the quality of unsupervised machine topic modelling.

2.  after the clustering, will do the topic assignment for each comment in the corpus

3.  last step involves analyzing each comment for polarity sentiment and intensity of emotion using an NLTK library called VADER - Valence Aware Dictionary for sEntiment Reasoning

For those who like using enterprise BI tools, here is a very modest section of processing and distributing a python script in PowerBI.

# First of all - why Power BI?

The benefit of Power BI is in the instant interactivity: being able to check the quality of a sentiment analysis in "real time", something that Python (as much as I hurt saying this!!!), can't deliver...

To make Power BI python ready go [here](https://docs.microsoft.com/en-us/power-bi/desktop-python-scripts), ignore the first part and scroll to "Enable Python scripting" part. That's where you learn how to properly connect Power BI with python (Power BI can't read paths so you have to specify the python directory in the PBI "options" menu). Well, a small price to pay...


To enable matplotlib.pyplot visualization through Power Bi, go [here](https://docs.microsoft.com/en-us/power-bi/desktop-python-visuals).
