# Text-Similarity-NLP
This project calculates similarities between 2 text inputs and returns a similarity score between 0 &amp; 1. Developed using NLP Techniques and deployed using Flask

Approach : 
- This Notebook focuses on calculating the similarity between 2 texts.
- We will be using a CSV file comprising of 2 independent features, viz. text1 & text2.
- Since there's no dependent variable, we have 2 options : Either treat the problem statement as an unsupervised problem and make clusters, or perform some feature engineering and treat the probem as a regression problem in supervised learning.
-  We would go with the supervised learning approach.
-  Please go through `Text Similarity.ipynb` for the approach in Data Analysis, Feature Engineering and Model Selection, Training, Deployment & Evaluation.
-  The `app.py` flask application is created to to be deployed in a developed environment, which renders the `index.html` template.
-  The `index.html` page takes 2 text inputs and provides us with the similarity score between 0 & 1 on submitting.
  ![TextSimilarity](https://github.com/maitreyaz/Text-Similarity-NLP/assets/83835081/0e31e1ed-49db-4883-979f-dae3191d3170)
