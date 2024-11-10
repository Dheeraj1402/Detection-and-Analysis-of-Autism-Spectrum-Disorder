# Detection-and-Analysis-of-Autism-Spectrum-Disorder

# Overview

This Autism Spectrum Disorder (ASD) Detection Project follows a structured workflow to analyze, preprocess, and model data for identifying ASD traits. First, Exploratory Data Analysis (EDA) is conducted to understand feature distributions, relationships, and potential predictors. In Data Preprocessing, missing values are handled, categorical variables are encoded, and numerical features are normalized before splitting the data into training and testing sets. Random Forest algoritm is trained and evaluated based on accuracy, precision, recall, and F1-score. Finally, visualizations like confusion matrices, ROC curves, and feature importance charts are used to interpret model results effectively.

# Features in the Dataset

CASE_NO_PATIENT'S: Unique identifier for each patient case.

A1-A10: Scores for individual questions on the Autism Spectrum Quotient (ASQ), a measure for assessing autistic traits.

Autism_Spectrum_Quotient: Total score on the ASQ, indicating the level of autistic traits.

Social_Responsiveness_Scale: Score indicating the individual’s social responsiveness, used to gauge social and communication skills.

Age_Years: Age of the individual in years.

Qchat_10_Score: Score on the Quantitative Checklist for Autism in Toddlers (Q-CHAT-10), assessing autism traits in young children.

Speech Delay/Language Disorder: Indicates if the individual has a history of speech or language disorders (Yes/No).

Learning disorder: Indicates the presence of a learning disorder (Yes/No).

Genetic_Disorders: Specifies if the individual has any known genetic disorders (Yes/No).

Depression: Indicates if the individual has a history of depression (Yes/No).

Global developmental delay/intellectual disability: Indicates developmental delays or intellectual disabilities (Yes/No).

Social/Behavioural Issues: Indicates the presence of social or behavioral issues (Yes/No).

Childhood Autism Rating Scale: Score on the Childhood Autism Rating Scale (CARS), which is a diagnostic assessment for autism.

Anxiety_disorder: Indicates if the individual has a history of anxiety disorders (Yes/No).

Sex: Biological sex of the individual (Male/Female).

Ethnicity: Ethnic background of the individual.

Jaundice: Indicates if the individual had neonatal jaundice (Yes/No).

Family_mem_with_ASD: Indicates if there is a family member with ASD (Yes/No).

Who_completed_the_test: Specifies who completed the ASD test (e.g., parent, teacher, or self).

ASD_traits: Label indicating if the individual shows traits associated with ASD (Yes/No), serving as the target variable for the model.

# Files in the Repository

Code Files

ASD.ipynb: Jupyter notebook for Exploratory Data Analysis (EDA), containing data preprocessing,visualizations,data preprocessing,model training and evaluation.

Dataset

ToddlerAutism.csv: The dataset file used for training and testing the model, containing features related to demographic, behavioral, and diagnostic information for ASD detection.

Research Paper

GMRIT_IEEE.docx: IEEE research paper titled "Analysis and Detection of Autism Spectrum Disorder (ASD) using Machine Learning," presented at AI-PTIS-2024.

Certificate

AI-PTIS-2024_0891.pdf: Conference certificate issued by GMR Institute of Technology, Andhra Pradesh, certifying the presentation of the ASD detection paper.

