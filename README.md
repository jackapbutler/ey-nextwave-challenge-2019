# NextWave_EY_Challenge
Partial Trajectory Prediction for movements around city centre

The data set featured anonymized GPS information for a set of people in the state of Georgia during October 2018 in the form of partial trajectories. Our task was to use this data to predict if the person would have a destination inside the “city centre” (x,y) boundary. All GPS trackers reset every 24 hours so each day of data was completely independent and untraceable. 

Method
1.	Researched papers and ideas surrounding this topic and the wider picture.
2.	Concluded that people at similar positions tend to be going to the same destination (IBM paper).
3.	A KNN on (x,y) coordinate data of people was a relatively simple method that required the least amount of time. 
4.	I eliminated variables that were not relevant and only over complicated the model.
5.	I explored a variety of ‘K’ models with different distance metrics and training data samples.
6.	Possible implementations include targeted advertising, urban planning, rideshare services and augmented reality uses.
