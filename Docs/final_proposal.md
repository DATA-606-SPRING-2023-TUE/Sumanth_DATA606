# Introduction
There are around 18 earthquakes of magnitude 7.0 or higher every year worldwide. Since 1968, actual yearly numbers have ranged from lows of 6-7 incidents each year. There are no particular symptoms/signs to know when and where the earthquakes will happen. But  earthquakes do have a distinct geographical patterns which can help to identify locations and magnitudes of certain future major earthquakes that are going to  be produced, even though we are unable to anticipate individual earthquakes.

90% of earthquakes are naturally occurring and the consequence of tectonic action. 10% of the remaining traits are connected to volcanism, human-caused effects, or other factors. Natural earthquakes are ones that happen naturally and are frequently a lot stronger than other types of earthquakes. The two theories that deal with earthquakes are the continental drift hypothesis and the plate-tectonic theory.

# Why it is Important?

Since they may seriously harm buildings, infrastructure, and people, earthquakes are vital to anticipate. Earthquakes can happen without much notice, and their effects can be catastrophic.

By foreseeing earthquakes, scientists may warn inhabitants in vulnerable locations and develop early warning systems that can lessen the effects of an earthquake. This may entail taking countermeasures to safeguard people and property, such as locking down transit hubs and ordering the evacuation of buildings.

Scientists can get a better understanding of the nature of earthquakes and the underlying geology that drives them by making earthquake predictions. This may result in improved earthquake predicting and mitigation techniques, such as enhanced construction regulations and emergency preparedness plans.

Ultimately, being able to forecast earthquakes is a crucial step in minimizing the harm and fatalities brought on by these natural catastrophes.

# Dataset

The dataset is taken from here https://raw.githubusercontent.com/amankharwal/Website-data/master/database.csv. There are 23412 rows and 21 colums.

It is very difficult to predict Earthquakes. The impact of an earthquake can differ depending on a number of variables, including the size of the earthquake, its depth, its epicentre’s location, and the local geology.

* Magnitude: The earthquake's magnitude, which is a measurement of the energy released at its source, is shown in this column. Normally, it is measured using the Richter scale, which has a range of 0 to 10.

* Depth: This column displays the depth at which the earthquake occurred, which is crucial information for estimating the quake's potential effects on the surface.

* Location: This column shows the earthquake's geographic coordinates, which can be used to pinpoint areas that are more likely to experience earthquakes.

* Time: The earthquake's time of occurrence is shown in this column, which can be used to spot patterns in the timing of seismic activity.

* Distance: This column shows the separation between the earthquake's epicentre and the closest recognized fault.
Latitude: Latitude is a geographic coordinate that indicates a point's north-south location on the surface of the Earth. It is measured in degrees, with the equator at 0° and the poles at 90°.

* Longitude: The east-west location of a point on the surface of the Earth is indicated by the longitude geographic coordinate. From 0° at the Prime Meridian to 180° East or West, it is measured in degrees.

* Horizontal Error: The horizontal error, which is typically expressed in kilometres, is the estimated error in the horizontal location of an earthquake. It stands for the uncertainty surrounding the epicentre’s location.

* Horizontal Distance: The distance between two points on the surface of the Earth measured in a horizontal plane is known as the "horizontal distance."
Root Mean Square: The root mean square (RMS) is a measurement of the earthquake waveform's overall amplitude. It is the average of the squared seismic signal values, expressed as a square root.

* Azimuthal Gap: The angle between the two stations reporting an earthquake that are the farthest apart is known as the azimuthal gap. It is employed to determine the seismic network's azimuthal coverage and the precision of the earthquake's location.

* Depth Error: The depth error, which is typically expressed in kilometres, is the estimated error in the earthquake's depth. It symbolizes the ambiguity surrounding the hypocentre of an earthquake, which is where the earthquake originates on Earth.

To predict the occurrence, location, magnitude, and other characteristics of earthquakes, machine learning algorithms can use any or all of these parameters as input features. Machine learning algorithms can learn to recognize patterns and forecast future earthquakes by examining historical earthquake data and other pertinent data sources.



# Machine Learning Models to predict the Earth Quakes

## Random Forest

It is a classification method that also makes use of ensemble learning. The main contrast between the random forest and the decision tree is how the random forest creates a root node feature by randomly splitting. The Random forest selects a random characteristic to increase its accuracy. The random forest method moves more quickly than the bagging and boosting technique.

## Gradient Boosting Algorithm

Gradient boosting machines (GBMs), sometimes known as simply GBMs, employ a learning process that successively fits new models to provide a more accurate estimate of the response variable. The basic idea behind this technique is to construct the new base learners with as much similarity to the ensemble's overall negative gradient of the loss function as feasible. It is possible to choose the loss functions at random.

## Nueral Network

A neural network is an artificial intelligence technique that teaches computers to process data in a way  inspired by the human brain. It's a type of machine learning, called deep learning, that uses interconnected nodes or neurons in a layered structure similar to the human brain.

# Developing Model

My plan is to develop machine learning model which is faster and gives the accurate prediction of Earth Quake. I am going to use all the models which are given above and give the faster prediction of Earth Quakes.

