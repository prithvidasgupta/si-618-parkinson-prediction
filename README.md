#  Parkinson's Disease Progression Prediction

We propose to predict the progression of Parkinson's Disease (PD) using protein and peptide data measurements. Parkinson's Disease is a chronic and progressive neurological disorder that affects movement, causing symptoms such as tremors, stiffness, and impaired balance and coordination. It is the second most common neurodegenerative disorder, affecting approximately 1% of people over the age of 60. Early and accurate prediction of disease progression can help healthcare providers plan and adjust treatment regimens accordingly, including medications, physical therapy, and surgical interventions. It can also help patients and their caregivers better understand what to expect in terms of symptoms and disease trajectory.

The progression in patients with PD is measured by MDS-UPDRS (Movement Disorder Society-Sponsored Revision of the Unified Parkinson's Disease Rating Scale), which is a comprehensive assessment of both motor and non-motor symptoms associated with Parkinson's. We plan to develop a model trained on data of protein and peptide levels over time in subjects with Parkinson’s disease.

We believe this work could help provide important breakthrough information about which molecules change as Parkinson’s disease progresses.

## Team members
* Prithvijit Dasgupta (prithvid)
* Nowrin Mohamed (nowrin)
* Sachin Salim (sachinks)

# Steps to run the code:

1. eda.ipynb - Exploratory data analysis of all 4 datasets present in the project with basic manipulation and also visualization.

2. main.ipynb - Preprocessing, data transformation, and all the ML models are present in this file.

3. data\ - contains the original train_clinical_data.csv, supplemental_clinical_data.csv, train_proteins.csv and train_peptides.csv data. In addition to this, it contains the processed data as peptides_features.csv and proteins_features.csv
