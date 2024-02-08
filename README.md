# Predicting heart disease using machine learning

This notebook looks into using varius Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of prediction whether or not someone has heart disease based on their medical attributes.

Approach:

1. Data
2. Evaluation
3. Features
4. Modelling
5. Experimentation

## Data

Came from here: https://archive.ics.uci.edu/dataset/45/heart+disease

## Evaluation

> Attempt to reach a 95% accuracy prediction

## Features

1.  (age) Years

2.  (sex) 1 = male, 0 = female

3.  (cp) - chest pain type

    - 0: Typical angina: chest pain related decrease blood supply to the heart
    - 1: Atypical angina: chest pain not related to heart
    - 2: Non-anginal pain: typically esophageal spasms (non heart related)
    - 3: Asymptomatic: chest pain not showing signs of disease

4.  (trestbps) Resting blood pressure

5.  (chol) Serum cholestoral in mg/dl

6.  (fbs) Fasting blood sugar (fbs > 120 mg/dl) (1 = true, 0 = false)

7.  (restecg) Resting electrocardiographic results

8.  (thalach) maximum heart rate achieved

9.  (exang) exercise induced angina (1 = yes; 0 = no)

10. (oldpeak) ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more

11. (slope) the slope of the peak exercise ST segment

    0: Upsloping: better heart rate with excercise (uncommon)
    1: Flatsloping: minimal change (typical healthy heart)
    2: Downslopins: signs of unhealthy heart

12. (ca) number of major vessels (0-3) colored by flourosopy

    colored vessel means the doctor can see the blood passing through
    the more blood movement the better (no clots)

13. (thal) thalium stress result

    1,3: normal
    6: fixed defect: used to be defect but ok now
    7: reversable defect: no proper blood movement when excercising

14. (target) - have disease or not (1=yes, 0=no) (= the predicted attribute)
