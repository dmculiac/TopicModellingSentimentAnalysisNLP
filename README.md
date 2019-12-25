# Topic modeling, topic assignment and sentiment analysis


Most of the data on the web is in some form of free format. This means it's both unstructured and unlabeled, making it challenging to process and analyze. Furthermore, processing it might involve labeling data one document, one text bit, one comment at a time, which is labor intensive, time consuming and not something we're looking forward to.
This project will demo techniques that perform unsupervised learning on a large corpus of unstructured text:

1.  will determine the clusterings topics using NMF (Non-negative Matrix Factorization). The topics will be represented as numbers. They will provide the most common words associated with that clustering. It will be up to us to name that topic something meaningful. This is the only work involving human judgement. It's not necessary - it will only help with the readability and also with judging the quality of unsupervised machine topic modelling.

2.  after the clustering, will do the topic assignment for each comment in the corpus

3.  last step involves analyzing each comment for polarity sentiment and intensity of emotion using an NLTK library called VADER - Valence Aware Dictionary for sEntiment Reasoning

For those who like using enterprise BI tools, here is a very modest section of processing and distributing a python script in PowerBI.

# First of all - why Power BI?

I asked myself this question and resisted the "heresy" of defecting from matplotlib to a different visualization engine. "What is there to gain?"

Well, what started as a curiosity became a compeling argument with every iteration. I mean, we trust the machines getting better with every epoch. Was that too much to ask of myself?

So, to cut a long story short, the benefit of Power BI is in the instant interactivity: being able to check the quality of a sentiment analysis in "real time", something that Python (as much as I hurt saying this!!!), can't deliver...

To make Power BI python ready go [here](https://docs.microsoft.com/en-us/power-bi/desktop-python-scripts), ignore the first part (I mean you wouldn't be there if this is your first brush with python) and scroll to "Enable Python scripting" part. That's where you learn how to properly connect Power BI with python (Power BI can't read paths so you have to specify the python directory in the PBI "options" menu). Well, a small price to pay...


To enable matplotlib.pyplot visualization through Power Bi, go [here](https://docs.microsoft.com/en-us/power-bi/desktop-python-visuals).

Keep in mind, if everything else fails, there's still Bowie to save the day... 

======================================================================


 *"There's a starman waiting in the sky*

 *He'd like to come and meet us*

*But he thinks he'd blow our minds..."*


======================================================================


# Happy holidays

