# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
1. The the run time error of displaying the values when history is updated ,( it display the previous value not the current ones )

2. New game does not reset the game  

- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

The hint is not working. and the new game is not resetting the game

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
Claude
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
The reset game feature was sucuesfully implemented with plan of ai architecting on how to fix it.


- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

Given the  hint feature is incomplete, ai did suggest that the idea of using heat as a hint is generally confusing, because not evryone can get the point and build connection with temperature 


## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
used py test to see the hint feature and the to final test by launching the game to obser it it actually runs as expected 
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
  I ran manual test bu putting inputs , the hints will give me a specific rnage of wher is the range of the correct number 
- Did AI help you design or understand any tests? How?
The Ai did help me design the hin feaure, in terms of how to come out with better hint for user to understand, 

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
I used Git to make sure that when i made one or 2 changes with ai , i will commit immediately and note down what aa=re the functions i changed , Interms of using ai , I will use claude plan mode to observe if the result is what i expecetd to be and correct claude form there before it actually implement the code 
- What is one thing you would do differently next time you work with AI on a coding task?
When I am working on thsi project , I immediately check the game without follwoing through the instructions , which takes me longer time to understand the probelm . Next time I will read the instructions first before I go and debug the probelm

- In one or two sentences, describe how this project changed the way you think about AI generated code.
I think plannig properly with ai will help me reduce all lot of hassle , as i can monitor the outputs of ai , this give me a batter outcome rather than directly prompt ai to make changes and correct the changes after the code was implemented 
