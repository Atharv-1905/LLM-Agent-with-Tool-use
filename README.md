# LLM-Agent-with-Tool-use

A GenAI Lab 8 assignment that demonstrates an LLM agent capable of using external tools through function calling.

## Project Overview
This project builds a small ReAct-style agent in a Jupyter notebook. The agent can:
- solve arithmetic with a safe calculator tool
- fetch current information with a web search tool
- decide when to use tools vs. answer directly

## Repository Structure
- `GenAI_EXP8.ipynb` — main notebook containing the complete implementation and experiments
- `README.md` — project documentation

## Features
- Secure arithmetic evaluation using Python AST
- DuckDuckGo-based web search integration
- Tool schema registration for model function-calling
- Agent execution loop for multi-step reasoning with tools
- Test prompts for math-only, search-only, and mixed queries

## Prerequisites
- Python 3.9+
- Jupyter Notebook or Google Colab
- Groq API key (configured in your notebook environment)

## Setup
1. Open `GenAI_EXP8.ipynb` in Jupyter or Google Colab.
2. Install required packages from the first setup cell.
3. Configure your API key in the environment used by the notebook.
4. Run notebook cells from top to bottom.

## Notebook Flow
The notebook is organized as a guided sequence:
1. Package installation
2. Imports and API key loading
3. Model selection
4. Calculator tool definition
5. Web search tool definition
6. Tool schema binding
7. Agent ReAct loop implementation
8. Main multi-tool experiment
9. Optional validation tests
10. Observations and summary

## Expected Outcome
After running the notebook, the agent should correctly choose and use the relevant tool(s) based on user query type.

## Author
Atharv Bhosale
