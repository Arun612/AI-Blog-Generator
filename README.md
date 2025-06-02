# 🧠 AI-Powered Blog Generator

This project is an **AI-powered blog generation system** that creates rich, informative blog posts based on any given topic. It combines cutting-edge LLMs, search tools, and prompt engineering to generate detailed, SEO-optimized content.

---

## 🚀 Features

- 🔍 **Automated Research**: Gathers information from Wikipedia and DuckDuckGo using LangChain tools.
- ✍️ **AI-Generated Titles**: Creates compelling, SEO-friendly blog titles.
- 📄 **Structured Content**: Organizes blogs into Introduction, Main Content (with subheadings), and Summary.
- 🧠 **LLM-Powered**: Uses the `llama-3.1-8b-instant` model from Groq for natural and coherent language generation.
- ⚙️ **Tool-Oriented Agent**: Employs a LangChain agent to fetch and reason with live search data.
- 🌐 **Web UI with Gradio** (optional): Easily extendable to a web interface for non-technical users.

---

## 🛠️ Tech Stack

| Component         | Description                                      |
|------------------|--------------------------------------------------|
| 🧠 **LangChain**     | Framework for chaining LLMs and tools            |
| 🦾 **Groq LLM (Gemma 2-9B)** | High-performance inference using Groq platform |
| 🔎 **Wikipedia & DuckDuckGo APIs** | For factual research on the given topic     |
| 🧱 **Prompt Engineering** | Custom templates for title, research, summary, and full blog |
| 🖼 **Gradio (optional)** | UI for interacting with the blog generator     |
| 🔐 **dotenv**         | For managing API keys securely                  |

---

## 📂 Project Structure
📁 ai-blog-generator/

├── main.py 

├── .env # Contains GROQ_API_KEY 

├── requirements.txt 

└── README.md # Project documentation (this file)

---

## 📌 How It Works

1. **Input**: User provides a topic (e.g., “Benefits of Quantum Computing”).
2. **Step 1**: Generate a blog heading using a custom prompt.
3. **Step 2**: Agent fetches research using Wikipedia & DuckDuckGo.
4. **Step 3**: Summarize the research into key points.
5. **Step 4**: Generate a full blog post with structured sections.
6. **Output**: A complete blog post ready for publishing.

---

