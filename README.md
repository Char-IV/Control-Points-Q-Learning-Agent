# Overview
Strategy based environment for AI training and Q-Learning Agent implemented for tests. Utilized a LLM to assist in creating both features.  
This project was together in a week or so for a class final.
  
# The Environment  
The Control Points environment is similar to the board game risk. You have units which you can move to different nodes, capturing them. You also procure additional units over time. Each node you own at the end of a turn awards currency to the owner. There are also options to upgrade unit power or purchase additional units.  

# The Agent
The Q-Learning Agent is a simple dynamic programming implementation. No imports for pre-built agents were used and the scope of this project is quite small, so it's written for this specific environment.  

# LLM Usage
A LLM was used (You.com as it is free under my university) to create and edit the initial environment and agent. It was passed specific instructions on how most features should be formatted. It did alright, but there were quite a few errors that it could not correct. I ended up doing a lot of bug-fixing and smaller edits myself.
