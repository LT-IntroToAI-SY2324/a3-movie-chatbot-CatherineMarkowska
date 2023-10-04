# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
The search_pa_list funciton attempts to match up what is parsed into the function with the pattern_action list in order to see if there is a match. If so, it returns the match (if the user asks who directed amarcord, it will return federico fellini). If what is parsed in does not exist or is speled incorrectly, it will return either "no answers" or "I don't understand." 

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added Jurassic Park (1993) and Carrie(1976) movies to the movies.py filed. I added these movies because they are iconic and are within the 1940s-2000s range of all the other movies. 

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
 I added "(str.split("what year was % released?"), title_by_year),". I think this is a useful pattern because sometimes people just want to know the year a particular movie was released, not all the movies in the database that happen to share the same date. 

4. What chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would create a chatbot, similar to this, that focuses on horror video games. I would create it because it is October (hence the focus on horror) and because horror video games like Five Nights at Freddy's and Amnesia are well-known. What this chatbox would do is, when the user asks a question, say date the game was released, the developer, what platforms the game was released on, and how much money it made as of making the chatbox. 

5. What was the most difficult portion of this assignment?
The most difficult portion of this assignment was the 'search_pa_list" because I didn't really know how to approach it. I understood it after Mr. Berg explained it, but when I attempted to do it I couldn't really figure out what steps to take. 

6. Did you write a new assert for your pattern action?



