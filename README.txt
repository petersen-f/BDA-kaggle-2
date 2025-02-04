===================================================================================================
Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set
Version 2.1
===================================================================================================
Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Luca Oneto(1) and Xavier Parra(2)
1 - Smartlab, DIBRIS - Universit�  degli Studi di Genova, Genoa (16145), Italy. 
2 - CETpD - Universitat Polit�cnica de Catalunya. Vilanova i la Geltr� (08800), Spain
har '@' smartlab.ws 
www.smartlab.ws
===================================================================================================

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. They performed a protocol of activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution. We captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually. The obtained dataset was randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The dataset consists of

- Files with Inertial sensor data: Raw triaxial signals from the accelerometer and gyroscope of all the trials with with participants. 
- A file with labels of all the performed activities.
  

The dataset includes the following files:
=========================================

- 'README.txt'

- 'RawData/Train/acc_expXX_userYY.txt': The raw triaxial acceleration signal for the experiment number XX and associated to the user number YY. Every row is one acceleration sample (three axis) captured at a frequency of 50Hz. 

- 'RawData/Train/gyro_expXX_userYY.txt': The raw triaxial angular speed signal for the experiment number XX and associated to the user number YY. Every row is one angular velocity sample (three axis) captured at a frequency of 50Hz. 

- 'RawData/labels.txt': include all the activity labels available for the dataset (1 per row). 
   Column 1: experiment number ID, 
   Column 2: user number ID, 
   Column 3: activity number ID 
   Column 4: Label start point (in number of signal log samples (recorded at 50Hz))
   Column 5: Label end point (in number of signal log samples)



Notes: 
======
- The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).
- The gyroscope units are rad/seg.
- A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: http://www.youtube.com/watch?v=XOEN9W05_4A


License:
========
Use of this dataset in publications must be acknowledged by referencing the following publications

- Jorge-L. Reyes-Ortiz, Luca Oneto, Albert Sam�, Xavier Parra, Davide Anguita. Transition-Aware Human Activity Recognition Using Smartphones. Neurocomputing. Springer 2015.

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.


Other Related Publications:
===========================

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. 

- Jorge-Luis Reyes-Ortiz, Luca Oneto, Alessandro Ghio, Albert Sam�, Davide Anguita and Xavier Parra. Human Activity Recognition on Smartphones With Awareness of Basic Activities and Postural Transitions. Artificial Neural Networks and Machine Learning � ICANN 2014. Lecture Notes in Computer Science. Springer. 2014.

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra, Jorge L. Reyes-Ortiz. Energy Efficient Smartphone-Based Activity Recognition using Fixed-Point Arithmetic. Journal of Universal Computer Science. Special Issue in Ambient Assisted Living: Home Care.   Volume 19, Issue 9. May 2013

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. 4th International Workshop of Ambient Assited Living, IWAAL 2012, Vitoria-Gasteiz, Spain, December 3-5, 2012. Proceedings. Lecture Notes in Computer Science 2012, pp 216-223. 

- Jorge Luis Reyes-Ortiz, Alessandro Ghio, Xavier Parra-Llanas, Davide Anguita, Joan Cabestany, Andreu Catal�. Human Activity and Motion Disorder Recognition: Towards Smarter Interactive Cognitive Environments. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.  

==================================================================================================
Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita and Xavier Parra. July 2015.

Adapted Aug 2018 for BDA, University of Amsterdam

