# Consciousness-access-and-heart-rate
The file contained behavioral data, ECG data and their codes to analyze them.
Behavior analysis
Using the code in the text file of "Behavior Analysis" to analyze the "rt_gz1.mat" data.
"mark_gz1.xlsx" represents the time of presenting stimulus (1, tilted to the left; 2, tilted to the right) and making response (4, correct response; 8, wrong response) during the experiment.
"event_gz1.mat" is divided into two mat files, trg (time) and conds (correct response).

Data modeling
Data: In the behavioral data (rtgz.csv), subj_id represents the number of the subject, rt represents the response of the corresponding conscious detection of the subject, angle represents the tilt Angle of the target stimulus, and response represents the choice (1, left; 2, right). 
Code: The "Data Modeling.txt" code from the site-https://hddm.readthedocs.io/en/latest/ was ran by the jupyter notebook ( a web-based application of Python3 for interactive computing) 

ECG analysis
We can obtain the "rr_gz1.txt", "qrs_gz1.txt" and "ecg_gz1" by running the code of "ECG_processing.txt" in MATLAB or from the ACKNOWLEGE software. In the file of “Pre- and Post- Stimulus Heart Rate Analysis.txt”, we can output the pre- or post stimulus heart rate. In the file of "Binary Analysis.txt", we can output the reaction time both in the diastole and in the systole.

Please feel free to contact me if you have any questions about the data operation. My email is mscnuysf@163.com.
