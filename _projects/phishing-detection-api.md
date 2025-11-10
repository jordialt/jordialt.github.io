---
layout: project
title: Phishing Detection API
permalink: /projects/phishing-detection-api/
description: A web service API for classifying URLs as phishing or legitimate using various trained Machine Learning models (Logistic Regression, Random Forest, XGBoost).
category: fun
# Add a custom image here (e.g., img: assets/img/phishing-detection.png)
# img: 
github: jordialt/phishing-detection-api
# website: # Add a link to a live demo of the API if it's deployed
---

This project focuses on building a robust, lightweight **Machine Learning API** capable of detecting phishing websites based on URL features.

The workflow involved:
* **Data Acquisition and Processing:** Sourcing and preparing a phishing dataset.
* **Model Training and Evaluation:** Training multiple classification algorithms (Logistic Regression, Random Forest, and XGBoost) and comparing their performance using metrics like the F1 score and confusion matrices.
* **API Deployment:** Serving the best-performing model (or a lightweight version) via a Python API.

This project was a great exercise in applying end-to-end data science to a practical cybersecurity problem.
