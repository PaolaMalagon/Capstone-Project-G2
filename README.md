# Killer Pandas Capstone :panda_face:
This a repository for our casptone project
<<<<<<< HEAD

## Overview ##
In this project we were exploring data sets using data analysis, statistical methods and generating insights to solve the needs of Computing Vision.

=======
## Overview ##
In this project we were exploring data sets using data analysis, statistical methods and generating insights to solve the needs of Computing Vision.
>>>>>>> 9477a073e0033bfcc760e4f25f5e2b67d7ba31ba
## Business Understanding ##
Our team is currently tasked with generating valuable insights as computer vision ventures into the film industry:
 - The movies who have the higher earnings and its categories
 - The best categories to develop a movie in
 - The most likely successful directors within these categories to make a successful movie
 - Find out if the duration of a movie has an influence in the earnings and engagement
<<<<<<< HEAD
 
=======
>>>>>>> 9477a073e0033bfcc760e4f25f5e2b67d7ba31ba
## Data Understanding and Analysis
The data that we used is from pages about movies such as the moviedb.org and rotten tomatoes. We used them due to their records where we got info such as movie ratings, genres, directors, etc. We used data sets with more than 140,000 entries and using statistical measures such as mean or standard deviation to understand the behavior of data
The conclusions and graphs we’re getting from the information of the datasets, such as the graph of the most popular genres in movies using columns from im.db dataset. We had to adjust our analysis due to limitations with some datasets that weren´t up to date and other ones had missing data
Description of data
<<<<<<< HEAD

### Data analysis of Earnings
Computer vision wants to make projects with big earning and that’s why we started studying the movies with highest earnings, if we identified them, we could find common points such as genres, directors, and another interesting data.
We started with dataset “tn.movie_budget.csv” we cleaned to converting the data in integers, then we get the values “Earnings” subtracting values “Budget” from values “Gross”. We ordered the data in descent way, and we get the first 10 movies to graph.
![Earnigs](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/top_10_highest_earnings.png)
Then we got a data frame of the top ten movies with highest earnings and added the genres of each movie, in this way we could find more useful information about those genres.  
![table-earnings](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/Top_ten_movies_and_genres.png)

### Data analysis of Categories  
Here will see the graphic of the most voted categories, we filter the data like only the categories
who have above 900,000 votes, so as you can see in this query the best rated movie it is 8.6.
![Categories](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/max1.png)
![Categories-table](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/max_table.png)
but this one isnt the one with the most votes, the one with the most votes is action and thriller.
In the sencond graphic it only show the best top 5 categories in a individual way.
![Categories2](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/max2.png)
So with this in mind we can see that this data could be related with the table of the 10 top movies.

### Data analysis of Directors
Here is the graph with the top 20 directors with their average ratings. 
![Directors](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/directors_graph.png)

We filtered the im.db database to only select directors that have a 7 or higher average rating for their body of work and over 400,000 votes on their films then limited the query to the top 20 in order of highest rating. On the next graph you will see that we worked on getting the Categories and film names for those top 20 directors. but the categories are grouped together i.e "action,adventure,drama".
![Directors-table](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/Categories_director.png)
so in the next graph we then seperated those categories into individual strings and also listed the frequency showing that Adventure, Action, and Sci-fi were the top three most highly voted and rated categories for these directors.
![Directors2](https://github.com/PaolaMalagon/Killer-Pandas/blob/main/images/Miguel2.png)

=======
Data analysis of Earnings
Computer vision wants to make projects with big earning and that’s why we started studying the movies with highest earnings, if we identified them, we could find common points such as genres, directors, and another interesting data.
We started with dataset “tn.movie_budget.csv” we cleaned to converting the data in integers, then we get the values “Earnings” subtracting values “Budget” from values “Gross”. We ordered the data in descent way, and we get the first 10 movies to graph.
###GRAPH###
Then we got a data frame of the top ten movies with highest earnings and added the genres of each movie, in this way we could find more useful information about those genres.
###TABLE###
Data analysis of Categories
Here will see the graphic of the most voted categories, we filter the data like only the categories
who have above 900,000 votes, so as you can see in this query the best rated movie it is 8.6
but this one isnt the one with the most votes, the one with the most votes is action and thriller.
In the sencond graphic it only show the best top 5 categories in a individual way.
So with this in mind we can see that this data could be related with the table of the 10 top movies.
Data analysis of Directors
Here is the graph with the top 20 directors with their average ratings. we filtered the im.db database to only select directors that have a 7 or higher average rating for their body of work and over 400,000 votes on their films then limited the query to the top 20 in order of highest rating. On the next graph you will see that we worked on getting the Categories and film names for those top 20 directors. but the categories are grouped together i.e "action,adventure,drama". so in the next graph we then seperated those categories into individual strings and also listed the frequency showing that Adventure, Action, and Sci-fi were the top three most highly voted and rated categories for these directors.
>>>>>>> 9477a073e0033bfcc760e4f25f5e2b67d7ba31ba
## Statistical Communication
Results of statistical inference
Interpretation of these results in the context of the problem

## Conclusion
We recommend to make a movie with high earnings the category that could have most impact on people will
be Action because it has the most number of votes.
We also recommend selecting a director due to their history of highly rated movies with a high number of votes
in the category of either Adventure, Action, or Sci-Fi.
We found that movies with runtimes between 90 and 130 minutes have a high number
of votes. So with that in mind we would recommend creating a film within that range of runtime.
