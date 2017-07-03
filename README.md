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
