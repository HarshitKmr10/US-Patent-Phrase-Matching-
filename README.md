# US-Patent-Phrase-Matching
This project was made for the kaggle competition https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching/overview
# Overview
In this competition, you will train your models on a novel semantic similarity dataset to extract relevant information by matching key phrases in patent documents. Determining the semantic similarity between phrases is critically important during the patent search and examination process to determine if an invention has been described before. For example, if one invention claims "television set" and a prior publication describes "TV set", a model would ideally recognize these are the same and assist a patent attorney or examiner in retrieving relevant documents. This extends beyond paraphrase identification; if one invention claims a "strong material" and another uses "steel", that may also be a match. What counts as a "strong material" varies per domain (it may be steel in one domain and ripstop fabric in another, but you wouldn't want your parachute made of steel). We have included the Cooperative Patent Classification as the technical domain context as an additional feature to help you disambiguate these situations.<hr>
# Dataset 
Here's the link for Dataset https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching/data<hr>
## Data Information
id - a unique identifier for a pair of phrases<br>
anchor - the first phrase<br>
target - the second phrase<br>
context - the CPC classification (version 2021.05), which indicates the subject within which the similarity is to be scored<br>
score - the similarity. This is sourced from a combination of one or more manual expert ratings.<br
