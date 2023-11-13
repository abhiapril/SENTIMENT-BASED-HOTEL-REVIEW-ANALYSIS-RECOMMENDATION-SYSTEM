SENTIMENT-BASED HOTEL REVIEW ANALYSIS & RECOMMENDATION SYSTEM

Project Overview

The primary objective of this data science project, named SENTIMENT-BASED HOTEL REVIEW ANALYSIS & RECOMMENDATION SYSTEM, is to utilize Natural Language Processing (NLP), Machine Learning techniques, and Large Language Models (LLMs) for sentiment analysis on user reviews. Additionally, it aims to deliver customized hotel suggestions, considering a user's intended purpose of visit and specific requirements. The automated system for sentiment analysis and hotel recommendations provides valuable insights to luxury hotels, helping them identify areas for improvement and areas of excellence within their services.

Tools Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Scikit-learn (Sklearn)
- NLTK
- Google.generativeai
- Count Vectorizer
- Bag-of-Words(BoW)
- NaiveBayes Classifier
- Cosine Similarity
- Palm 2(LLM)

Initial Data Exploration

After initially exploring the dataset, it was observed that the majority of the 1492 European luxury hotels have average scores that fall within the range of 7.6 to 9.2. The average scores span from 5.2 to 9.8, with a mean value of 8.4. The project focuses on sentiment analysis using NLP, particularly employing a bag-of-words model with a Naive Bayes Classifier, achieving high accuracy during both training (93.5%) and testing (92.5%). The most informative words for positive and negative reviews were identified, providing valuable insights for hotels looking to enhance customer satisfaction.

Recommendation System

A recommendation system has been created that allows users to input their preferred country, purpose of visit, and travel preferences. The system offers a list of the top 5 hotels in that country according to the user's specifications. Cosine similarity is leveraged to determine relevant recommendations, and the Palm2 language model is used to craft succinct descriptions for the recommended hotels. The Django framework is employed for the graphical user interface (GUI) development of this system.

References

- "Introduction to Machine Learning with Python" by Andreas C. Müller and Sarah Guido
- "Python for Data: Data Wrangling with Pandas, NumPy, and IPython" by Wes McKinney
- Python packages: Matplotlib, Pandas, SciPy, Seaborn documentations
- StackOverflow for debugging code
- Popular blogs such as Analytics Vidhya, Towards Data Science, KDnuggets, etc.
- Youtube channels: StatQuest with Josh Starmer, Data School, Krish Naik, etc.

Data Set

The dataset, sourced from Kaggle, consists of 515,000 rows with information on 1493 luxury hotels across Europe. Key features include Hotel Name, Hotel Address, Hotel Score, Review Date, Reviewer Nationality, Positive Review, Negative Review, Reviewer Score, Tags, and Days Since Review.

Data Source: 515K Hotel Reviews Data in Europe (https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe/data)
