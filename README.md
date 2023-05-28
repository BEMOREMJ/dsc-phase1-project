# FILM SUCCESS ANALYSIS FOR MICROSOFT'S NEW STUDIO

![cinema](cinema.jpeg)

## INTRODUCTION
Film is a medium that tells stories through images and sounds. It is considered by many to be the most dominant art form of the twentieth century. Films are a means of telling stories through images and sounds, and an instrument of illusion. They can be used to entertain, educate, inform, and inspire.
Film production started a long time ago as a source of entertainment which quicly turned into a way of making money as people are drawn to them. Nowadays one can say that movies are one of the biggest source of entertainment in the world together with music and social media. Many Big companies have ventured into film making as it a source of income if done properly. Apple and Sony are an example of how films can be profitable. 
The metrics of success of a film can be categorized into:
    1. A compelling storyline depending on the genre of the film
    2. A well-written script(Writers)
    3. Great actors who have a reach to the audience
    4. A visionary director alongside a director of photography and editor
    5. Film budget 

The future of films is an interesting topic. According to BBC Culture, an array of rapidly developing technologies offer thrilling potential for the future of motion pictures. Some of these technologies include:

    1. Virtual reality
    2. Augmented reality
    3. Artificial intelligence
    4. 3D printing

However, according to Vox, the future of movies is not bright. The article states that the movie industry is facing a number of challenges, including:

    1. The rise of streaming services like Netflix and Amazon Prime Video
    2. The high cost of producing movies
    3. The decline in movie theater attendance

It will be interesting to see how the movie industry adapts to these challenges in the coming years.



## PROBLEM STATEMENT
Microsoft sees all the big comapanies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.


## MAIN OBJECTIVE
To provide recommendations to the Microsoft CEO about the factors that can make a film a success.

### SPECIFIC OBJECTIVES 
We are going to analyse different factors which can lead us to determine the success of a film:
    1. Determine which genre of films are more likely to be successive 
    2. Determine how actors and directors influence films.
    3. Determine how a film budget can influence the movie to be successful in terms of gross and whether it will be profitable as it is an important aspect of a business as well.


## DATA AVAILABLE 
We have been provided with data from different sources:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

All the data is related we just have to figure out how to use it by finding a relation between them. The data is in csv format we will use the appropriate method to extract them.

### Notebook Structure
-Reading the data
-Data Wrangling
-Exploratory Data Analysis
-Conclusions
-Recommendations

## METHODOLOGY
### - Data Wrangling

Data provided wasn't clean so we had to perform some cleaning where some rows had null values were dropped, some columns were also dropped. Some of the data type wasn't in the desired format so we had to change them using the appropriate formats. Some tables were also joined for better EDA.

### - EDA

We are interested in mainly three aspects:
- Types of genres
- Directors and actors
- Movie Budgets

1. On types of genres we are investigating which types of genres are most likely to achieve the highest rating. And which ones come in last. We employed visualization of filtered data of types of genres with rating of 9.0 and above.

2. On directors and actors we are investigating how directors and actors can affect the movie. We employed visualization of filtered data of films with a rating of 9.0 and above.

3. On movie budgets we invetigate the relationship between movie budgets and the total gross to examine the linear relationship between the two. We employed visualization and correlation.


## CONCLUSION

- From 5.1 we have discovered that the genre with the highest number of movies with a rating of 9.0 and above are documentaries with over 700 films. It was followed by drama, comedies, biography, adventure, action, crime. Coming in last are game-shows.

- From 5.2 we had to set out to see if we can see directors and actors have influence on films and can make them succesful. We found that directors and actors can actually influence movies as per our findings where films with a rating of 9.0  and above some directors had several films in the category which also true with actors too. You might have spotted the name Leanardo DiCaprio who is a popular actor.

- From 5.3 we were investigating to see if there is a relation between movie_budgets and total_gross. total_gross is important as in every business venture profits are important as well. We found that as the movie budget tends to increase total gross also increases. By visualizing the graph you can see it. From the correlation calculations we find that movie budget and total gross are positively related.


## RECOMMENDATIONS

- The company should go for a documentary or drama or comedy genre-based film as it starts up the new film division. This more likely to be recognised and liked by people as a result the company new division will get recognition. The genre of a movie can also affect the target audience and the overall tone of the film. Different genres have different conventions and expectations. 

- The company should seek out famous or succesful directors and actors for its films. Actors and directors play a crucial role in the success of a movie. The director determines the creative vision and makes all of the film's biggest decisions. They are responsible for directing the actors and ensuring that their performances are consistent with the overall vision of the film. The director's relationship with the actors is critical to the success of the film. Actors also have a significant impact on movies. A great actor can save bad material, but bad acting can destroy an awesome script. Actors need at least the illusion that their own imaginations have full freedom. The director's efforts are naturally affected by the length of time given to rehearsals.

- The company should be ready to spend and invest in the new venture. The budget of a film includes all costs related to the development, production, and post-production of the film. This includes costs such as acquiring the script, payments to talent, and production costs. The budget plays a dominant role throughout the film's cycle with implications going far beyond the mere cost of the film. The budget of a film can affect many aspects of the production. For example, a high budget movie is almost always financed by a film studio and is synonymous with blockbuster cinema. The project type and genre also a big role in the structure of your accounts and sub-accounts on your film budget breakdown.