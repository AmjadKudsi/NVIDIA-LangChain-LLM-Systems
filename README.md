# NVIDIA NIM LangChain Prompting and Agents
This repository provides a compact, end to end demonstration of building large language model applications using NVIDIA NIMs as the inference layer and LangChain as the application framework. It starts with core prompt engineering and progressively introduces reusable chains, message based prompting, and structured outputs, all executed against NIM hosted chat models optimized for low latency and scalable deployment.

The material shows how LangChain Expression Language and runnables enable modular composition of NIM powered workflows, moving from simple prompt response patterns to parallel and reusable pipelines. Message level prompting is used to implement few shot learning, system role control, and reasoning oriented prompting while remaining compatible with NIM served models.

The repository concludes with schema enforced outputs using Pydantic and agent based tool use, where NIM backed models decide when to invoke external functions and integrate results. Overall, it serves as a focused reference for using NVIDIA NIMs as the reasoning core in structured, agentic LLM applications built with LangChain.
