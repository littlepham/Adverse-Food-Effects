# MIS-381N

## Dataset: https://www.kaggle.com/fda/adverse-food-events

## Question: 

What are the biggest predictors of food-related severe outcomes, including required intervention, hospitalization, death, life-threatening conditions, disability, serious injuries, and other medical problems? 

## Importance of the Question: 

* Put some statistic about how many people die from food allergies each year or have some major suffering <br>
* Can predict what providers need to look out for in symptoms in like E.R. to take care of those who will probably die first/have serious repercussions -> minimize deaths and healthcare costs <br>
* Improve diagnoses through analytics (this is in the field of healthcare analytics) <br>

### Google Colab Link:
https://colab.research.google.com/drive/1fhQCmTEiSIh7RGKcxkxzcDTDG2BxGwnx?usp=sharing

### Report Link:
https://docs.google.com/document/d/16yBLidQgjIiWVTrqLjq9xtNM8i7nBs9FbKyTgtKCRXo/edit?usp=sharing

## Steps and Timeline: 

### By August 4th (Exploratory Analysis): 

**MEET ON ZOOM at ?**
* Varun - Relation between Industry and product name (both after dropping redacted and without dropping).
* Disha - Word cloud for symptoms.
* Krish - Proceed with Outcome boolean EDA idea (code for finding Outcomes_bool from Outcomes uploaded to Github).
* Ask professor what method to use for encoding the symptoms.
* Upload results to Github for the report.

**Report + PPT**
* Description of project goals (Description + Importance of question).

### By August 5th (Create models):

**MEET AFTER WORKSHOP**
**Coding**
* Try to encode the symptoms into a feature and find the relation between symptoms and Outcomes_bool.
* Disha - Word2Vec for symptoms (DO ONLY IF THERE IS NO OTHER WAY TO ENCODE).
* Varun - Apply PCA to the Word2Vec encoded symptoms (DO ONLY IF THERE IS NO OTHER WAY TO ENCODE).
* Varun - Apply Boruta, find out which features are important.
* Upload results to Github for the report.

**Report + PPT**
* Update description of project goals if question changes.
* Finish EDA result portion from Aug 4th.

### By August 6th (Models):
**MEET at ?**
**Coding**
* Naive Bayes
* Logistic Regression
* KNN
* Random Forest
* Disha - SVM
* Upload results to Github for the report.

NOTE - Baseline accuracy = 74.35%. Include scaling (for KNN and logreg), normalization (for KNN and logreg), splitting into test-train, cross validation for all models.

**Report + PPT**
* Include results from Aug 5th.

### By August 7th: 
**MEET at ?**
**Report + PPT**
* Include results from Aug 6th.
* Write insights and solutions in the report and PPT.
* Final formatting/changes.

### August 7th/8th (Buffer day if things mess up): 
**MEET at ?**
* Practice Presentation and re-read deliverables.

### August 9th/10th:
* Presentation Days
