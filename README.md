# Projects
## :one: Titanic data set- Prediction of Survival using Logistic Regression </br>
:diamonds: Used pandas, numpy, matplotlib, seaborn and sklearn</br>
:diamonds: Initially checked for null values and deleted the rows where there were minimal numbre of missing values </br>
:diamonds: Removed some features that were not important to the model like name and passenger ID </br>
:diamonds: For features with many missing values, imputes the data: Categorical data was imputed with the values that appear most frequently in the datset and numeric values were imputed with the mean value </br>
:diamonds: Did some basic visualizations using seaborn and matplotlib.pyplot </br>
:diamonds: Did the same steps above for both test and training set </br>
:diamonds: Fit a Logistic Regression model on the training set </br>
:diamonds: Predicted the survival of passenger in the test set</br> 
:diamonds: Now split the original training set into separate training and test sets </br> 
:diamonds: Got the accuracy of the model using confusion matrix and .acc_score() </br> 
:diamonds: The accuracy of the model is : 71% </br> 
<img src="https://akm-img-a-in.tosshub.com/indiatoday/titanic_647_041416113640.jpg?size=690:388" width="300" height="200"> </br>
</br>
</br>
</br>
## :two: Iris data set - Classification/prediction using K Nearest Neighbors </br>
:cherry_blossom: Used pandas, numpy, matplotlib, seaborn and sklearn </br>
:cherry_blossom: There were no null values in the dataset, however the id column was not necessary for the model, so dropped the column</br>
:cherry_blossom: Did some basice eda, heat maps and jointplots etc </br>
:cherry_blossom: Split the data into training and test sets </br>
:cherry_blossom: Plot the accuracy scores for a rage of 1 to 20 K values </br>
:cherry_blossom: Overfitting problem occurs after k=8. 8 Gives highest accuracy </br> 
<img src="https://cdn11.bigcommerce.com/s-ynwe6/products/366/images/1233/iris__57764.1663963103.380.380.jpg?c=2" width="300" height="300"> </br>
## :three: Clustering of Social media posts using PCA and KMeans clustering </br>
:sparkles: Used pandas, numpy, sklearn - PCA and KMeans and matplotlib </br> 
:sparkles: Checked the number of null values and dropped unncessary columns like status_id </br>
:sparkles: visualized the data using jointplot, heatmap and bar and scatter plots</br>
:sparkles: Converted categorical variables to numeric variables as sklearn does not work with categorical variables </br>
:sparkles: Got the optimal value of K using the elbow method : optimal K = 5 in this case </br>
:sparkles: Used PCA and found out that only 2 features are sufficient to build the model </br>
:sparkles: Fit a pipleine for PCA and KMeans model to transform the data </br>
:sparkles: Plotted the transformed data and showed the 5 clusters </br> 
:sparkles: Built a hierarchical clustering Dendrogram </br> 
<img src="https://media.smallbiztrends.com/2022/01/social-audio.png" width="300" height="200"> </br>
## :four: Sentiment analysis of clothing reviews using the vader method and basic of Hugging face Roberta </br>
:star: Used, pandas, numpy, seabor, matplotlib, nltk, wordcloud and Hugging face's transformers </br> 
:star: Did basic EDA, check the number of each of the ratings</br>
:star: Tokenized a random sample review from the data set </br>
:star: Got the part of speech tags for each of tokens </br>
:star: Got the polarity scores of the sample text using .polarity_scores() </br>
:star: There were some null values in the review text, dropped these rows </br>
:star: Got the polarity scores for each of the reviews in the dataset and added them back to the original dataset </br>
:star: Built a wordcloud with all reviews in the dataset. Most frequest words were : dress, love, top, wear, look, size and fit</br>
:star: Check the relation between ratings and polarity scores </br>
:star: Used transformers to find the polarity of the sample review pulled out earlier</br>
:star: Compared the results for the sample review in Vader method and hugging face's transformers </br>
:star: Transformers performed better in determining the polarity of the review </br>
<img src="https://www.powerreviews.com/wp-content/uploads/2022/01/2023reviewguide.png" width="300" height="200"> </br>
## :five: Visualizations of 2022 Layoff data using Power BI  </br>
:chart_with_downwards_trend: Table: Company wise, number of people laid off </br>
:chart_with_downwards_trend: Map: Countries affected and by how much</br>
:chart_with_downwards_trend: Tree Map: Industry wise lay offs </br>
:chart_with_downwards_trend: Scatter plot: is there a relation between funding and layoffs? </br>
:chart_with_downwards_trend: In total: 262K people were affected due to layoffs in 2022 </br>
<img src="https://missionloca.s3.amazonaws.com/mission/wp-content/uploads/2022/11/feature-tech-layoff-03.png" width="300" height="200"> </br>
