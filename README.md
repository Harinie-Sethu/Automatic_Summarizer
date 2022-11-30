# Automatic Summarizer
We have built two summarizer models: Edmundsons and MMR (maximal marginal relevance)

# Dataset
Dataset:WCEP 

Download from: https://colab.research.google.com/github/complementizer/wcep-mds-dataset/blob/master/wcep_getting_started.ipynb#scrollTo=vlnPI2ZXuQVq

The WCEP dataset for multi-document summarization (MDS) consists of short, human-written summaries about news events, obtained from the Wikipedia Current Events Portal (WCEP), each paired with a cluster of news articles associated with an event. Each cluster contains multiple articles and one golden summary. We use this golden summary against our generated summarizers to test the similarity.

# Edmundson

# MMR

# Evaluation
Rouge has been used to measure the similarity between golden summaries given i

# Report
When the summary has more sentences, the precision increases, but the F-measure stays roughly the same across both.

# References
