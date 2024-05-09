# brainTumorMriAgePrediction
This is a Deep Learning project, consisting of a ResNet50 model that aims to load the LGG dataset from The Cancer Imaging Archive, specifically from The Cancer Genome Atlas and provide a comprehensive classification and prediction system.

We firstly create a loop of dividing and separating all patients from the dataset into specific age groups of which they belong to. The ResNet50 model is then trained, validated and tested on how accurately it is able to predict a patient's age group only from analyzing the patient's respective brain tumor MRI. 

From this project, we want to investigate the impact that brain tumor can have on a deep learning model's ability to precisely predict a patient's age, and whether the model is capable of making such a prediction without focusing on the tumor related brain changes, but on the age related changes. 
