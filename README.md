# Student Employability Prediction and HR Bias Detection through Machine Learning Analysis of Interview Traits

<div align='center'> This an ML training where the target is Employability, with character behavior features.  </div>

<div align='center'>
Before we dive into training the model we have to look at previous works of Machine learning model methods.
</div> 
<br>
<div align='center'>
There are several ways to factor the employability of a person. in this study a <a href="https://www.atlantis-press.com/article/126017440.pdf">ML model training on Employability</a>.it utilizes various ML training methods such as: Logistic Regression, Random Forest and XGBoost. this model uses school participation or extracurriculars, internship, technical skills. CGPA.
</div>
<br>

### DATA OBSERVATION ( IT IS AN INTERVIEW ASSESMENT DATASET)

<div align ='center'>
The <a href="https://www.kaggle.com/datasets/anashamoutni/students-employability-dataset">data</a> that the model that we are about to use relies on characteristics. physically and mentally. This dataset is designed to evaluate employability based on a set of observable personal and behavioral traits rather than academic or technical achievements during an interview.

 Each student record includes categorical ratings (on a scale of 2–5) for attributes such as general appearance, manner of speaking, physical condition, mental alertness, self-confidence, ability to present ideas, and communication skills. Alongside these, a performance rating is included to capture overall student assessment. The target variable is a binary class label — Employable or LessEmployable — which frames the problem as a classification task.

By focusing on soft skills and presentation qualities, the dataset emphasizes how interpersonal and behavioral factors influence employability perceptions. This approach differs from datasets built on grades, internships, or technical skills, as it highlights the role of confidence, communication, and presence in hiring decisions. While effective for modeling evaluator judgments, it also raises questions about subjectivity and fairness, since traits like appearance or physical condition may introduce bias. Nonetheless, it provides a valuable lens for studying employability from a behavioral standpoint, complementing more traditional academic or skill-based datasets.
</div>

### how to utilize it. recognizing limitations and scope
<div align='center'> 

 its limited to 1 single nation for assesment of someone sucessfuly passing an interview. so its features can be culturally bias. but not to a single individual who conducted the interview as this data was collected from various universities. such as manner of speaking and general appearance can differ from culture to culture.  this data doesnt will not likely tell someones employability as it is limited to mental and physical capacity and characteristics. but it can tell how a student carry themselves during an interview. 

 
</div>

## RESULTS and Discussion 

<div align='center'> 

<p> <img src='score\score.png' alt="Feature Importance"> </p>

- We see that the overall accurary of the model is 90 percent. with a precision of 91 percent, a recall of 91 percent and an F1 of 91.6 percent. 

<p> <img src='images\FeatureImportnace.png' alt="Feature Importance"> </p>

- we see that Mental Alertness and General Apperance weighs heavy. which accounts to 17.37 and 15.18 percent when it comes to making a choice whether someones is employable or less employable. this shows that mental alertness there is a wide gap in importnace compared to communication skills (9.7). 
 
</div>