<p align="center">
  <img src="nvidia.png" alt="NVIDIA logo" width="220"/>
</p>

# NIM-LangChain-Agents

A practical, end-to-end repository for building large language model applications using **NVIDIA NIMs** as the inference layer and **LangChain** as the orchestration framework.

---

## Overview

This repository provides a structured walkthrough of developing LLM-powered applications, starting from basic prompt submission and progressing to fully agentic systems. NVIDIA NIMs are used as the model serving backbone, while LangChain enables composition, control flow, and reuse of LLM driven logic.

The focus is on building reliable, modular, and production-oriented workflows rather than one-off prompt experiments.

---

## Tech Stack

- **NVIDIA NIMs**  
  Containerized, high-performance inference services for large language models.

- **LangChain**  
  Application framework for chaining, routing, and managing LLM interactions.

- **Pydantic**  
  Schema validation and structured output enforcement.

- **Python**  
  Primary implementation language.

---

## Repository Structure and Learning Path

### 1. Prompting Fundamentals

- Sending prompts to NIM served chat models
- Receiving standard responses
- Streaming outputs
- Batch processing
- Iterative prompt refinement

This section establishes how NIMs fit into an LLM application stack as low latency, programmatically accessible inference services.

---

### 2. LangChain Expression Language and Runnables

- Introduction to LCEL
- Creating reusable runnables
- Composing chains
- Parallel execution
- Modular prompt pipelines

These examples show how NIM powered models can be embedded into scalable workflows rather than single shot interactions.

---

### 3. Message-Based Prompting

- System, human, and AI message roles
- Few-shot prompting
- Persona control using system messages
- Chain of thought style prompting
- Conversation history management

This section demonstrates how structured message handling improves task reliability and reasoning depth while remaining compatible with NIM deployed chat models.

---

### 4. Structured Output and Data Extraction

- Defining output schemas with Pydantic
- Enforcing structured LLM responses
- Extracting and tagging information from free-form text
- Working with long documents

This enables LLM outputs to be used safely in downstream systems.

---

### 5. Tool Use and Agents

- Defining external tools
- Integrating tools into LangChain chains
- Building simple agents
- Reasoning about when tool invocation is appropriate
- Merging tool outputs into final responses

Here, NIM backed models act as the reasoning component, while LangChain manages execution and integration logic.

---

## What This Repository Demonstrates

- How to use NVIDIA NIMs as a drop-in inference layer for LLM applications
- How LangChain enables composable, reusable LLM workflows
- How to move from prompts to structured, agentic systems
- How to enforce output reliability using schemas
- How to extend LLM capabilities with tools and agents

---

## Author and Credits

**Author:** Amjad Kudsi

This repository was created and is maintained by Amjad Kudsi.

It builds on and integrates the following open source and publicly documented technologies:

- NVIDIA NIMs  
  https://docs.nvidia.com/nim

- LangChain  
  https://github.com/langchain-ai/langchain

- Pydantic  
  https://github.com/pydantic/pydantic
