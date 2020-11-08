# Drugs.com Reviews Data Mining 

Exploratory and predictive analysis of consumer drug reviews using text mining approaches

In Gräber (2018), the authors scraped online review data from Drugs.com and Druglib.com, and used this data set to perform in-domain, cross-domain, and cross-data sentiment analysis to develop a classification model to predict patient satisfaction and sentiments towards side effects.

This Python notebook performs additional descriptive and predictive data mining techniques to this data set, as follows:  

1.	Exploratory analysis to detect potential patterns or relationships:

  a.	Distribution of various features, such as distribution of drug ratings, distribution of drug review lengths, distribution of review helpfulness scores, etc.
  b.	Relationships between features, i.e. relationship between date of review and drug rating, condition treated and the number of reviews, review length and condition treated, helpfulness of review and length of review, review length and drug rating, condition treated and drug rating
  c.	Identify the most-used words in drug reviews

2.	Text Extraction/“Featurizing” Text:  Extract keywords from the unstructured drug review text for use as predictors in regression analysis, using techniques such as TF-IDF, Latent Semantic Analysis (LSA)/Principal Component Analysis, and/or spectral learning (Eigenwords) algorithms.

3.	Regression Analysis:  Applys and evaluate various regression models for predicting patient drug score, based on known or extracted features.

Data 
This notebook uses the Drug Review Dataset provided by the University of California Irvine’s Machine Learning Repository (link).  This dataset provides online patient reviews of drugs that have been scraped from online drug review sites, like Drugs.com.  

The data contains 6 attributes:  the name of the drug, the condition reported, the full text of the patient’s review, the patient’s rating of the drug (out of 10 stars), the date of the review,  and the number of users who found the review useful.  The data set contains ~275,000 records in two tab-separated value files which have been conveniently pre-separated into testing and training sets.  



Raw data files: https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29 

Original paper:  Felix Gräßer, Surya Kallumadi, Hagen Malberg, and Sebastian Zaunseder. 2018. Aspect-Based Sentiment Analysis of Drug Reviews Applying Cross-Domain and Cross-Data Learning. In Proceedings of the 2018 International Conference on Digital Health (DH '18). ACM, New York, NY, USA, 121-125. DOI: [Web Link]

