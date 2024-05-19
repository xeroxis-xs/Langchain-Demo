# LangChain Demo Project

This project demonstrates the use of LangChain, a Python library for building applications with language models.

## Getting Started

To get started with this project, you need to install several packages. You can do this by running the following commands in your terminal:

```bash
pip install -U langchain==0.2.0
pip install -U langchain-core==0.2.0
pip install -U langchain-community==0.2.0
pip install -U langchain-openai==0.1.7
pip install -U langchain-experimental==0.0.59
pip install -U wikipedia
pip install -U yfinance
pip install -U tabulate
pip install python-dotenv
```

## Project Structure
This project contains a Jupyter notebook `demo.ipynb` that demonstrates various features of LangChain, including:  

- Prompt Templates: Predefined recipes for generating prompts for language models.
- Output Parsers: Transform the output of a language model to a more suitable format.
- Chaining: Execute a sequence of steps or operations in a specific order to accomplish a task.
- Memory: Refer to information introduced earlier in the conversation.
- Tools and Toolkits: Interfaces that an agent, chain, or language model can use to interact with the world.
- Agents: Use a language model to choose a sequence of actions to take.

# Running the Demo
To run the demo, open the demo.ipynb notebook in Jupyter Notebook and run the cells in order.