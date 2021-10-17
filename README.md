**The purpose of the model**


Importance of Travel Reviews for Travel-Related t Decisions , travel service providers use reviews posted by consumers as having several advantages based on their ratings.this project explores dimensions of satisfying  experiences on a travel and advances insight for understanding the factors evaluation of travel experiences at a destination. In our project we will separate users in different clusters, which would help us to recommend them different types of advertisment,The analysis ratings and reviews provide tremendous value to merchants to provide services and advertisments correctly. it provides businesses with valuable market and help them better understand the opinions and needs of the tourists. 

**dataset**

Tarvel Review Ratings dataset ,I obtained it from Kaggle website. This data set is populated by capturing user ratings from Google reviews. Reviews on attractions from 24 categories across Europe are considered. Google user rating ranges from 1 to 5 and average user rating per category is calculated.
My dataset contains more then 5000 instances and 25 features 
Attribute 1 : Unique user id
Attribute 2 : Average ratings on churches
Attribute 3 : Average ratings on resorts
Attribute 4 : Average ratings on beaches
Attribute 5 : Average ratings on parks
Attribute 6 : Average ratings on theatres
Attribute 7 : Average ratings on museums
Attribute 8 : Average ratings on malls
Attribute 9 : Average ratings on zoo
Attribute 10 : Average ratings on restaurants
Attribute 11 : Average ratings on pubs/bars
Attribute 12 : Average ratings on local services
Attribute 13 : Average ratings on burger/pizza shops
Attribute 14 : Average ratings on hotels/other lodgings
Attribute 15 : Average ratings on juice bars
Attribute 16 : Average ratings on art galleries
Attribute 17 : Average ratings on dance clubs
Attribute 18 : Average ratings on swimming pools
Attribute 19 : Average ratings on gyms
Attribute 20 : Average ratings on bakeries
Attribute 21 : Average ratings on beauty & spas
Attribute 22 : Average ratings on cafes
Attribute 23 : Average ratings on view points
Attribute 24 : Average ratings on monuments
Attribute 25 : Average ratings on gardens

In this project I will use all features in the dataset based on clustering algorithm to figure out how is the people visit certain places 

**Target result**
This dataset describes how users rate their estimates ,my  job is to learn how to grouped them in clusters. This is most secnificant important because it will allow us to work more efficiently with our users , based on clusters, we can offer people services more specifically.

**Tool**

Our project tools are anaconda environment using python, The required libraries 
Pandas, sklearn, matplotlib and seaborn and numpy

**Exploratory Data Analysis**

In this phase we do that 
1-Remove Nun values 
2-Renamed columns
3-Remove missing values 
4-Convert object values in to float values
5-Showed the feature scaling and relation between feature and save data after EDA

![image](https://user-images.githubusercontent.com/78117752/137635615-a372865b-a313-4b96-9788-859517148263.png)

![image](https://user-images.githubusercontent.com/78117752/137635623-bfc49d7e-a88a-446d-9c3b-7e6738df16bc.png)

We make  checking on outlires in our data, how features are distrbuted before moved to next phase 

**Preprocessing phase**

We normalize catagroies in our data 

**clustering data by K-MEAN algorithm**

Before we visualizing our data we cant get a clear plot of data according to a large number of features in our data ,PCA is an algorithm that is used for dimensionality reduction - meaning, informally, that it can take in a DataFrame with many columns and return a DataFrame with a reduced number of columns that still retains much of the information from the columns of the original DataFrame.

1-	We initialize our PCA models
2-	displays our data point on the three principal components created for 3-D visualization

![image](https://user-images.githubusercontent.com/78117752/137635733-82b3d130-0c26-46d6-9e4a-5e53a4b20489.png)

the plot here is not clear enugh, so i tend to reduced dimentional to 2 APC

3-	PCA Visualizations with 2D

![image](https://user-images.githubusercontent.com/78117752/137635777-41ef04e2-7789-476c-bec8-51371fbe6f38.png)

as we can see plotting our data before clustering ,from plotting I can decide number of K 

**Applying K-mean clustering**

![image](https://user-images.githubusercontent.com/78117752/137635869-4b93e26d-55f4-46de-be1e-0e71f9f3b027.png)

According to result we can conclude that we have 6 groups of people who give estimates based on their rating 




