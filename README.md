# HealthcareSBERT
NLP final project


Our goal is to train or fine-tune SBERT on a healthcare-specific dataset so that it understands domain-specific language. In this case the domain is health care.

We found these two main related applications:

-Clustering clinical notes or research abstracts (or general documents that we find,depending on the dataset). Find the best number of clusters and understand how they are divided. 

-Match a new input to the clustered documents and retrieving the most related ones (you can also label it, using the clusters we previously made).


RQ1 – Domain adaptation:
How much does fine-tuning SBERT on healthcare-specific sentence pairs improve sentence similarity performance compared to general-domain SBERT models?

RQ2 – Clustering effectiveness:
How effectively do sentence embeddings from fine-tuned SBERT capture semantic structure in healthcare texts for clustering purposes, compared to general-domain embeddings?

RQ3 – Retrieval performance:
Does using fine-tuned SBERT embeddings improve the retrieval of semantically related documents compared to general-domain embeddings?
