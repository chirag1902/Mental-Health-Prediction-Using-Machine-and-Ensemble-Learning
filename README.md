# Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning
A comparative study of different Machine learning and Ensemble Learning Algorithms

## INTRODUCTION
In the fast-paced modern world, mental health is something that doesn’t get addressed as much as it should be, and often is surrounded by stigma. But studies show that it is a matter of major concern and which needs to be addressed. Psychological health issues like anxiety, depression and stress have become prominent among the public. Some of the major mental health disorders, such as chronic diseases, bipolar disorder, and schizophrenia they don’t suddenly arise out of nowhere, they often develop over time and produce symptoms that can be recognized in the early stages. Such disorders could be avoided or controlled more successfully.
To avoid serious illness, it is necessary to identify the mental health of different categories at different times. In the next years, healthcare providers will be required to consider a patient’s mental health profile to deliver better medication and aid in a speedier recovery. Early detection of mental health issues allows specialists to treat them more effectively and it improves patient’s quality of life. Mental health is about one’s psychological, emotional, and social well-being. Mental health is very important at every stage of life, from childhood and adolescence through adulthood. This project aims at identifying machine learning techniques and assess their accuracy in identifying mental health issues using several accuracy criteria. The machine learning techniques to be used are Logistic Regression, Decision Tree Classifier, Random Forest, Extra Trees Classifier, LGBM, Ada boost, SVC, Naïve Bayes, KNN, and LDA.

## PROPOSED METHODOLOGY

![image](https://github.com/chirag1902/Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning/assets/71887495/1b6b74ec-d35a-4370-aa7a-a3c5650d23f4)

The Proposed Architecture has been divided into 5 main parts: Dataset Description, preprocessing of the dataset which includes feature encoding, visualization, feature selection, model building, and performance analysis. The first step, Data set description, describes about the dataset and its columns. The next step, preprocessing of the data, involves checking for null values, Label encoding. The third step, involves visualizing the data to gain insights about the data .The fourth step, model building, involves various machine model that can learn from the preprocessed data and perform the desired task of mental health classification. Finally, the performance analysis step involves evaluating the performance of the model by measuring metrics such as accuracy, precision, recall, and F1-score.

### Dataset Description:
The "Mental Health in Tech Survey" dataset is a collection of survey responses from people who work in the technology sector and is accessible on Kaggle. The Open Sourcing Mental Illness (OSMI) organisation, which seeks to increase awareness of and offer assistance for mental health concerns in the tech community, gathered the data. A total of 1,990 respondents from several nations, including the United States, Canada, and the United Kingdom, provided replies for the dataset.
A wide range of issues relating to mental health are included in the survey questionnaire, such as the presence of mental health illnesses, attitudes about seeking treatment, and experiences with workplace modifications. Demographic data from the dataset includes things like age, gender, race and ethnicity, education level, and job status. The dataset also includes details on the participants' job responsibilities, employment perks, and the amount of support their employers provided for mental health issues.
Almost 1,900 rows of responses are contained in 27 columns of the CSV-formatted dataset. Age, gender, race/ethnicity, level of education, employment status, job title, benefits offered by the employer, and the amount of support participants have received for mental health issues are all listed in the columns. Aspects including attitudes towards mental health, experiences with workplace adjustments, and the existence of mental health illnesses are covered in other sections.

### Feature encoding:
Feature encoding is an important step in preparing data for use in machine learning models. For this purpose we have used label encoding, which involves transforming categorical variables into numerical variables. Label encoding is needed because many machine learning algorithms cannot process categorical variables directly. Instead, they require numerical inputs.
The following features were encoded using label encoder : Age, Gender, self_employed, family_history, treatment, work_interfere , remote_work, tech_company , benefits, care_options, wellness_program, seek_help , anonymity, leave, mental_health_consequence, phys_health_consequence, coworkers, supervisor, mental_health_interview, phys_health_interview, mental_vs_physical, obs_consequence
.
### Data Visualization:
We performed visualization over various features to find their distribution, and how related each feature is with the target feature. We mapped the features individually with the target feature to find which classes are more prone to get treatment and which are not. For instance among genders we found that male were the most prone to mental health disorder than any other gender, we also found that people having a family history of mental health were more prone to get treated with one in the later stages of their life, self-employed and people doing remote work were also found to be more probable to get a mental health issue, on the contrary tech company employees majority of employees didn’t have any mental health issues. We also performed discrete analysis over answers to few of the questions asked such as whether a person feels safe to discuss about mental health with their coworkers. A majority of them said yes (at least to some of the coworkers). We also found that a majority of people in the office haven’t gone through any mental health interview at all in the first place.

## RESULTS

This section provides a comparative analysis of the different machine and ensemble learning models used in this project on various performance metric.

![image](https://github.com/chirag1902/Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning/assets/71887495/445c8dfd-365d-47ab-97cb-e020292666a6)

![image](https://github.com/chirag1902/Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning/assets/71887495/d33c6234-c9af-4b42-bb79-2a77a7ebdc7a)

![image](https://github.com/chirag1902/Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning/assets/71887495/22939897-9572-4bf1-981a-445d7a1f090e)

![image](https://github.com/chirag1902/Mental-Health-Prediction-Using-Machine-and-Ensemble-Learning/assets/71887495/2504b040-6cb5-40f7-b0c8-85f07c2b4863)

## CONCLUSION:
This project presented an approach for classifying whether a patient should seek treatment to improve their mental health by using machine learning and ensemble methods. We collected a dataset name “Mental Health in Tech Survey” from Kaggle. The acquired dataset was preprocessed, erroneous data was removed and key features were extracted using correlation techniques. Data Visualization was performed to gain insights from the data and understand the distribution of the data.
Different machine learning algorithms were trained and tested on the preprocessed dataset. The machine learning algorithms used are Decision Tree Classifier, Random Forest Classifier, KNN Classifier, Logistic Regression, LGBM Classifier, AdaBoost Classifier, Naïve Bayes Classifier, Extra Trees Classifier, Linear Discriminant Analysis and Support Vector Classifier. The metrics used for evaluation of models were accuracy, precision, recall and F1-score. The model which performed the best in predicting the target variable in terms of accuracy was LGBM Classifier, for the test dataset, LGBM Classifier had a 75.4% accuracy rate, in terms of precision the highest precision rate of 77.6% was achieved by Naïve Bayes and in terms of recall highest recall of 76.9% was achieved by Ada Boost Classifer, which also achieved the highest F1 - score of 74.7%. In this project it is necessary that model chosen has the least False Negative, which is achieved by Ada Boost, which has classified 28 labels as False Negative.




