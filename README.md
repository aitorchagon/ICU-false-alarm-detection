# ICU-false-alarm-detection

We participated on a Kaggle challenge as part of our learning process in Physiological Signal Processing. 
We ended at top 5 of our class, out of 34 groups (each of them being composed of 3/4 people).

The main objective of this project was to address the high false alarm rates in the ICU when trying
to predict an arrhytmia.

The data set comprises monitor signals from ICU with labeled arrhythmia alarms.
We used as a classifier a Naive Bayes (as was specified in the subject) and analyzed very 
different features to get the best possible metrics.

We ended up using heart rate mean and standard deviation over the second channel,
several heart rate variability statistics over the second and the fifth (such as
the mean, the standard deviation or the entropy), obtaining a 0.68 on the public leaderboard
and a 0.74 on the private and final one.

The packages employed to design the algorithm are enumerated as follows:
-Numpy.   
-Scipy, especially the signal subpackage.     
-Matplotlib (the pyplot visualization tool).   
-Pandas.    
-Biosspy.   
-PyHRV.   
-Neurokit2.    
-HRV.   
-Heartpy.   
-Neurokit (an older version of neurokit2).   

