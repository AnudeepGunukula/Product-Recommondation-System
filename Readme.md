# Product Recommondation System

<br>

##Problem Statement
<hr>

Building recommondation system for products electronics and clothing

<br>

##Description

Online E-commerce websites like Amazon,Flipkart uses different recommondation models
to provide different suggestions to different users. ecommerce sites currently uses
item-to-item collaborative filtering, which scales to massive data sets and produces
high-quality recommendations in real time. This type of filtering matches each of the 
user's purchased and rated items to similar items, then combines those similar items
into a recommendation list for the user. In this project we are going to build 
recommendation model with the similar kind of approach.

<br>


##Objecives:
<hr>

1. Predict the rating that a user would give to a product that he has not yet rated.
2. Minimize the difference between predicted and actual rating (RMSE) 

##Prerequisites:
<hr>
You need to have installed following softwares and libraries in your machine before running this project.

1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.

## installing:
<hr>

1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/

## Built with:
<hr>

Built With

1.  ipython-notebook - Python Text Editor
2.  sklearn - Machine learning library
3.  seaborn, matplotlib.pyplot, - Visualization libraries
4.  numpy, scipy- number python library
5.  pandas - data handling library

## Steps Followed: 
<hr>

1.Read and explore the given dataset.

2.Take a subset of the dataset to make it less sparse/ denser.

3.Split the data randomly into train and test dataset.

4.Build Popularity Recommender model.

5.Build Collaborative Filtering model.

6.Evaluate both the models.

7.Get top - N ( N = 5) recommendations. Since our goal is to recommend new products foreach user based on his/her habits, we will recommend 5 new products.

8.Summarise your insights.

<br>

# References
<hr>
I have referred many blogs while making of this project

* https://medium.datadriveninvestor.com/how-to-built-a-recommender-system-rs-616c988d64b2


* https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada


* https://www.analyticssteps.com/blogs/what-are-recommendation-systems-machine-learning


* https://en.wikipedia.org/wiki/Singular_value_decomposition


* https://towardsdatascience.com/understanding-singular-value-decomposition-and-its-application-in-data-science-388a54be95d

###### this is a markdown file created by Anudeep Gunukula