### Fetal Health Risk Prediction

**Author**
Rohit Kulkarni 

#### Executive summary
This project uses machine learning to predict fetal health risk categories based on cardiotocographic (CTG) data.
The goal is to assist in early detection of potential fetal complications and support clinical decision-making by providing a baseline predictive model.

#### Rationale
Fetal monitoring is crucial for identifying potential risks during pregnancy. Traditional assessment methods can be subjective and inconsistent.
By leveraging machine learning models trained on real-world CTG data, we aim to improve early detection accuracy and provide more consistent support for healthcare professionals.

#### Research Question
Can machine learning algorithms predict fetal health risk categories (Normal, Suspect, Pathological) based on cardiotocographic measurements?

#### Data Sources
Dataset: Fetal Health Classification Dataset
Source: UCI Machine Learning Repository
File used: fetal_health.csv

The dataset contains 2,126 records and 21 features, including measurements like fetal heart rate baseline, accelerations, decelerations, uterine contractions, and others.

#### Methodology
Data Cleaning: Removed duplicates and checked for missing values.

Exploratory Data Analysis (EDA): Visualized feature distributions, identified outliers, and explored correlations between variables.

Feature Engineering: Basic standardization and verification of key variables.

Modeling:

    Built a baseline Random Forest Classifier using scikit-learn.

    Evaluated performance based on accuracy and classification report (precision, recall, F1-score).

Visualization: Used Matplotlib and Seaborn to create readable charts and heatmaps.

#### Results
Baseline Model: Random Forest Classifier

Accuracy Achieved: ~95% on the test set

Key Findings:

    Strong correlation between variables like severe_decelerations and pathological fetal health.

    Some features had skewed distributions, which may require normalization for more advanced models.

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
