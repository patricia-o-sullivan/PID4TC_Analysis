# PID4TC (Pressure insoles for Task Classification)
20 subjects carried out 5 tasks while wearing loadsol pressure insoles: manual handling, pick and place, assembly, walking and standing. Time and frequency domain features were extracted from raw force data (also publicly available) to create new data bases of varied window lengths - 2, 3, 4, 5, 6, 8, 10, 12 and 15 seconds. Using tehe attached code, the databases were analysed across a 10 fold cross-validation and random forest classifier across all windows. A re-analysis was completed for the top 5 performing features. Accuracies over 80% were observed for all time windows.

This repository contains the (1.) Databases of extracted features for each subject and time window, and (2.) The analysis code. 
Raw data can be found at https://zenodo.org/record/7755802 (doi: 10.5281/ZENODO.7755802).
The associated publication in IEEE Sensors Journal can be found at link (doi).

The files within the database follow the format Sub1Features_L_2, in this case 1 denotes the subject number and 2 denotes the window size in seconds (200 frames).
The analysis code is named PID4TC_Analysis.

