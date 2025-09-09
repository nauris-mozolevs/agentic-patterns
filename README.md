# agentic-patterns

## Reflection Pattern Example
### Overview
reflection.py demonstrates the Reflection design pattern for AI agentic workflows using Ollama models or OpenAI API. It implements a ConversableAgent and AssistantAgent that generates and refines output through iterative collaboration between a generator agent and a reflector agent.

### Functionality
Input: Accepts a user prompt for topic and word count (e.g., "AI Agentic Workflows").

### Process:
A generator agent creates initial response based on the prompt.
A reflector agent critiques the response, suggesting improvements.
The process iterates for a specified number of steps (n_steps=10) to refine the output.
Output: Prints the final, polished response.

### Run the script:
python reflection.py

### Dependencies
* Python 3.8+
* Ollama model for local LLM execution
* autogen
