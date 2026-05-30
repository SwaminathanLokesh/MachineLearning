# K-Nearest Neighbors (KNN) Classification on Titanic Dataset

## Project Overview

This project implements the K-Nearest Neighbors (KNN) algorithm to predict passenger survival on the Titanic dataset. The dataset contains information about passengers such as age, gender, passenger class, and fare. The objective is to classify whether a passenger survived or not.

## Dataset

The Titanic dataset contains details of passengers aboard the Titanic.

### Features Used

* **Pclass** – Passenger class (1, 2, 3)
* **Sex** – Gender of the passenger
* **Age** – Age of the passenger
* **Fare** – Ticket fare

### Target Variable

* **Survived**

  * 0 = Not Survived
  * 1 = Survived

## Steps Performed

### 1. Data Loading

The Titanic dataset was loaded using the Seaborn library.

### 2. Exploratory Data Analysis (EDA)

* Checked dataset structure
* Identified missing values
* Visualized survival distribution
* Analyzed survival based on gender and passenger class
* Studied age distribution

### 3. Data Preprocessing

* Filled missing values in the Age column using the median value
* Encoded categorical variables into numerical form
* Selected relevant features for model training

### 4. Feature Scaling

StandardScaler was applied to normalize feature values because KNN is a distance-based algorithm.

### 5. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 6. KNN Model Training

The K-Nearest Neighbors classifier was trained using different values of K to determine the optimal number of neighbors.

### 7. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## Algorithm Used

K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm used for classification and regression tasks. It classifies a new data point based on the majority class of its K nearest neighbors.

## Results

The trained KNN model successfully predicted passenger survival and achieved a satisfactory accuracy score on the test dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-Learn

## Conclusion

This project demonstrates the application of the KNN classification algorithm on the Titanic dataset. Through preprocessing, feature scaling, and model evaluation, KNN was able to classify passenger survival effectively.
