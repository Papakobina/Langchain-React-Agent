# Langchain-React-Agent

This project is designed to explore and understand how ReAct agents work within the LangChain framework. The focus is on integrating a simple tool for calculating text length to demonstrate the process and principles behind ReAct agents.

<img src="https://github.com/Papakobina/Langchain-React-Agent/blob/main/react-langchain-flowChart.png"/>

## Objectives
- Understand the functionality of ReAct agents.
- Learn how to integrate custom tools within the LangChain framework.
- Explore the interaction between agents and tools through natural language inputs.

## Technologies Used
- Python
- LangChain
- OpenAI API
- dotenv

## Technical Explanation
ReAct Agents Overview
ReAct agents in LangChain are designed to handle natural language inputs, process them, and determine the appropriate actions to take using a set of integrated tools. The agent operates by maintaining an internal state and iteratively performing actions based on the input and the results of previous actions.

Tool Integration
In this project, a custom tool get_text_length is integrated within the LangChain framework. This tool calculates the length of a given text string, demonstrating how custom tools can be utilized by ReAct agents.

Tool Definition
The get_text_length tool is defined using the @tool decorator. It takes a text string as input, strips any non-alphabetic characters, and returns the length of the text.



