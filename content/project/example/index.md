---
title: Heart Diseases Prediction
summary: Heart diseases prediction via six different ML models.
tags:
  - ML
date: '2023-09-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/hakancelik/Happy_Hearts_capstone_Miuul
url_code: 'https://happyheartscapstonemiuul.streamlit.app'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

project_description:
  dataset_info: >
    This dataset is from a 1988 study and contains four databases: Cleveland, Hungary, Switzerland, and Long Beach.
    The dataset consists of 1024 observations and 14 variables, with the "target" variable indicating the presence of heart disease.
    It is an integer value where 0 = no disease and 1 = disease present.
  project_purpose: >
    This project is a simple Streamlit web application based on users predicting the probability of heart disease based on their characteristics.
    The prediction is made using a machine learning model trained on heart disease data.
  result_description: >
    As a result, when the user selects all the features and clicks the "Predict" button, the application will display the predicted outcome and indicate whether the prediction is positive or negative for heart disease.
variable_description:
  - name: age
    description: Age
  - name: sex
    description: Gender (0: Female - 1: Male)
  - name: cp
    description: Chest Pain Types (0: Typical angina - 1: Atypical angina - 2: Non-anginal pain - 3: Asymptomatic)
  - name: trestbps
    description: Resting Blood Pressure
  - name: chol
    description: Cholesterol (mg/dl)
  - name: fbs
    description: Fasting Blood Sugar (0: < 120 mg/dl - 1: > 120 mg/dl)
  - name: restecg
    description: Resting Electrocardiographic Results (0: Normal - 1: ST-T wave abnormality - 2: Probable or definite left ventricular hypertrophy)
  - name: thalach
    description: Maximum Heart Rate Achieved
  - name: exang
    description: Exercise Induced Angina (0: No - 1: Yes)
  - name: oldpeak
    description: ST Depression Induced by Exercise Relative to Rest
  - name: slope
    description: The Slope of the Peak Exercise ST Segment (0: Upsloping - 1: Flat - 2: Downsloping)
  - name: ca
    description: Number of Major Vessels (0-3)
  - name: thal
    description: Thalassemia, Blood Disorder (0: Normal - 1: Fixed defect - 2: Reversible defect)
  - name: target
    description: Presence of Heart Disease (0: No - 1: Yes)
