# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
1. The the run time error of displaying the values when history is updated ,( it display the previous value not the current ones )

2. New game does not reset the game  

- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
Claude
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).


- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

Given the  hint feature is incomplete, ai did suggest that the idea of using heat as a hint is generally confusing, because not evryone can get the point and build connection with temperature 

# conditionally show bonus hint:
if show_hint:
    secret_val = st.session_state.secret
    parity = "even" if secret_val % 2 == 0 else "odd"
    diff = abs(guess_int - secret_val)
    if diff <= 5:
        temp = "🔥 Hot"
    elif diff <= 15:
        temp = "🌡️ Warm"
    else:
        temp = "🧊 Cold"
    st.info(f"Hint: The number is **{parity}**. You are **{temp}**!")

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
