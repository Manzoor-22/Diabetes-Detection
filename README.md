# Diabetes-Detection

According to WHO:

"Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. 
Insulin is a hormone that regulates blood glucose. Hyperglycaemia, also called raised blood glucose or raised blood sugar, is a common effect of uncontrolled diabetes and over time leads to serious damage to many of the body's systems, especially the nerves and blood vessels."

Diabetes is a disease that occurs when your blood glucose, also called blood sugar, is too high. Glucose is your body’s main source of energy. Your body can make glucose, but glucose also comes from the food you eat.
<p align="center">
    <img width="600" src="https://github.com/Manzoor-22/Diabetes-Detection/assets/110250967/d8d63568-db0f-4665-bc60-9f3c52f0e084">
</p>


# Overview
This project aims to create a machine learning model that can predict the likelihood of an individual having diabetes based on certain medical features, all patients here are **Females** and at least **21 years old** of Pima Indian heritage. The model is built using a dataset containing various health-related attributes, and it leverages the power of machine learning to provide valuable insights into diabetes risk assessment.

# Dataset Features
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (in years)
- Outcome: Class variable (0 or 1)

# Methodology
The project involves the following main steps:

- Data Preprocessing: The dataset is thoroughly examined and cleaned to handle missing values, outliers, and any anomalies that might affect model performance.

- Feature Engineering: Relevant features are selected, and new features may be created to enhance the predictive power of the model.

- Model Building: Machine learning algorithms(Logistic Regression, Decision Tree, NaiveBayes Classification) are employed to train and test.

- Model Evaluation: The selected model is evaluated on unseen data to determine its generalization performance and predictive accuracy.

- Metics Evaluation : The performance of each model is evaluated using Accuracy Score, Precision Score and Confusion Matrix.

# Performances of Different Models

- Logistic Regression
  
  Accuracy = 75.324%
  
  Precision = 67.272%

- Decision Tree Classifier

  Accuracy = 74.675%

  Precision = 72.727%

- GaussianNB Classifier

  Accuracy = 76.623%

  Precision = 70.909%

# Credits
Information related to [Diabetes](https://www.who.int/news-room/fact-sheets/detail/diabetes).

Dataset taken from Kaggle, You can find the [original dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).
