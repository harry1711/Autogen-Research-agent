# Autonomous Research Agent using AutoGen & GROQ API

This project demonstrates an autonomous agent built using the **AutoGen agentic framework** and **GROQ API** to automate academic research from ArXiv.

## 💡 What It Does

The agent takes a **user-specified research topic** and performs the following steps autonomously:

1. Queries **ArXiv** for the **top 5 most relevant research papers**.
2. Extracts:
   - 📌 **Title**
   - 📝 **Summary**
   - 🔗 **Link to the paper**
3. Analyzes and summarizes each paper using the **GROQ LLM**.
4. Presents the collected data in a structured format.

## 🔧 Technologies Used

- **AutoGen** – Agent orchestration framework for agent-based workflows  
- **GROQ API** – LLM for intelligent analysis and summarization  
- **ArXiv API** – For fetching open-access academic papers  

## 📥 Example Output

**Topic**: _"Large Language Models for Code Generation"_

### 🔎 Paper 1

- **📌 Title**: "CodeGen: An Open Multilingual Code Generation Model"
- **📝 Summary**: This paper introduces CodeGen, a family of open large language models trained for code generation in multiple programming languages. The model achieves high performance on benchmark datasets, and the authors provide insights into training strategies and multilingual capabilities.
- **🔗 Link**: [https://arxiv.org/abs/2203.13474](https://arxiv.org/abs/2203.13474)

> 💬 **LLM Analysis**: CodeGen demonstrates that LLMs can generalize across languages and tasks. Its training on both natural and programming languages highlights the importance of diverse datasets. It also raises questions about reproducibility and code safety in production systems.

---

*More examples will be shown in the actual run output of the agent.*
