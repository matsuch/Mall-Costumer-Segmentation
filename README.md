# Mall-Costumer-Segmentation
 Data from Kaggle containing informations about costumers

### Table of Contents

1. [Installation](#installation)
2. [Project Overview](#overview)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Overview<a name="overview"></a>

This data set is created only for the learning purpose of the customer segmentation concepts. You are owing a supermarket mall and through membership cards, you have some basic data about your customers and want to understand the customers like who can be easily converge Target Customer so that the sense can be given to marketing team and plan the strategy accordingly.

## File Descriptions <a name="files"></a>

- Data
   - Mall_Customers.csv - demographic data for each costumer and score

- Code
   - Mall-Costumer-Segmentation.ipynb - code that runs all the analysis

## Results<a name="results"></a>

Below is a chart called "Elbow Method" and is used to identify the best number of clusters for the data.

![image](https://user-images.githubusercontent.com/77889112/121788910-ca5cfa00-cba7-11eb-8f09-7f4dfeaffc95.png)

Here we have two types of clustering, the first one on the left chart it was using a simple scatter plot with the costumer gender. On the right chart, we have four clusters analysing AGE and COSTUMER_SCORE using the Kmeans algorith . You will find other types of clusterings in the code.

![image](https://user-images.githubusercontent.com/77889112/121788895-ae595880-cba7-11eb-8ef4-c1dac7b1be13.png)


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

This is a open data from Kaggle, must give credits to the owner and you can find it [here](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python). Otherwise, feel free to use the code here as you would like! 
