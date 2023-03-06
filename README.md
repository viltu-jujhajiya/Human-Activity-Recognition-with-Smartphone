# Human-Activity-Recognition-with-Smartphone
A machine learning model to detect activity using data which is collected by accelerometer and gyroscope of smartphone. The model uses 3-dimentional smartphone accelerometer and gyroscope as the only sensors to collect time series signals.   

## Data
Data was collected from the recordings of 30  study participants performing activities of daily living while carrying a waist-mounted smartphone (Samsung Galaxy S II) with embedded inertial sensors. The objective is to classify activities into one of the following six activities performed. Using its embedded accelerometer and gyroscope, they captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.  

Six Activities: {WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING}  

Dataset Link: https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones  


## Machine Learning Methods
For activity classification, used predefined version of two ML techniques in sklearn  
(i) Logistic Regression: Test Accuracy : 95.80%   
(ii) Support Vector Machine (rbf Kernel):  Test Accuracy : 96.17%
