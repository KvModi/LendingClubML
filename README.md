# LendingClubML
Input data: https://bit.ly/2YfxTAi
Task 1:
-Irs the professor is going to need the wholedata set for the study. The professor would like to know the trend and the factors affecting the intrest rate of loan as the students have more data(features) to explore. This strengthens the point that in industry most of the efforts goes in improving and understanding data. It is more importat to have more data when compared to complex algorithms.
-The data had many coloums which were empty or had values which can not be used. 
-Analysis of the the graphs generated from the lending club data. The graphs has been studied keeping in mind the need of the professor.
https://bit.ly/2YhEYQF

Task 2:
The data was cleaned using panda library. The coloum with more than 80% of empty data was dropped. The coloums with functions not related to predection were droped too. Converting the grade from string to numeric value. Changing the type of data and filling the empty cells with the median of the coloum.
Used manual feature engneering and auto featuretools (https://github.com/featuretools/featuretools/ )
In manual feature tools we could change the things according to our needs while in auto we are restriceted 


Task 3:
Building 3 manual ML models:
-Linear regression 
-Random Forest
-Neural Network

We have taken a MAPE of the output to choose the most reliable model. Random Forest has the least MAPE.

Task 4: Hypertuning
Using Hypertuning to increase the efficency.
a. Regression: Try L1, L2, Elasticnet regularization
b. Neural networks: Change epochs, optimizers, learning rate
c. Random forest: No of trees, Tree depth
. https://scikitlearn.org/stable/modules/grid_search.html
Libraries Used:
1. MLPRegressor
2. numpy
3. pandas
4. tensorflow
StandardScaler
Building 3 AutoML models:
-TPOT
-AutoSklearn
-H2O.ai

Using AutoML makes it more Interactive and Interpretable. AutoML makes it easy to change the input files without much changes.
It can be used on any input data to get the desired output

Task 5:
Building test cases to check our Random Forest model and Analysisng the output.


Citations:
1. James Max Kanter, Kalyan Veeramachaneni. Deep feature synthesis: Towards automating data science endeavors. IEEE DSAA 2015.     [https://dai.lids.mit.edu/wp-content/uploads/2017/10/DSAA_DSM_2015.pdf]
2. https://cmdlinetips.com/2018/01/7-tips-to-read-a-csv-file-as-pandas-data-frame/
3. https://github.com/ryanschaub/Predicting-Loan-Interest-Rates/blob/master/WF%20Interest%20Rate%20Predictions.ipynb
4. Team 4 (Presentation given in the class)
5. https://www.liebertpub.com/doi/full/10.1089/big.2018.0092




