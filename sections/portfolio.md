
## Portfolio

---

[**Predicting Psychiatric Readmission Rate Based on Clinical Notes**](https://github.com/Emmyphung/psychiatric-readmission-prediction)

[![Models](https://img.shields.io/badge/Jupyter-Models-blue?logo=Jupyter)](https://github.com/Emmyphung/psychiatric-readmission-prediction/tree/master/model-training)

<div> Rapid psychiatric readmissions present a burden for both the patients as well as the hospitals. Due to the difficulties in assessing mental health status and complications inherent to mental illnesses, premature discharges as well as rapid decay of mental status after discharge is an issue many psychiatric facilities faces. We aim to create a <b>BERT-based model that can assist clinicians in identifying patients as risk of psychiatric readmission </b> upon discharge as well as extract abstract relationships from discharge summaries. Furthermore, as an attempt to understand the level of representation learning achieved by BERT, we visualized the attention (or connection) between two word tokens within BERT embeddings and were surprised to see that these connections actually make sense.
<br>
<br>
Models: <b>LSTM with GloVe embedding, BERT (base) and BERT pre-trained on discharge notes</b>.
</div>
<br>
<center><img src="/images/bertproject.gif"/></center>
  
---
[**Food Happens in Vegas: How can restaurants improve their Yelp profiles for success?**](https://github.com/Emmyphung/Vegas_foodies)

[![Models](https://img.shields.io/badge/Jupyter-Models-blue?logo=Jupyter)](https://github.com/Emmyphung/Vegas_foodies/blob/master/models/models_vegas_final.ipynb)
[![Recommender System](https://img.shields.io/badge/Jupyter-Recommender_System-blue?logo=Jupyter)](https://github.com/Emmyphung/Vegas_foodies/blob/master/models/vegas_recommender_system.ipynb)

<div> The goals of this data mining project is to <b>1/ redefine success on Yelp</b> and <b>2/ identify key attributes that are associated with a successful Yelp profile using feature importance</b>. Our findings can help restaurants improve their Yelp profile to become more appealing to users.
<br>
Our methodology defines “success” as a binary variable through an exploratory analysis of the restaurants’ review counts and ratings on Yelp. Feature variables include categories and attributes that Yelp users can use to select which restaurant to visit. For this project, we ran Decision Tree, Random Forest, and Logistic Regression to explore key features associated with “success” and obtain recommendations for restaurants to improve their Yelp profile.
<br>
Models: <b>Decision Tree, Random Forest, and Logistic Regression</b>.

</div>
<center><img src="/images/yelp_project.gif"/></center> 

---
[**Effects of US Presidential Elections on the stock market: a close look into the Tech sector**](https://github.com/Emmyphung/FAANG_stockprices)

[![Time series analysis](https://img.shields.io/badge/Jupyter-Stock_analysis_with_interative_charts-blue?logo=Jupyter)](https://github.com/Emmyphung/FAANG_stockprices/blob/master/EDA_StockAnalysis.html)
[![Stock prediction](https://img.shields.io/badge/Jupyter-Stock_prediction-blue?logo=Jupyter)](https://github.com/Emmyphung/FAANG_stockprices/blob/master/Times%20series%20analysis_bymonths_%20FAANG.ipynb)

<div> This project analyzes stock prices of big tech companies, Facebook - Apple - Amazon - Netflix - Google (FAANG) and sees how they progressed throughout the two recent presidential election (2012 - Barack Obama and 2017 - Donald Trump).
<br>
Some interesting findings: 1) Overall, stocks within the FAANG companies are closely correlated; 2) Facebook and Google stocks were the most volatile in 2018, the year when Facebook had its infamous scandal with Cambridge Analytica; 3) Several tech stocks rocketed after Trump's elecion in 2017.<br>
<br>
Models: <b>Auto-regressive (AR), Moving average (MA), ARIMA (Autoregression integrated with moving-average) model</b>.
</div>
<center><img src="/images/FB_stock.png"/></center> 
  
---
[**Product Differentiation in the Automobiles Market: An Empirical Analysis**](https://github.com/Emmyphung/car_models/blob/master/README.md)

[![EDA](https://img.shields.io/badge/Jupyter-Stock_analysis_with_interative_charts-blue?logo=Jupyter)](https://github.com/Emmyphung/car_models/blob/master/car_EDA.ipynb)
[![Models](https://img.shields.io/badge/Jupyter-Stock_prediction-blue?logo=Jupyter)](https://github.com/Emmyphung/car_models/blob/master/car_modelling.ipynb)

<div> This research project examined the <b>quality vs. fuel-efficiency trade-offs between low-end and high-end car models</b>. I first consolidated a cross-sectional dataset of 10,000+ observations (2005–2014) and 22 variables from 3 sources. I then developed a Double-Log Regression model to estimate the average miles-per-gallon of an automobile model based on its design features and real market price. 
For feature engineering, I conducted Pearson’s correlation test to detect and reduce multi-collinearity problem; used year-fixed effects to avoid serial correlation. 
<br>
<br>
Models: <b>Linear Regression, Lin-Log and Double-Log models</b>.<br>
Results: Final R_squared: 0.7984 | Final MSE: 0.0024.
<br>
</div>
<center><img src="/images/Car_model_corrplot.png"/></center> 

---

[**Sentiment Analysis on Movie Reviews: Logistic Regression vs. Naive Bayes Bernoulli**](https://github.com/Emmyphung/Sentiment-Analysis)

[![Models](https://img.shields.io/badge/Jupyter-Models-blue?logo=Jupyter)](https://github.com/Emmyphung/Sentiment-Analysis/blob/master/Sentiment%20Analysis%20-%20NLP%20and%20Logistic%20Regression.ipynb)

<div> This notebook will compare the performance of two NLP techniques, <b>Count Vectorizor and TF-IDF Vectorizer</b>, and two classification models,  <b>Logistic Regression and Bernoulli Naive Bayes in sentiment analysis</b>. I'll give detailed explanation on which model performs better and why.
</div>
<center><img src="/images/Sentiment_analysis.png"/></center> 
<center><img src="/images/Sentiment_analysis_math3.png"/></center> 
<br>

---
[**Kaggle Competition: Google QUEST Q&A Labelling**](https://github.com/JasonZhangzy1757/Kaggle_Google_QUEST_QA_Labeling)

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://drive.google.com/file/d/1hiDfVsVQ3QgMWhEJ46JU7HjntgVCsjmj/view?usp=sharing)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/JasonZhangzy1757/Kaggle_Google_QUEST_QA_Labeling/blob/master/190103_StratifiedKFold_Emmy.ipynb)

<div style="text-align: justify"> Google Q&A Labelling is a classification problem. Given pairs of questions and answers, we are asked to classify the question types, answer types, level of helpfulness of the answers, etc. For this project, I conducted comprehensive EDA to understand the datasets and important variables, used Multilabel Stratified KFolds to solve class imbalance issue, and used BERT pretuned models to solve the classification problems.
</div>
<br>
<center><img src="/images/Google_Quest_QA.png"/></center>
<br>

---

[**Projected growth of Neurendocrine cells using Matlab**](https://github.com/Emmyphung/Neurendocrine-cells) <br>

[![Open Research Paper](https://img.shields.io/badge/PDF-Open_Research_Paper-blue?logo=adobe-acrobat-reader&logoColor=white)](https://github.com/Emmyphung/Neurendocrine-cells/blob/master/Project%20Write-up_My%20Phung.pdf)

<div style="text-align: justify">The project aims at tracking the three phase transformation of neuroendocrine cells specific to the human colon. A stem cell transforms into a progenitor cell and finally a mature cell through symmetric and asymmetric cell division. Symmetric cell division, also known as self-renewal, occurs when a stem cell divides symmetrically into two identical stem cells. Asymmetric cell division characterizes the maturation process when a stem cell divides into a stem cell and a progenitor cell, or a progenitor cell divides into a progenitor cell and a mature cell. In each phase, cells also experience apoptosis. meaning cell death. With an aim to capture this phenomenon, I want to build a model that track the number of cells in each phase, stem cells, progenitor cells and mature cells.
</div>
<center><img src="/images/Neucell.png"/></center>

