# rule_based_chatbot

This project involves the development of a simple rule-based chatbot implemented in Python. The chatbot simulates a conversation with an alien named Shisu, who is curious about Earth and its inhabitants. The chatbot responds to user inputs based on predefined patterns and offers a conversational interface for users to interact with.

# Features
# Greeting and User Interaction:
The chatbot initiates the conversation by asking for the user's name.
It asks if the user is willing to help Shisu learn about Earth.
If the user responds negatively, the chatbot ends the conversation politely.

# Exit Commands:
The chatbot recognizes certain commands that signal the end of the conversation, such as "quit," "pause," "exit," "goodbye," "bye," and "later."

# Random Questions:
The chatbot can ask a series of random starter questions to engage the user. These questions range from "Why are you here?" to "What technology do you have on this planet?"

# Pattern Matching and Intent Recognition:
The chatbot uses regular expressions to match user input with predefined patterns.
It can recognize intents such as:
Describing the planet (describe_planet_intent)
Answering why the alien is here (answer_why_intent)
Information about Suraj (about_suraj)

# Response Generation:
Based on the identified intent, the chatbot generates appropriate responses.
For unmatched inputs, it provides generic responses to encourage further conversation.

# Code Structure
# Imports:
The project uses Python's re module for regular expressions and random module for random selections.

# Class Definition:
The main class, Rulebot, encapsulates all the functionalities of the chatbot.

# Class Variables:
Negative responses and exit commands are defined as class variables.
A list of random questions is also defined

# Initialization:
The __init__ method initializes the dictionary for pattern matching

# Greeting and Conversation Flow:
The greet method handles the initial interaction.
The chat method manages the flow of the conversation

# Pattern Matching:
The match_reply method matches user input to predefined patterns and invokes the corresponding response method.

# Intent Handling:
Methods like describe_planet_intent, answer_why_intent, and about_suraj generate responses for specific intents

# Generic Responses:
The no_match_intent method provides responses for inputs that do not match any pattern

# Conclusion
This rule-based chatbot project showcases a simple yet effective way to create a conversational agent using Python. By leveraging regular expressions and predefined patterns, the chatbot can engage users in a meaningful conversation, simulating an interaction with an inquisitive alien
