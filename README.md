# 🧠 TalentScout Hiring Assistant Chatbot

Welcome to **TalentScout**, an intelligent hiring assistant built using Streamlit and LLMs (Large Language Models) to streamline the initial candidate screening process for tech roles.

---

## 🚀 Features

- 👋 Friendly greeting and purpose overview
- 📝 Collects candidate details: Name, Email, Experience, Tech Stack, etc.
- 🤖 Generates **custom technical questions** based on the candidate's declared tech stack (e.g., Python, Django, React, SQL)
- 💬 Maintains coherent and context-aware conversation
- ❌ Graceful exit when the candidate uses a conversation-ending keyword
- 🔄 Handles unknown inputs with fallback responses

---

## 🎯 Use Case

Designed for recruitment agencies and HR teams to automate the **first round of candidate screening**—saves time and ensures consistency.

---

## 🛠️ Tech Stack

| Component        | Tool / Library              |
|------------------|-----------------------------|
| Frontend UI      | Streamlit                   |
| Language Model   | OpenAI GPT / HuggingFace LLMs |
| Backend Logic    | Python                      |
| Deployment       | Streamlit Cloud / Local     |

---

## 📂 File Structure

```bash
talentscout-chatbot/
├── app.py                  # Main Streamlit app
├── prompts.py              # Prompt templates and helper functions
├── utils.py                # Utility functions (e.g., generate questions)
├── requirements.txt        # Python dependencies
├── example_data/
│   └── candidates.json     # Sample data (for testing)
├── .gitignore
└── README.md
