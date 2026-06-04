# AI-chatbot
# Role-Based Prompt Engineering Chatbot 🤖

An AI-powered chatbot that dynamically switches between expert personas 
to answer questions from different professional perspectives.

## Features
- 🎭 Multiple roles — Teacher, Lawyer, Developer
- ⚔️ Debate Mode — all roles respond simultaneously with counterarguments
- ⚡ Powered by Mistral AI (mistral-small-latest)
- 🧩 Modular prompt engineering architecture

## Tech Stack
Python • Streamlit • Mistral AI • Prompt Engineering

## Setup
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Add your Mistral API key to `.streamlit/secrets.toml`:
   MISTRAL_API_KEY = "your_key_here"
4. Run: `streamlit run app.py`
