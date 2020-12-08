
# <div align="center"> Predict whether patients have 10-year risk of future coronary heart disease (CHD)
![alt text](https://github.com/Sandeep-Bansal1/Diabetes_Project/blob/main/Diabetes%20image.png) <pre>
Contrubuter  : Sandeep Bansal
</pre>

<pre>
Languages: Python
Tools/IDE: Anaconda
Libraries: pandas, matplotlib, numpy, sklearn, seaborn
</pre>

<pre>
Assignment Submitted: October 2020
</pre></b>
---
## Project Overview
- <b>Data</b> - Two datasets were used for modeling and reference. The raw dataset can be found on the Kaggle website, [here](https://www.kaggle.com/uciml/pima-indians-diabetes-database). The Maryland Dataset can be found [here](https://opendata.maryland.gov/Health-and-Human-Services/Number-of-Diabetes-Deaths-among-Maryland-Residents/smru-f5wc)
- <b>Research</b> 
  - Emma Wilmot Department of Diabetes & Endocrinology & Iskandar Idris Royal Derby Hospital and Division of Medical Sciences & Graduate Entry Medicine, University   of Nottingham Title: "Early onset type 2 diabetes: risk factors, clinical impact and management" can be found 
  [here](https://journals.sagepub.com/doi/full/10.1177/2040622314548679)
  - If you are unfamiliar with Diabetes and its disease process please check out **my Diabetes Pathophysiology video which can be found** [here](https://www.youtube.com/watch?v=QaDSHYmdpyU&feature=youtu.be)
  - Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.
## Buisness Objective </b> 
- Using Logistic Regression can a machine learning model accurately predict whether or not the patients in the dataset have diabetes or not?
---
## Abstract and Introduction:
- The worldwide prevalence of DM has risen dramatically over the past two decades, from an estimated 30 million cases in 1985 to 415 million in 2017. According to the article titled "Early onset of type 2 diabetes: risk factorsm clinical impact and management", statistics state the Global estimate for Diabetes Mellitus is approximatly 415 million in 2017. Regional estimates of the number of individuals with diabetes (20–79 years of age) are shown (2017).Based on current trends, the IDF projects that 642 million individuals will have diabetes by the year 2040.
#  <div align="center"> ![alt text](https://github.com/Sandeep-Bansal1/Diabetes_Project/blob/main/Diabetes%20Global%20Impact%20.png?raw=true)
  
---
## Motivation: 
- Approximately 623,041 people in Maryland, or 12.6% of the adult population, have diabetes. Of these, an estimated 156,000 have diabetes butare unaware of it, greatly increasing their health risk. In addition, 1,634,000 people in Maryland, 36.9% of the adult population, have prediabetes with blood glucose levels higher than normal but not yet high enough to be diagnosed as diabetes. 
# <div align="center"> ![alt text](Diabetes_Maryland_Chart.png)
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
