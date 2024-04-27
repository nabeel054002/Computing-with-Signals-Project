We have our inputs for training and testing in the train and test folders respectively

We define 9 features, that vary across time, and have to give an output of size 6, which defines what action are we talking about 

'train/Inertial Signals/total_acc_x_train.txt': The total acceleration signal

'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.

Similarly for other directions y and z, and also for the testing case.
The units used for the accelerations (total and body) are 'g's (gravity of earth = 9.80665 m/seg2).
The gyroscope units are rad/seg. 

Input consists of 9 inputs/features, across 128 timesteps

Output is a single size 6 column vector that shows the activity in the 128 timesteps - time frame

