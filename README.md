# Explainable-AI
This repository is about the implemnentation of “Explainable AI for Classification using Probabilistic Logic
Inference” by Fan et al

The overarching goal of Explainable AI is to develop systems that not only exhibit intelligent behaviours, but also are able
to explain their rationale and reveal insights. In explainable machine learning, methods that produce a high level of prediction
accuracy as well as transparent explanations are valuable.

In this repository I have implemnented the algorithom or methods proposed by Fan et al in python.

Repository also contains the review of “Explainable AI for Classification using Probabilistic Logic
Inference” by Fan et al and “Causability and explainability of artificial intelligence in medicine” by holzinget et al
## Dataset
For implementation liver disease dataset is downloaded from kaggle. The dataset contains the data of 579 patients. 414 patients are suffering from liver disease while 165 are not.

## Classification
First classification is done using logistice regression

## Explanation:
Later the explaination of feature is done using the method proposed in the paper
The model is implemented in the following steps:
1. Constructing Knowledge Base directly (Algorithm 3)
2. Constructing Knowledge Base relevant to query (Algorithm 5)
3. Solving a single Query (Algorithm 4)
4. Explaining a single Query (Algorithm 6)
