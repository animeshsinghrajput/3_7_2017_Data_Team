# 3_7_2017_Data_Team

# 1.Vehicle Prediction Test

Given a corpus of metal-content readings and controlled testing environments, build a classification engine that can then be used to predict the type of vehicle travelling on top of that meta. Assume a single metal strip and assume all vehicles are travelling at around 15KM/hr. Assume that input files are provided one set each for a (a) bus (b) car (c) motorbike, with each category having distinct average metal readings.


For example, the corpus has the following readings for various time instances, where subsequent time instances are separated by 1 second. First column is time, second is Ampere rating, third column says what vehicle it is.


# Input data sample for one metal reading: 
* 1, 0.0, -
* 2,-0.05, -
* 3,0.1, -
* 4, 0.5, Motorbike
* 5, 0.4, Motorbike
* 6, 0.0, -
* 7, 1.5, Bus
* 8, 1.55, Bus
* 9, 1.29, Bus
* 10, 1.62, Bus
* 11, -0.09, -
* 12, -0.01, -
* 13, 5.5, Car
* 14, 5.66, Car
* 15, 4.58, Car
* 16, 0.3, -
* 17, 0.2, -


# Question 3.1: Build a classification engine for being able to correctly classify given a set of readings the category they belong to. Note that, as per data above, different vehicles induce readings of differing lengths on the metal.
 
# Question 3.2: Demonstrate how that classification engine can be used for prediction given unclassified data.
 
# Question 3.3: How would you change the model building approach if the problem setting is such that there are multiple metal detectors each covering a width of about 1 feet? Note that while a motorcycle is of width < 1 feet, a bus or a car have a width of at least 3 feet and so would span to cover multiple metal detectors.
 
# Question 3.4: How would your predictive model  (built in Question 2) perform when there are 1000s of vehicles moving at 60km/hr every second on a national highway? 
