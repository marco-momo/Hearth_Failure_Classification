# Hearth Failure Classification : A survey of simple classification algorithms applied to a clinical records dataset. 

Cardiovascular diseases kill several people every year, and they mainly exhibit myocardial infarctions and heart failures. For doctors is crucial to understand how severe is the cardiovascular disease of a patient. The patients can be analyzed in terms of electronic medical records which quantify symptoms, body features, and clinical laboratory test values. There are some well-known risk factors, such as *serum creatinine* and *ejection fraction*, that are a key flag for detecting cardiovascular diseases. However, in some situations, the whole figure of a patient may be not clear and the risk factors could not be enough for detecting the disease. 

With Machine Learning we can derive non-trivial decision rules that can predict whenever the patients are at risk of death given in medical records. Moreover, models like *Decision Tree* or *Random Forest* can individuate the most important features among the ones included in the records. In this work, we deal with a medical dataset, where there are contained a lot of clinical measurement of patients observed during a follow-up period together with a variable that declare the state of the patient at the end of the period, which can be *survived* or *death*. We apply several classification algorithms to this dataset obtaining models that learn how to predict the risk of death for a patient given input medical record.

The work is dived into $4$ sections:
- **Exploratory Data Analysis** : where we understand what kind of data we have;
- **Preprocessing** : where we manipulate the data making them more proper for classification algorithms;
- **Model Selection and hyperparameter tuning** : where we define the models and detect the best configurations of the hyperparameters; 
- **Model evaluation** : where we evaluate the selected classification models on unseen data.

The dataset is available at the link : [dataset.](http://archive.ics.uci.edu/ml/machine-learning-databases/00519/)
