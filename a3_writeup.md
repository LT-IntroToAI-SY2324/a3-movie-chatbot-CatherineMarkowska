# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
The search_pa_list function attempts to match up what is parsed into the function with the pattern_action list in order to see if there is a match. If so, it returns the match (if the user asks who directed Amarcord, it will return Federico Fellini). If what is parsed in does not exist or is spelled incorrectly, it will return either "no answers" or "I don't understand." 

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added Jurassic Park (1993) and Carrie(1976) movies to the movies.py file. I added these movies because they are iconic and are within the 1940s-2000s range as all the other movies. 

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
 I added (str.split("what actors were in %"), actors_by_title). I felt that it was useful because, in paList there is only one actors_by_title pattern, so adding another one allows for more ways to ask about the actors by title. I feel that this additional pattern is also the natural way someone would ask the question, which is why I added it. 

4. What chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would create a chatbot, similar to this, that focuses on horror video games, movies, and books. I would create it because it is October (hence the focus on horror) and because there are horror icons such as the Halloween movie Five Nights at Freddy's games, and the Carrie book. What this chatbox would do is similar to this chatbot: the user would ask the chatbox a question about a movie, book, or video game. The available questions are:
### For video games 
 Who developed this video game?
 How long was the game in development?
 When was it released?
 How long does it take to play the game on average? 
 How many copies did it sell? 
 Who is the villain? 


### For books: 
 Who wrote it? 
 When was it released?
 How many copies were sold? 
 How many words is it? 
 Who is the main character of the book? 

### For movies: 
 What year was it released?
 Who are the actors?
 Who directed it? 
 How long did it take to make? 
 Is the movie based on a true story?
 What rating does the movie have (is it PG-13, rated R, etc)?

5. What was the most difficult portion of this assignment?
The most difficult portion of this assignment was the 'search_pa_list" because I didn't really know how to approach it. I understood it after Mr. Berg explained it, but when I attempted to do it I couldn't really figure out what steps to take. 

6. Did you write a new assert for your pattern action?
Yes, I did. It was: 
 # my assert 
    assert sorted(actors_by_title(["carrie"])) == sorted(
        ["sissy spacek"]
    ), "failed actors_by_title test"
    


