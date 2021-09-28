Description:

This project is used to predict US traffic accidents severity based on weather conditions like visibility, temperature, and weather categories as well as based on US location and the day of the week. 

This project can be used for numerous applications such as real-time accident severity prediction based on environment factors. 
Studying accident hotspot locations and their severity.

-->Rich data with almost 3.5 million rows
-->Needed pre-processing 
-->Severity contained in data is prone to errors
-->Weather condition categorization may not be accurate
-->Data is imbalanced

Data Cleaning:

-->Select important features and remove unnecessary columns.
-->Remove the rows with null values.
-->Do data profiling to validate correctness of data.

Data Pre-processing:

-->Convert columns with text field to numerical data, One hot encoding
-->Categorized weather conditions
-->Eliminated rows that greatly contributed to the imbalance of the data and were not significant in volume
-->Replaced null values with fillers and dropped some of the rows and columns with more missing values

Features:

Latitude, Longitude, Temperature(F), Visibility(mi), Weather_Category(Rain, Cloudy, slippery etc..), Weekday,Start_Time,Start_Lat,Distance(mi)

Machine Learning Models:

-->Logistic Regression
-->Decision Trees
-->Random Forest

Attempts to achieve good accuracy:

-->Trained the model with 80% of data
-->Tested Accuracy for all models using test data
-->Generated classification reports
-->Generated feature importance

Logistic Regression:

Training Accuracy: 91.7%
Testing Accuracy: 92.1%


Decision Tree Classifier:

Training Accuracy: 100%
Testing Accuracy: 97%

Random Forest: 

Training Accuracy: 99.6%
Testing Accuracy: 99.5% 

Tools and Technology:

Jupyter notebook, Pandas, Scikit-learn

Commands to run the code:

-->We have shared the kaggle link of the notebook and dataset in the google form.
-->Dataset link : https://www.kaggle.com/sobhanmoosavi/us-accidents
-->Kaggle notebook link : https://www.kaggle.com/harshapriyacr/022-da-hmp-co


Acknowledgements:

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

Team members:

Harshapriya C R
Narpala Meghana Reddy
Priyanka G

