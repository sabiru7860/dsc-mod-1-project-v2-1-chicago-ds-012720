# Intro 
My main goal of this project was to find a way for microsoft to enter the movie scene. I decided to focus on the movie components instead of the monetary aspects of the movie

# Prerequistes 
The python libraries i used were pandas,numpy and matplotlib. I also used the Rotten tomatoes database to analyze what movie components make a good movie


`import pandas as pd`

#Data Cleaning
I decided that i wanted to merge the Rotten Tomatoes databases together. I also decided to change the fresh column into a bianary set instead of 'Fresh and Rotten'. This helped me make comparing much more easier.
`def rotten(rating):
    if rating== 'rotten':
        return 1
    else:
        return 0` 
        
# Analyze
i started analyzing diffrent movie components and compared it to the fresh ratings of rotten tomatoes. For my comparisions i used runtime,genre,director,age restriction rating of movie.


#Conclusion
After analyzing my findings i came to a conclusion that the best runtime,director,age restriction rating, and genre were 115 mins,Steven Spielberg,rated R, and drama.


