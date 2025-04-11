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
Topic: "Reinforcement Learning for Robotics"

Title: Deep Reinforcement Learning for Robotic Manipulation Summary: This paper explores... Link: https://arxiv.org/abs/xxxx.xxxxx

Title: Policy Gradient Methods for Real-Time Control Summary: ... Link: https://arxiv.org/abs/yyyy.yyyyy

...
