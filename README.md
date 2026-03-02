# Ai-support-escalation-agent
RAG-Based Intelligent Customer Support System
📌 Project Overview

AI Support Escalation Agent is an intelligent backend system that automates customer support using Retrieval-Augmented Generation (RAG).

The system retrieves similar past support tickets using semantic search and automatically decides whether to:

✅ Provide an instant AI response

🚨 Escalate the issue to a human agent

This project demonstrates practical use of Vector Databases, Embeddings, and Escalation Logic in real-world support systems.

🧠 Architecture

User submits query

Query converted into embeddings

FAISS searches similar past tickets

If similarity is high → Return automated response

If similarity is low → Escalate to human agent

⚙️ Tech Stack

Python

Flask (REST API Backend)

SentenceTransformers (Embeddings)

FAISS (Vector Search Engine)

Google Colab (Development & Testing)

Ngrok (Public API Testing)
