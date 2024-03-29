# PID4TC (Pressure insoles for Task Classification)
20 subjects carried out 5 tasks while wearing loadsol pressure insoles: manual handling, pick and place, assembly, walking and standing. Time and frequency domain features were extracted from raw force data to create new data bases of varied window lengths - 2, 3, 4, 5, 6, 8, 10, 12 and 15 seconds. Using the files in this repository, the databases were analysed across a 10-fold cross-validation and random forest classifier for all windows. A re-analysis was completed with the top 5 performing features. Accuracies over 80% were observed for all time windows.

This repository contains the (1.) Databases of extracted features for each subject and time window, named PID4TC_FeatureDatabase; and (2.) The analysis code, named PID4TC_Analysis.
Raw data can be found at https://zenodo.org/record/7755802 (doi: 10.5281/ZENODO.7755802).
The associated publication in can be found at link (doi).

The files within the database follow the format Sub1Features_L_2, in this case 1 denotes the subject number and 2 denotes the window size in seconds (200 frames).
The analysis code is named PID4TC_Analysis.

