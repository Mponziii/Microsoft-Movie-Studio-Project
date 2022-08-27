# MICROSOFT MOVIE STUDIO PROJECT
Author: `James Mponzi`


## 1.OVERVIEW

Microsoft has enlisted my services as a data scientist to help them identify which movies are doing best at the box office, since the creation of their new movie studio.My task will be to go through available resources like the IMDb database and Box Office Mojo dataset, this will enable me to figure out which movies have performed the best depending on various factors such as total gross revenue of the movie and its rating. The results attained will enable the Microsoft movie studio  to know which genres of movies and other factors might influence the performance of their movie in the box office, hence allowing them to make a well informed choice on which type of films they want to make .

## 2.DATA UNDERSTANDING

The datasets used in this analysis were:
    * [Box Office Mojo](https://www.boxofficemojo.com/)- contains foreign and domestic gross earned by movie
    * [IMDB](https://www.imdb.com/)-This is a database but the two specific tables we'll be using are movie_basics and movie_rating

From movie_basics table the  columns being used are runtime_minutes which tells us the length of the movies in minutes, while the other column genres tells us the genres of the movies 

## 3.DATA ANALYSIS
To ensure quality of our analysis the data had to be cleaned.This entailed removing rows with null values and outliers and replacing other null values in columns:

![5]("C:\Users\mponz\zara\Microsoft_movie_analysis_P1\Microsoft-Movie-Studio-Project\zara\5.png")

The most coomon genres:

![2]("C:\Users\mponz\zara\Microsoft_movie_analysis_P1\Microsoft-Movie-Studio-Project\zara\2.png")

The relationship between the foreigh gross and foreign gross can be shown in the plot below:

![output]("C:\Users\mponz\zara\Microsoft_movie_analysis_P1\Microsoft-Movie-Studio-Project\zara\output.png")


## 4.CONCLOSION

* From the data analysis carried out on the data available to us some conclusions can be derived from our observations
<ol>
   <li>The 20 most common movie genres are:Documentary , Drama , Comedy , Horror , Comedy,Drama , Thriller , Action , Biography,Documentary , DramaRomance Comedy,Drama,Romance , Documentary,Drama , Comedy,Romance , Romance , Documentary,Music , Drama,Thriller , Documentary,History , HorrorThriller , Biography,Documentary,History , Biography,Documentary,Drama , Family</li>
   <li>The average length of a movie is 86 minutes but a number of movies tend to be longer or short </li>
   <li>For both domestic gross majority of movies get less than the average gross amount</li>
   <li>Movies that a large domestic gross amount have larger foreign gross amount compared to movies with small domestic gross amount</li>
   <li>Majority of movies get a rating of 6</li>
   <li>Majority of the average numbrer of votes are low numbers</li>
   <li>Majority of movie ratings are determined by a low number of votes</li>
   <li>The genres with the least number of number of results can be found in 4.2 section</li> 
</ol>   

## 5.RECOMMENDATIONS

* My recommendations to the new movie studio are:
     <ol>
        <li>Genres of the movies should be selected from the most common genres and genres that get the most average votes</li>
        <li>The length of the movies should be more than average 86 minutes</li>
        <li>The movies made should target the domestic market although higher income comes from foreign</li>
        <li>Genres with a low number of average votes should be avoided since this may indicate a small audience</li>

## 6.NEXT STEP

* If more analysis is done genres which are liked more by the domestic market can be identified
* Popularities of movies can also be based of the actors present in the movie
* The average spending amount to make certain genre movies
* Comparing amount spent on a movie and amount returned


## For further refrence and research

* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)
