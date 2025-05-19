# 🤖 AI Agents – Hugging Face Multi-Agent Systems

This repository explores the design, orchestration, and application of autonomous AI agents using Hugging Face’s `transformers` and `agents` libraries. It delves into how intelligent agents can reason, plan, and act across different domains, integrating tools and prompts to solve complex tasks either individually or as part of a coordinated multi-agent system.

---

## 🧠 Project Overview

Autonomous AI agents represent a shift from static LLM usage to dynamic, task-oriented systems capable of:

- Understanding user intent through prompt-based instructions
- Selecting and executing tools (e.g., code interpreters, search engines, browsers)
- Chaining together reasoning steps to accomplish goals
- Collaborating with other agents in structured environments

This project implements several such agents in modular notebooks to showcase key patterns in agentic interaction, reasoning, and coordination.

---

## 📁 Notebook Descriptions

### `Agents_crew_ai.ipynb`
Introduces the `crewAI` framework for defining roles, goals, and tasks across multiple agents. Demonstrates how to architect a collaborative environment where agents delegate and synchronize actions.

### `Course_Ch_0.ipynb`
Foundational concepts in AI agents, prompting strategies, and how tool-use is embedded into LLM-driven decision-making.

### `HF_Agent_text_to_sql.ipynb`
Builds an agent capable of converting natural language queries into SQL commands. Highlights how LLMs interpret user prompts, generate structured output, and interface with databases.

### `HF_Agentic_RAG.ipynb`
Implements a Retrieval-Augmented Generation (RAG) pipeline using Hugging Face Agents. The agent fetches relevant context from a document corpus before generating informed responses.

### `Hf_Agent_Web_Browser_Automation_with_Agents.ipynb`
Explores how agents can interact with web browsers to automate tasks. This includes parsing webpage elements, filling forms, or navigating based on user instructions.

### `hf_agent_orchestrate_a_multi_agent_system.ipynb`
Demonstrates a complex use-case where multiple agents collaborate to complete subtasks. It covers task division, memory management, role assignment, and output coordination.

---

## 💡 Key Concepts Explored

- **Agentic Reasoning**: Each notebook emphasizes step-wise reasoning and goal decomposition.
- **Tool Integration**: Agents use tools like search engines, databases, or browsers to accomplish specific subtasks.
- **Prompt Engineering**: Carefully designed prompts guide agents’ behavior, decision-making, and output format.
- **Multi-Agent Collaboration**: Agents interact and share context to collectively solve larger problems.
- **Embodied Intelligence**: Some agents demonstrate capabilities closer to embodied cognition — acting on environments (web, SQL, vector stores) instead of just generating text.

---

## 📚 Learning Objectives

By studying this repository, you will:

- Understand the building blocks of agent systems built on top of LLMs.
- Learn how to integrate tools and decision logic into agent workflows.
- Gain insights into prompt design for controlling agent behavior.
- See practical implementations of retrieval-augmented and tool-augmented reasoning.
- Explore multi-agent coordination strategies for complex task automation.

---

## 📌 Applications & Use Cases

- AI assistants that can answer questions using structured and unstructured data sources.
- Agents that can automate repetitive or multi-step web-based workflows.
- Natural language interfaces for databases.
- Prototypes for multi-agent simulations in enterprise, research, or educational settings.

---

