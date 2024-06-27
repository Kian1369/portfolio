# Selected Projects in Data Science, Machine Learning, and NLP

<br>

## Automatidata: NYC Taxi Fare Estimator
[Github Repository](https://github.com/Kian1369/Automatidata-Project)


![Taxi](assets/img/Taxi 3.jpg)


#### Overview

In this project, I developed an application for the New York City Taxi and Limousine Commission (TLC) to enable riders to estimate taxi fares in advance. The project spanned six comprehensive parts, each focusing on different aspects of data analysis and machine learning.

#### Key Features

- **Project Proposal:** Defined the fare estimation app's scope, milestones, and tasks.
- **Data Understanding:** Identified necessary datasets and explored key variables.
- **Exploratory Data Analysis (EDA):** Cleaned and visualized data to uncover patterns.
- **Statistical Testing:** Conducted hypothesis testing to validate data assumptions.
- **Regression Models:** Built and evaluated regression models to predict fare amounts.
- **Machine Learning Models:** Developed machine learning models to predict tipping behavior.

#### Highlights

- **Model Performance:** Achieved high accuracy and reliability in fare and tip prediction. 
- **Data Insights:** Identified key factors influencing fare and tipping behavior.
- **Business Impact:** Provided actionable insights for improving driver service strategies.


![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)


<br>

## Project: Naive Machine Translation and Locality Sensitive Hashing (LSH)

![Translation](assets/img/translation.png)

This project was the last section of the NLP specialization with classification and vector spaces authorized by DeepLearning.AI and offered through Coursera. I implemented and developed a machine translation system to translate English words to French using word embeddings and vector space models. The project involved the following key steps:

1. **Generating Embedding and Transformation Matrices**:
   - Created matrices for English and French word embeddings using a provided dictionary.
   - Ensured that each row in the English matrix corresponded to the same row in the French matrix for accurate alignment.

2. **Translation as Linear Transformation**:
   - Implemented a linear transformation to convert English word embeddings to French embeddings.
   - Minimized the translation error by computing and optimizing a transformation matrix using the Frobenius norm loss function.

3. **Testing the Translation**:
   - Evaluated the translation system by finding the nearest neighbors in the French embeddings and recommending the most similar French word.
   - Managed to translate words from one language to another language without ever seeing them with almost `56% accuracy` by using some basic linear algebra and    learning a mapping of words from one language to another!

4. **Locality Sensitive Hashing (LSH) for Document Search**:
   - Applied LSH to perform efficient document search and find similar tweets.
   - Created hash tables to index document embeddings, enabling fast approximate nearest neighbor search.

This project enhanced my understanding of machine translation techniques and the practical application of word embeddings in natural language processing tasks.
