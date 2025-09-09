# agentic-patterns
---
##Reflection Pattern Example
###Overview

reflection.py demonstrates the Reflection design pattern for AI agentic workflows using Ollama models. It implements a ReflectionAgent that generates and refines Python code through iterative collaboration between a generator agent and a reflector agent.

###Functionality
Input: Accepts a user prompt for topic and word count (e.g., "Generate a Python implementation of the Merge Sort algorithm").

###Process:
A generator agent creates initial code based on the prompt.
A reflector agent critiques the code, suggesting improvements.
The process iterates for a specified number of steps (n_steps=10) to refine the output.
Output: Prints the final, polished code.

###Usage
Ensure the agentic_patterns module and an Ollama model are installed (see repository setup instructions).

###Run the script:
python reflection.py

###Dependencies
* Python 3.8+
* Ollama model for local LLM execution