# EY NextWave Challenge
Partial Trajectory Prediction model for civilian movements around city centre area.

- The dataset featured anonymized GPS information for a set of people in the state of Georgia during October 2018 in the form of partial trajectories. 

- Our task was to use this data to predict if the person would have a destination inside the “city centre” (x,y) boundary. 

- All GPS trackers reset every 24 hours so each day of data was completely independent and untraceable to previous recordings. 

# Method
1.	I researched papers previous methods used to tackle this topic. 

2.	I concluded that people at similar positions tend to be going to the same destination (IBM Taxi Destination problem).

3.	I developed a KNN algorithm on (x,y) coordinate data as it was a very effective method that required the least amount of time. 

4.	I eliminated variables that were not relevant and only served to overcomplicated the model.

5.	I explored a variety of numerical values for ‘K’ with different distance metrics and training data sampling techniques.

6.	Possible implementations of my solution include targeted advertising, urban planning, rideshare services and various augmented reality uses.

# Visualisation of the Problem

![Image of framework](https://github.com/jackapbutler/EY-NextWave-Challenge/blob/master/ey_nextwave.png)
