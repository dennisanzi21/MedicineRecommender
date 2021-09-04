# Drug Recommender System
  
__Overview__  
  
  
There are multiple drugs available for a condition, and consumers often have difficulties choosing drugs for their conditions.   
My aim of this project is to make a recommendation system for patients by predicting patients outcome using drug reviews. 
The recommender system potentially can help patients to choose better drugs for their conditions, and also can provide benchmark to drug providers such as doctors and pharmaceutical companies.  
  
__How to Run__  (Noted that there are several deendencies must be import for the codes to work)
1. Getting dataset: https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29  
2. Data cleaning and initial EDA: [drug_recommendation-data_cleaning.ipynb](https://github.com/jisong316/drug-recommendation/blob/master/drug_recommendation-data_cleaning.ipynb)  
3. Topic modeling: [drug_recommendation-topic_modeling-CV_bigram-LDA.ipynb](https://github.com/jisong316/drug-recommendation/blob/master/drug_recommendation-topic_modeling-CV_bigram-LDA.ipynb)  
4. Distribution of topics of top 10 conditions: [drug_recommendation-top_10-topics.ipynb](https://github.com/jisong316/drug-recommendation/blob/master/drug_recommendation-top_10-topics.ipynb)  
5. Supervised learning: [drug_recommendation-nlp_supervised.ipynb](https://github.com/jisong316/drug-recommendation/blob/master/drug_recommendation-nlp_supervised.ipynb)  
6. Summary of my data: presentation slides [drug_review.pdf](https://github.com/jisong316/drug-recommendation/blob/master/drug_review.pdf)


__For Web Demo__  (Noted that there are several deendencies must be import for the codes to work)
1. Getting github repository: https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29  
2. initialise installation: 
step 1: pip install widgetsnbextension
step 2: pip install ipywidgets
step 3: pip install voila
