# AI-Blog-Generator

Generate detailed, SEO-friendly, and well-structured blog posts using the power of [Groq's Gemma LLM](https://groq.com/) and LangChain's tool integration. This app collects real-time information from Wikipedia and DuckDuckGo and uses prompt chains to produce high-quality blog content — all accessible through an interactive Gradio interface.

---

## 🚀 Features

- 🔍 Uses **Wikipedia** and **DuckDuckGo** for real-time, accurate research.
- 🧠 Powered by **Groq's `gemma2-9b-it` model** via LangChain.
- 🪄 Generates:
  - A compelling blog title
  - Research summary
  - Conclusion
  - Full blog post (800–1200+ words)
- 🖼️ Simple **Gradio** web app interface.

---

## 📦 Requirements

Install the required packages with:

```bash
pip install -r requirements.txt
gradio>=3.0.0
langchain>=0.0.200
langchain-groq>=0.0.1
python-dotenv>=0.21.0
requests>=2.28.0


GROQ_API_KEY=your_groq_api_key_here

.
├── app.py               # Main Gradio app
├── requirements.txt     # Dependencies
├── .env                 # Environment variables (not committed)
└── README.md           
