Building a ReAct Agent for Intelligent Query Resolution
This project demonstrates the development of a ReAct-style AI agent that integrates with a language model via the Groq API to perform structured reasoning and query resolution. The agent follows an iterative "Thought, Action, PAUSE, Observation" cycle to solve queries interactively, such as computing planetary masses and performing arithmetic operations.

By leveraging Groq’s Chat API, this agent dynamically constructs responses based on user prompts, showcasing chain-of-thought reasoning and structured automation. The project includes an Agent class, helper functions for mathematical computations, and planetary mass retrieval, enabling intelligent step-by-step execution.

Key Features:
Groq API Integration: Seamless interaction with Groq’s large language models.
ReAct (Reasoning + Acting) Framework: Implements iterative query resolution.
Structured AI Workflow: Step-by-step execution using Thought-Action-Observation cycles.
Mathematical Computation: Built-in functions for arithmetic operations and planetary mass retrieval.
Dynamic Conversational AI: Maintains conversation history and updates responses iteratively.
