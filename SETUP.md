# Setup Instructions for AI Blog Generator

This document provides step-by-step instructions to set up the AI Blog Generator project on your local machine.

---

## Prerequisites

- Python 3.10 or higher installed. You can download it from [python.org](https://www.python.org/downloads/)
- Git installed (optional, for cloning the repository). Download from [git-scm.com](https://git-scm.com/downloads)
- An API key for Groq LLM (Gemma 2-9B / llama-3.1-8b-instant model). Ensure you have your API key ready.

---

## 1. Clone the Repository

If you have Git installed, clone the repo:

```bash
git clone https://github.com/Arun612/BlogCrafter.git
cd BlogCrafter
```

Or download the ZIP file from GitHub and extract it.

---

## 2. Create and Activate Python Virtual Environment

It's best practice to use a virtual environment to avoid package conflicts.

On Windows:

```bash
python -m venv env
.\env\Scripts\activate
```

On Linux/macOS:

```bash
python3 -m venv env
source env/bin/activate
```

---

## 3. Install Dependencies

Install all required Python packages from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

## 4. Setup Environment Variables

Create a `.env` file in the project root directory with the following content:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Replace `your_groq_api_key_here` with your actual Groq API key.

---

## 5. Run the Application

Run the main script to generate a blog based on a topic:

```bash
python main.py
```

You will be prompted to enter a topic. The script will generate and display the blog content.

---

## Troubleshooting

- If you encounter errors related to missing packages, ensure you ran `pip install -r requirements.txt`.
- For API errors, double-check that your `.env` file contains the correct API key.
- Ensure your Python version is 3.10 or above.

---

## Suggestions for Improvement

- Integrate a web interface (e.g., using Gradio) for user-friendly interactions.
- Add more research tools or APIs for richer content.
- Improve prompt templates for enhanced content quality.

---

## Contact

For questions or issues, please open an issue on the GitHub repository or contact the maintainer.

---

*Happy blogging!*
