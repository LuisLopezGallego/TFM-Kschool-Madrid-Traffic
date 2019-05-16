# TFM-Kschool-Madrid-Traffic

This repository contains my TFM about the Traffic evolution in Madrid. it contains an analysis done about the impact of the Madrid Central restriction on the variable traffic intensity in the surrounding areas of Madrid Central.

Important: the files with the data are downloaded from the Notebook 0 with a script.

To be able to follow the process properly, you may need to open and run the files in the repository in the following order:

0. Notebook 0 Data Acquisition: Downloading files with the data => notebook containing a script to GoogleDrive to download the files with the data used for the project

1. Notebook 1 Data Cleaning and Preparation (1): Devices Location => notebook with the code to analyse and visualize the location of the traffic measure devices

2. Notebook 2 Data Cleaning and Preparation (2): Traffic Data => notebook with all the code related to the traffic data from January 2015 to April 2019. Actions performed on each file per month to afterwards concatenating them into a final dataframe with the devices
IMPORTANT: the size of the file per month is heavy and the code last long so in case you want to omit that part of the code I stored also the final csv that concatenates all the monthly files "clean" on a csv named "data_traffic.csv" (see end of Notebook 0)

3. Notebook 3 Analysis (1): Time Series => analytical analysis of the traffic intensity before Madrid Central restriction began and real observations performed for each device chosen from the surrounding area

4. Notebook 4 Analysis (2): Time Series => forecasting traffic intensity of the devices

5. Notebook 5 Visualization and Conclusions: charts summarizing the results and conclusions




