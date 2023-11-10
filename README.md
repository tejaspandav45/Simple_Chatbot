# Simple_Chatbot with OS Functionality

## Overview

This Python script implements a simple chatbot using the Natural Language Toolkit (NLTK). The chatbot engages in conversations based on predefined patterns and includes additional functionality to perform basic operating system-related tasks.  It's a simple rule-based chatbot using NLTK for pattern matching. The chatbot responds to predefined patterns with specific responses.

## Features

### 1. Greetings and Conversation

The chatbot responds to common greetings and engages in simple conversations. It recognizes patterns such as "hello," "hi," "hey," "how are you," and "how's it going."

### 2. Opening Applications

Users can instruct the chatbot to open specific applications by typing commands like "open notepad" or "open calculator." The chatbot uses the `os.system` function to execute the corresponding operating system command.

### 3. Web Searching

The chatbot can perform web searches by launching the default web browser and initiating a search based on user input. For example, typing "search chatbot" will open a web search for "chatbot" using the default search engine.

## Libraries required

- Python 3.x
- NLTK (Natural Language Toolkit)

## Steps i have use to build this chatbot

1. **Install Python:**
   - Download and install Python from [python.org](https://www.python.org/downloads/).

2. **Install NLTK:**
   - Open a terminal or command prompt.
   - Run `pip install nltk`.

3. **Run the Script:**
   - Execute the script in a Python environment.

## Steps to access

1. Run the script.
2. Enter text to interact with the chatbot.
3. Type 'exit' or 'quit' to end the conversation.

## Patterns and Commands

- **Greetings:**
  - "hello," "hi," "hey"
- **Well-being:**
  - "how are you," "how's it going"
- **Bot's Name:**
  - "what is your name"
- **Exiting:**
  - "exit," "quit"
- **Opening Applications:**
  - "open {application_name}"
- **Web Searching:**
  - "search {query}"

## Example Usage

- Typing "open notepad" will attempt to open Notepad.
- Typing "search chatbot" will initiate a web search for "chatbot."

## Results:

This is the way how this chatbot generates the output:

You: hello
Chatbot: Hi there!

You: how are you
Chatbot: I'm good, thank you!

You: what is your name
Chatbot: I'm a simple chatbot.

You: open notepad
Chatbot: Opening notepad...

You: search chatbot
Chatbot: Searching for chatbot...

You: exit
Chatbot: Goodbye!

Thats all for this project.
