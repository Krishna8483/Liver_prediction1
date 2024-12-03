Liver-disease-prediction
Business Problem
Problem Context

Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhaling of harmful gases, and intake of contaminated food, pickles, and drugs. This dataset was used to evaluate prediction algorithms to reduce the burden on doctors.
Content

This data set contains 416 liver patient records and 167 nonliver patient records collected from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to divide groups into the liver patient (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records.

Any patient whose age exceeded 89 is listed as being of age "90".
Features:

    Age of the patient
    The gender of the patient
    Total Bilirubin
    Direct Bilirubin
    Alkaline Phosphotase
    Alanine Aminotransferase
    Aspartate Aminotransferase
    Total Proteins
    Albumin
    Albumin and Globulin Ratio
    Dataset: field used to split the data into two sets (patient with liver disease, or no disease)

Mapping business problem to ML problem
Type of Machine Learning Problem

It is a binary classification problem, where given the above set of features, we need to predict if a given patient has liver disease or not
Evaluation Metric (KPI)

Since this is a binary classification problem, we use the following metrics:

    Confusion matrix - For getting a better clarity of the no of correct/incorrect predictions by the model
    ROC-AUC - It considers the rank of the output probabilities and intuitively measures the likelihood that the model can distinguish between a positive point and a negative point. (Note: ROC-AUC is typically used for binary classification only). We will use AUC to select the best model.
