# NLP Coding Challenge

We want to know how you approach NLP problems and how would you solve them. This challenge is not supposed to answer are you a great linguist or a programmer - but how well would you fit into our team, where we constantly face new challenges.

Your task is to create a simple bot that allows a user to add an appointment to his calendar using natural language. You only need to implement the dialog capabilities, not the integration with the calendar. Use a language understanding system (e.g. Microsoft LUIS, api.ai, etc.) to define an NLU component and train it with a couple of utterances. Also, please explain how you would implement a mixed-initiative dialog manager system (using UML diagrams or other flowcharts).

Note: Actions are transfered to the backend in the following format, so you should have this data before sending the data: {"intent": intent_name, "start_time": start_time, "end_time": end_time, "title": title}

## What we'll look at
- Quality of the NLU recognition system trained by you and it's coverage.
- How did you choose the language understanding system and why.
- Explanation how you would test the system and it's components.
- The task is deliberatly very open. If you want to clarify anything, please ask us.
- Bonus: Implement the system in Python or any other language - either as a server, or an application.

## Time limit
It should take you between 4 to 8 hours to finish this task. If it takes you longer, just provide an explanation on what you omitted and why.

After sending you the challenge we'll wait 2 weeks to hear back from you. Feel free to ask us for any clarification if you need it.

## Process

If you want to write some code, when you're ready, please fork this repository and start writing code in your fork. If you want to focus on describing the system, use any tool of your preference and send us the results over email.
