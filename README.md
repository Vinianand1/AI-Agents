# AI-Agents

## An AI Agent is a system that uses an LLM to decide the control flow of an application.

![image](https://github.com/user-attachments/assets/1976a8de-9b47-4455-b9c6-5b5198323151)


**LLM**: In AI, LLM refers to large language models designed for natural language processing that are pre-trained on vast amounts of data. Some of the common LLms are GPT-3.5-Turbo, GPT-4, PaLM-2, etc.

### What is an AI Agent?
![image](https://github.com/user-attachments/assets/6b208e0e-7a53-42f3-997d-3e416bfd92f8)

**An AI agent is an autonomous system designed to perceive its environment, process information, and take actions to achieve specific goals or objectives.**

**Planning:** An AI agent sets goals and creates milestone-based plans to achieve the goals.

**Memory:** They use memory to process immediate prompts and remember past interactions, often through retrieval-augmented generation (RAG).

**Tools:** AI agents interact with external APIs to retrieve data or execute commands, enabling them to perform multi-step tasks and adapt to dynamic environments.

**Prompt Template:** Provide a set of instructions to instruct the agent.

## Components and interactions involved in an AI agent's function
![image](https://github.com/user-attachments/assets/d1fbd1c2-db4e-4342-b702-769c5c8afba4)


### Components
- **Agent(center):** This is the main element where processing happens. The agent is responsible for taking actions based on inputs from other components.

### Inputs to the Agent:

1. **Abilities:** The skills or capabilities that the agent has to perform specific tasks.
2. **Goal/Preferences:** The objectives or preferences that guide the agent's decision-making.
3. **Prior Knowledge:** Information the agent already knows, which influences its actions.

### Interaction with the Environment:
1. **Actions:** These are actions the agent performs, which directly impact the Environment.
2. **Environment:** This is the setting or context where the agent operates, which changes based on the agent's actions.
3. **Observations and Past Experiences:** Feedback the agent receives from the environment, helping it adapt and refine future actions.

### Flow of Information:
Inputs (Abilities, Goal/Preferences, and Prior Knowledge) feed into the **Agent**.
The **Agent** performs **Actions** within the **Environment**.
The **Environment** provides feedback to the agent in the form of **Observations** and **Past Experiences**, which help improve its decisions and actions over time.

This diagram emphasizes the **cyclic relationship** between the **Agent** and its **Environment**, where the agent’s actions influence the environment, and the feedback loop helps the agent improve or modify future actions.

