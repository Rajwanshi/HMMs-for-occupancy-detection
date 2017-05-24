# HMMs-for-occupancy-detection
Repository hosting the files for "A methodology based on Hidden Markov Models for occupancy detection and a case study in a low energy residential building. Luis M Candanedo, Veronique Feldheim, Dominique Deramaix. Energy and Buildings. 148 (2017) 327-341" 

All the files will be uploaded shortly! Thank you for your patience.

The Evaluation_of_HMM_performance_time_influence_3.Rmd  file has the scripts to produce the html file (which you can see in any browser after downloading it). It has the results reported in the tables in the paper for the accuracies of the different models for different time windows.

Download all the files and put them in a directory. 
Then, modify the file Evaluation_of_HMM_performance_time_influence_3.Rmd to replace the line that sets the working directory)

     setwd("D:/Dropbox/Occupancy_estimation/data_occupancy_detection") 

Also do not forget to install the required libraries: lubridate, openair, depmixS4, plyr,caret.

After doing that you are ready to run the Evaluation_of_HMM_performance_time_influence_3.Rmd file and should get you the same results as the one in the Evaluation_of_HMM_performance_time_influence_3.html file.
 
