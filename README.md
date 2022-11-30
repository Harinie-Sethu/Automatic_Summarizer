# Automatic Summarizer
We have built two summarizer models: Edmundsons and MMR (maximal marginal relevance)

# How to use


# Dataset
Dataset: WCEP 

Download from: https://colab.research.google.com/github/complementizer/wcep-mds-dataset/blob/master/wcep_getting_started.ipynb#scrollTo=vlnPI2ZXuQVq

The WCEP dataset for multi-document summarization (MDS) consists of short, human-written summaries about news events, obtained from the Wikipedia Current Events Portal (WCEP), each paired with a cluster of news articles associated with an event. Each cluster contains multiple articles and one golden summary. We use this golden summary against our generated summarizers to test the similarity.

# Edmundson
It is based on the combined weightage from four methods as proposed by H.P. Edmundson (1969). The four methods include: CUE method, KEY method, TITLE method and HEADING method. 
It is a single document summarizer which is mostly used for technical documents.

# MMR
Maximal Marginal Relevance is based on the method as proposed by Carbonell and Goldstein. 
It is a multi document summarizer.

# Evaluation
The evaulation was done based on the Rouge method proposed by Chin-Yew Lin. Rouge has been used to measure the similarity between golden summaries given in the specific cluster versus the summaries generated through our models.

# Initial Result
When the summary has more sentences, the precision increases, but the F-measure stays roughly the same across both.

# References
