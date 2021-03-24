# EY NextWave Challenge 2019
Partial Trajectory Prediction model for civilian movements around a city centre area.

- The dataset featured anonymized GPS information for a set of people in the state of Georgia during October 2018 in the form of partial trajectories. 

- The task was to use this data to predict if the person would have a destination inside the “city centre” (x,y) boundary. 

- All GPS trackers reset every 24 hours so each day of data was completely independent and untraceable to previous recordings. 

- My final model placed me in the top 10 in UK & Ireland and top 250 globally with a F1 score of 0.869 and Accuracy of 0.95.

# Visualisation of the Problem

![Image of framework](https://github.com/jackapbutler/EY-NextWave-Challenge/blob/master/ey_nextwave.PNG)

# Method
1.	I researched previous publications that tackled similar topics. 

2.	I concluded that people who start at similar positions tend to be going to the same final destination (IBM Taxi Destination paper).

3.	I developed a KNN algorithm on (x,y) coordinate data as it was a very effective method that required the least amount of time to implement and tweak. 

4.	I eliminated any variables that were not relevant and only served to overcomplicated the data.

5.	I explored a variety of numerical values for ‘K’ while also varying the distance metric and training data sampling techniques.

6.	Possible real world uses of my solution include targeted advertising, urban planning and rideshare services.
