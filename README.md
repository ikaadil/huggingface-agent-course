# huggingface-agent-course

## Unit 1 Summary

#### 📘 What Is an AI Agent?

An **agent** is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks.

#### 🧩 Core Components
- **The Brain** (AI Model)  
- **The Body** (Capabilities and Tools)

#### What an Agent Must Do
- **Understand natural language**: Interpret and respond to human instructions in a meaningful way.  
- **Reason and plan**: Analyze information, make decisions, and devise strategies to solve problems.  
- **Interact with its environment**: Gather information, take actions, and observe the results of those actions.

####  🔁 Thought → Action → Observation Cycle

Agents operate in a continuous loop:

- **Thought**: The LLM decides the next step based on the current context.  
- **Action**: The agent performs an action by calling a tool with specific arguments.  
- **Observation**: The agent observes the result of the action and updates its internal state accordingly.

This cycle continues until the agent achieves its objective.

