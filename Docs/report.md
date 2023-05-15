# Earthqukae Prediction 

### Data 606 final project report. 

### - Presentation video:
https://youtu.be/IhRtCUs2prk
### - Project PPt:
https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/blob/main/Docs/capstone.pptx

### Introduction:
Natural disasters like earthquakes can do a lot of damage and kill a lot of people. Precise expectation of quakes is fundamental for growing early advance notice frameworks, fiasco arranging, risk appraisal, and logical examination. There are around 18 earthquakes of magnitude 7.0 or higher every year worldwide. Since 1968, actual yearly numbers have ranged from lows of 6-7 incidents each year. But  earthquakes do have a distinct geographical patterns which can help to identify locations and magnitudes of certain future major earthquakes that are going to be produced, even though we are unable to anticipate individual earthquakes.
90% of earthquakes are naturally occurring and the consequence of tectonic action. 10% of the remaining traits are connected to volcanism, human-caused effects, or other factors.

### Dataset: 
The dataset is taken from Northern California Earthquake website. It contains information about earthquakes in California, United States, with a magnitude of 3.0 or greater. 
The dataset contains Earthquake details like Latitude, Longitude, Magnitude, Depth, Time, Azimuthal gap etc. The Data set contains 18030 rows and  13 attributes.

* Date and time of the earthquake in UTC: Date/time
* Latitude and longitude of the epicenter: Lat/Lon
* Depth of the earthquake: Depth
* Magnitude of the earthquake on the Richter scale: Mag
* SRC: Source
* NST: Number of stations used
* CLOSE: Closest station distance
* RMS: Root-mean-squared residual
* GAP: Azimuthal gap

### Preprocessing: 
Removed null values. Dropped all unnecessary unwanted columns.
### Libraries used:
Matplotlib. 
Numpy.
Basemap.
Pandas.
Seaborn.

### Objective:
The objective of earthquake prediction using machine learning is to develop models that can accurately forecast when and where earthquakes may occur. This can help in disaster preparedness, allowing people to evacuate or take necessary precautions to minimize the impact of an earthquake.Through this project i am going to implement a machine learning model for EarthQuake Prediction. 

# Data Visulisation

Python provides several libraries for data visualization, including Matplotlib, Seaborn, Plotly, and Bokeh. These libraries allow you to create a wide range of charts and graphs, including bar charts, line charts, scatter plots, histograms, heatmaps, and more.

Blue color in the map represents the areas where the frequency of earthquake is less and the red color in the map shows frequency of the earthquake is more.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/1500ae4f-8c33-4608-9205-f0eea5d99094)




### Random Forest Model

Random Forest Classifier is an ensemble learning algorithm that combines multiple decision trees to make accurate predictions and reduce overfitting. It is effective for handling large datasets with high dimensionality and is less prone to overfitting compared to other models like Decision Trees.

Based on the latitude, longitude, depth, and number of monitoring stations, we predicted earthquake magnitudes with the random forest algorithm. 
The random forest model was trained on the training data, and its performance on the test data was evaluated using the mean squared error (MSE) and R-squared (R2) score. The data were divided into training and testing sets.


![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/14c587e0-2793-48ac-bbfc-e538eb9a2991)


### Support Vector Machine(SVM)

SVM is a powerful machine learning algorithm used for both classification and regression tasks. It works by finding the hyperplane that best separates the data into different classes, maximizing the margin between the classes. SVM is effective in handling high-dimensional datasets and is less prone to overfitting compared to other algorithms.

It can handle both linear and non-linear data by using different kernels, such as linear, polynomial, and radial basis function (RBF) kernels.
 It can be used to predict the magnitude of a new earthquake given its features, which can be useful for predicting earthquakes in real-time and understanding the factors that contribute to earthquake occurrence.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/7789be36-a57f-4beb-b79a-421ff1858fe3)


### Naive Bayes

Naive Bayes classifier is a simple probabilistic algorithm that is commonly used for classification tasks. It is based on Bayes' theorem, which describes the probability of an event occurring given some prior knowledge or evidence. In the context of classification, Naive Bayes classifier calculates the probability of a data point belonging to a particular class given its features. 

Based on the latitude, longitude, and number of monitoring stations, we predicted earthquake magnitude with the Naive Bayes classifier. We split the information into preparing and testing sets, prepared the Innocent Bayes model on the preparation information, and assessed its exhibition on the test information utilizing the exactness score, disarray grid and characterization report.


![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/827e948e-b05a-4b1b-8352-ccc3056fa22e)
![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/05ba0af7-04ad-428a-825c-316f6fe63c70)

### Confusion Matrix

In machine learning, a confusion matrix is a table that summarizes the performance of a classification model on a set of test data for which the true values are known.The confusion matrix can be used to calculate various metrics to evaluate the performance of a classification model, such as accuracy, precision, recall, and F1-score.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/e2c6b7bc-2936-49f7-bf30-70ac659ddae4)



# Accuracy and Results
When comparing models, both the mean squared error (MSE) and R-squared (R2) score can be used to evaluate the performance of the models.
The results obtained from the random forest model  and  SVM are as follows

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/d7ff7025-af31-4d77-a898-b790cfebc34b)


The accuracy of the Naïve Bayes model is as follows

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sumanth_DATA606/assets/123931726/f931ad03-5d30-49b4-8f77-d4cf6ac4dd21)


# Conclusion

One of the biggest challenges in earthquake prediction is the lack of reliable and consistent data. The occurrence of earthquakes is infrequent and unpredictable, and the data collected from sensors can be noisy and incomplete. Furthermore, earthquakes are influenced by a wide range of factors, including geological, atmospheric, and human factors, which makes it difficult to model the behavior of the system.

From the results of this project, we can conclude that random forest and is the most accurate model for predicting the magnitude of Earthquake compared to all other models used in this project.

# References

### 1. Team, D. (2022, November 28). Earthquake prediction using machine learning. DataFlair.
https://data-flair.training/blogs/earthquake-prediction-using-machine-learning/ 
 
### 2. Earthquake prediction using Hybrid Machine Learning Techniques. (n.d.).
https://www.researchgate.net/publication/352414816_Earthquake_Prediction_using_Hybrid_Machine_Learning_Techniques 

### 3. Martins, G. (2023, February 12). Predicting earthquakes using machine learning. Medium. 
https://medium.com/marionete/predicting-earthquakes-using-machine-learning-21689435dc52 

### 4. Predicting earthquakes may soon be possible with machine learning. DUG Technology. (2022, April 21). 
https://dug.com/predicting-earthquakes-may-soon-be-possible-with-machine-learning/ 
