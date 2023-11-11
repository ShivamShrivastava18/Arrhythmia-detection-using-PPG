# Arrhythmia-detection-using-PPG
This is a machine learning model that predicts whether a patient suffers from Atrial Fibrillation or not.
# Purpose
We first started building this as a project for college but when we were researching the topic, we couldn't find any open-source projects. Hence we have decided to make this an open-source project to collaborate with different people to further expland this project. 
# Dataset
The dataset we used was MIMIC PERform AF Dataset taken from https://ppg-beats.readthedocs.io/en/latest/ 
# Method
We took the Time and PPG columns from different patients and added them to single csv file and labelled them as '0' if patient sufferes from AF and '1' if otherwise. Then we are using a decision tree algorithm to train the model. We were getting varied accuracy, everytime we ran the same code so we used a while loop to train the model until we get an accuracy of 85% or above. Then we have taken a random patient's PPG data and ran it through the model to check if the model is working correctly or not.
# Citations 
Charlton PH et al., Detecting beats in the photoplethysmogram: benchmarking open-source algorithms, Physiological Measurement, 2022.
# Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
