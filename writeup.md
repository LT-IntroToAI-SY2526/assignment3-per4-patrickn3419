# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?

I learned how to use for loops for the programming to loop through the movie database and find what I was looking for. I also learned about tuples and how they can store multiple variables in a list. I was able to extract the values that I wanted from each tuple and manipulate it to work in my movie chatbot. I also learned how the chatbot works by finding matches and taking out the information from the source which is not included in the source and uses the pattern to figure out which function to use on the match.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The movie chatbot first asks the user for input. Then, based on the user's response, the chatbot checks to see if any of the words in the response match to the pattern, which is like a template for a question. If the words match, the chatbot looks to see words that provide key information, such as a date or director. The chatbot then figures out which function to use to find what the user is looking for based on the pattern that matched with their source (the response). The functions allow the chatbot to look through its database and extract the requested information.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

On many company's websites, there are chatbots with the user can use to ask basic questions. This also allows the company to depend less on service workers. To extend the system, I could add more patterns, or add different variations of patterns so that it does not make much of a difference when the user words a question differently. I could also do this by having the chatbot just look for specific phrases and words rather than a complete part of the promt.