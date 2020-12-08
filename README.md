
# <div align="center"> Predict whether patients have risk of future Coronary Heart disease
![alt text](https://github.com/Sandeep-Bansal1/heart_disease/blob/main/heart%20cover%20picture.png?raw=true) <pre>
Contrubuter  : Sandeep Bansal
</pre>

<pre>
Languages: Python
Tools/IDE: Anaconda
Libraries: pandas, matplotlib, numpy, sklearn, seaborn
</pre>

<pre>
Assignment Submitted: December 2020
</pre></b>
---
## Project Overview
- <b>Data</b> -The raw dataset can be found on the Kaggle website, [here](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset). 
- <b>Research</b> 
  -World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.The remaining research can be found 
  [here](https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds))
  - If you are unfamiliar with Diabetes and its disease process please check out **Heart Disease Pathophysiology video which can be found** [here](https://www.youtube.com/watch?v=lTCF8y7e1Bw)
  
## Buisness Objective </b> 
- Using Logistic Regression can we pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk?
---
## Abstract and Introduction:
- CVDs are the number 1 cause of death globally: more people die annually from CVDs than from any other cause.
- An estimated 17.9 million people died from CVDs in 2016, representing 31% of all global deaths. 
- Of these deaths, 85% are due to heart attack and stroke.
- Over three quarters of CVD deaths take place in low- and middle-income countries.
- Out of the 17 million premature deaths (under the age of 70) due to noncommunicable diseases in 2015, 82% are in low- and middle-income countries, and 37% are caused by CVDs.
#  <div align="center"> ![alt text](https://github.com/Sandeep-Bansal1/heart_disease/blob/main/heart-attack-diagnostics.png?raw=true)
  
---
## Motivation: 
- Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions.

---

## Proposed Methodology of Modeling:
- Logistic regression is one such regression algorithm which can be used for performing classification problems. It calculates the probability that a given value belongs to a specific class. If the probability is more than 50%, it assigns the value in that particular class else if the probability is less than 50%, the value is assigned to the other class. Therefore, we can say that logistic regression acts as a binary classifier.
- For this project we will calculate the probability that a patient has diabetes which will be labeled the dependent variable. 0 = Not Diabetic, 1 = Patient is Diabetic
---
## Results and Primary Findings:
 ---
| Model | Evaluation |
| --- | --- |
| **Accuracy** | 0.75 |
| **Precision** | 0.89 |
| **F1_Score** | 0.82 |
| **Recall** | 0.76 |
- Accuracy: Help us determine or predict the true diabetic person out of the population. It is the fraction of predicted diabetic patients that the model got right.
- Precision: ssists to determine what are the relevant positive diabetic patients out of entire positive diabetic predictions.If what you have predicted and actual are matching. ) 
- F1_Score: Harmonic mean of precision and recall. We consider F1_score because it balances between precision and recall.
- Recall: Fraction of actual diabetic patients to the number of diabetic patients retrieved from population.

#  <div align="center"> ![alt text](https://github.com/Sandeep-Bansal1/Diabetes_Project/blob/main/ROC%20curve.png?raw=true)
  - Measure of model and how it can distinguish two seperate groups under the target variable. The more area under the curve the better the model.
---
## Limitations and Future work:
  - According to the article "Early onset type 2 diabetes: risk factors, clinical impact and management" Author Emma Wilmot indicates that to determine prognosis of patients with diabetes its important to catch it at an early stage. If patients are young adults typically between 18-30 years old, patients are likely to have Type 1 Diabetes, patients over the age of 40 are more likely to be diagnosed with Type-II-Diabetes.Therefore the primary limitation in this dataset is the lack of age of these individuals in the dataset. If provided with the age we would be able to further our analysis between Type I and Type II diabetes.
  In future analysis I would add more features. I would add more of a variety in ages of individuals, and I would add a feature indicating whether the patient is a male or female. These two features would provide us insight into whether diabetes is moreso found in male or female, and in which age group. Lastly, I would utilize other machine learning models to investigate whether we would be able to produce a more effective model. 
---
## Conclusion and summary:
  - Logistic regression is a regression algorithm which can be used for performing classification problems. It calculates the probability that a given value belongs to a specific class. In this particular study we utilized the diabetes dataset to determine whether the features could accuratly predict whether a patient would have diabates. After modeling our data we were able to produce convincing results that the features in this dataset do in fact increase the odds and the probability of a patient being diagnosed with diabetes. 
 
---
## References and contributions:

1. Datasets: https://www.kaggle.com/uciml/pima-indians-diabetes-database
2. Maryland Dataset: https://opendata.maryland.gov/Health-and-Human-Services/Number-of-Diabetes-Deaths-among-MarylandResidents/smru-f5wc
3. Research Article: https://journals.sagepub.com/doi/full/10.1177/2040622314548679
4. Cover Picture, Global Map: Google.com 
5. Professor Murat Guner: https://github.com/mguner/UMBC_DATA602/tree/master/Week-4
6. My Youtube Diabetes Video: https://www.youtube.com/watch?v=QaDSHYmdpyU&feature=youtu.be
