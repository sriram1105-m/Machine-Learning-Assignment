# Machine-Learning-Assignment

**Aim:**

Aims of this assignment are: 

a) to learn to identify machine learning techniques appropriate for a particular practical problem.

b) to undertake a comparative evaluation of several machine learning procedures when applied to the specific problem.

**NOTE: The zip files contains the dataset used in this problem**

**Identification of the problem type:**

The given type of problem is a binary classification type problem. Here, in this problem we need to predict whether the customers of travel insurance company would make a future claim or not. There are two possible outcomes which are as follows. Either the customer would make an insurance claim or the customer will not make the claim. So, this type of problem is a Binary classification problem. Binary classification is the type of machine learning problem where the goal is to categorize the data points in one of the two cases, here in our case it is either true or false.

**Requirement of data features for analyses:**

In order to make a perfect prediction for the travel insurance claim, the following features are required.

They are 
•	Age of the insured

•	Gender of the person 

•	Frequency of travel 

•	Coverage for medical expenses 

•	Personal injury 

•	Accident coverage 

•	Lost or delayed baggage

•	Coverage for cancellation and curtailment

•	Distribution channel (online or offline)

•	Insurance product type

•	Duration of travel

•	Travel destination

•	Number of trips in the next 12 months

•	Single trip or Multiple trip 

•	Local or worldwide coverage

•	Individual or family coverage

•	Personal liability coverage

•	Holiday or trip duration

•	Requirement of specialist policy or not

•	Transportation mode for travel

•	Coverage against burglary when you are away

•	Other coverages (sports equipment insurance, cover for disaster or unexpected events etc.)

**The Learning Procedure:**

In order to make a good prediction whether the customer will claim travel insurance or not, I am suggesting to use SVM Classifier (Support Vector Machine). 

Support Vector Machine classifier is a supervised machine learning algorithm that can be used in our classification problem. The reason for choosing SVM algorithm is that, if the data points are not linearly separable, then it is a good practice to use SVM classifier to make the prediction. Support Vector Machine uses a technique called kernel trick that can transform the data and based on this transformation it will find an optimal boundary between the possible outputs. This algorithm performs extremely complex data transformations and then figures a way out to separate the data points based on the labels.

The kernel trick offers more efficient and less expensive way to transform the data into higher dimensions.

Reasons to use SVM classifier algorithm:

•	It can be used for the data points that are highly overlapped between the classes.

•	SVM algorithm can avoid overfitting.

•	The influence of outliers in SVM algorithm is less when compared with other machine learning algorithms.

•	The prediction time of SVM algorithm is faster along with better accuracy.

**Performance Evaluation:**

Before model deployment, the performance of the model should be analyzed. Since, this type of problem falls under classification type, there are three most important performance evaluation metrics that needs to be considered.

They are Classification Accuracy, Accuracy by class and Confusion Matrix.

**Classification Accuracy:**

Classification accuracy is the number of correct predictions out of the total number of predictions made.

**Accuracy by Class:**

This can be found out by making a note of the True Positive and False Positive rates for each class obtained from Confusion Matrix. 

**Confusion Matrix:**

A Confusion matrix is a table that tells us how good the model has performed. Confusion matrices are useful because they give direct comparison of values like true positives, false positives, true negatives and false negatives. Confusion matrices are used to visualize some more important predictive analytics like recall, precision, specificity and accuracy.  

