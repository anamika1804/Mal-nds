# Malicious URL Detection using Lexical Features

## Overview
This repository contains code and resources for detecting malicious URLs using lexical features. The problem is approached as a multi-class classification task, where URLs are categorized into different classes such as benign (safe), phishing, malware, or defacement URLs.

## Problem Statement
The primary objective of this case study is to develop machine learning models that can accurately classify URLs based on their malicious intent. To achieve this, lexical numeric features are extracted from the raw URLs, as machine learning algorithms require numeric inputs. Three popular boosting machine learning classifiers are employed for this task: XGBoost, Light GBM, and Gradient Boosting Machines.

## About the Data
The dataset used for training and testing the machine learning algorithms comprises 651,191 URLs, categorized into four classes:

Benign or Safe URLs: 428,103
Defacement URLs: 96,457
Phishing URLs: 94,111
Malware URLs: 32,520
The distribution of these classes is depicted below:

* Benign or Safe URLs: 65.7%
* Defacement URLs: 14.8%
* Phishing URLs: 14.4%
* Malware URLs: 5%
  
The dataset is curated from multiple sources to ensure diversity and adequacy:

1. URL dataset (ISCX-URL-2016): Used for collecting benign, phishing, malware, and defacement URLs.
2. Malware domain black list dataset: Utilized to augment phishing and malware URLs.
3. Faizan's GitHub repository: Used for increasing benign URLs.
4. Phishtank dataset and PhishStorm dataset: Employed to augment phishing URLs.

## Steps:

1. Clone this repository to your local machine.
2. Download the dataset from the provided Kaggle link and place it in the appropriate directory within the repository.
3. Preprocess the data, train models, and evaluate their performance.

## Contributors
Anamika Mallick

