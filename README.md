## Malicious URL Detection using Lexical Features

#Overview
This repository contains code and resources for detecting malicious URLs using lexical features. The problem is approached as a multi-class classification task, where URLs are categorized into different classes such as benign (safe), phishing, malware, or defacement URLs.

#Problem Statement
The primary objective of this case study is to develop machine learning models that can accurately classify URLs based on their malicious intent. To achieve this, lexical numeric features are extracted from the raw URLs, as machine learning algorithms require numeric inputs. Three popular boosting machine learning classifiers are employed for this task: XGBoost, Light GBM, and Gradient Boosting Machines.

#About the Data
The dataset used for training and testing the machine learning algorithms comprises 651,191 URLs, categorized into four classes:

Benign or Safe URLs: 428,103
Defacement URLs: 96,457
Phishing URLs: 94,111
Malware URLs: 32,520
The distribution of these classes is depicted below:

Benign or Safe URLs: 65.7%
Defacement URLs: 14.8%
Phishing URLs: 14.4%
Malware URLs: 5%
The dataset is curated from multiple sources to ensure diversity and adequacy:

URL dataset (ISCX-URL-2016): Used for collecting benign, phishing, malware, and defacement URLs.
Malware domain black list dataset: Utilized to augment phishing and malware URLs.
Faizan's GitHub repository: Used for increasing benign URLs.
Phishtank dataset and PhishStorm dataset: Employed to augment phishing URLs.
Repository Contents
Data Preprocessing: This section contains scripts and notebooks for cleaning and preprocessing the raw data. It involves tasks such as merging data from different sources, handling missing values, and encoding textual URLs into numerical features.

Model Development: Here, machine learning models using XGBoost, Light GBM, and Gradient Boosting Machines are trained and evaluated. Different feature engineering techniques and hyperparameter tuning approaches may be explored in this section.

Evaluation: This section focuses on evaluating the performance of trained models using various metrics such as accuracy, precision, recall, and F1-score. Visualizations may also be provided to gain insights into model behavior and performance across different classes.

Deployment: If applicable, scripts or instructions for deploying the trained models into production environments may be provided in this section.

Documentation: This includes a comprehensive README file (like this one) providing an overview of the project, instructions for replicating the results, and any additional information deemed necessary for users or contributors.

Usage
To replicate the experiments and results presented in this repository, follow these steps:

Clone this repository to your local machine.
Install the required dependencies listed in the requirements.txt file.
Download the dataset from the provided Kaggle link and place it in the appropriate directory within the repository.
Follow the instructions in each section of the repository to preprocess the data, train models, and evaluate their performance.
Contributors
Anamika Mallick

