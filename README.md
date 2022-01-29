# Employee's-Income-Classification-based-age
This is a project of classification of employee on the basis of their age and income. Objective of this project is to classify different groups of employee based upon the income and age group. Here, we found three groups for the given dataset (income.csv), after predicting for set ([['40','4500']]) we found it belongs to the cluster 0 such that red community. The project is followed by following steps:
1. Importing some basic libraries for solving classification problem (KMeans Classification)
2. Importing the csv file into pandas dataframe
3. Ploting the data for better visualization into scatter plot
4. Building classification object and fitting the data in the model 
5. Plotting the result in scatter plot the better visualization of different cluster found by the classification model.
6. ![download](https://user-images.githubusercontent.com/65527534/151661890-bb80bf9e-4bb6-465a-83bd-74a30259d093.png)
7. For the best results, scaling the data and again fitting it into the model. After scaling, we can see the visualization and anlysise the difference from previous plot.
8.  ![download](https://user-images.githubusercontent.com/65527534/151661920-1551401c-c900-49fb-a0bf-23b963431fbd.png)
9. Using Elbow method the appropriate number of clusters are found (k=3).
10. ![download](https://user-images.githubusercontent.com/65527534/151661960-c4347d95-c926-48cb-82cc-d7f08495f51a.png)
11. In such a way, we classified the employees based upon their income and age group.
In the end, the same model is used for irir flower dataset for the classification of ["petal length (cm)","petal width (cm)"]. And by elbow method we found the value of k is 3.
    ![download](https://user-images.githubusercontent.com/65527534/151662064-9aad7338-6b38-4c56-84da-a89b6a56f86d.png)


