
# ResearchMind — Multi-Agent AI Research System

ResearchMind is a Python-based AI research application that
uses specialized agents and language-model chains to automate
web research, webpage extraction, report generation, and
report evaluation.

## Features

- Web search using Tavily
- Webpage content extraction using BeautifulSoup
- AI-generated structured research reports
- Critic feedback with scores and improvement suggestions
- Streamlit user interface
- Downloadable Markdown reports

## Technology Stack

- Python
- LangChain
- Groq API — openai/gpt-oss-20b
- Tavily
- BeautifulSoup
- Requests
- Streamlit

## Project Structure

- app.py — Streamlit interface
- agents.py — Agents and LLM chains
- tools.py — Search and scraping tools
- pipeline.py — Terminal-based research pipeline
- requirements.txt — Dependencies

## Setup

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the dependencies.
4. Configure the required API keys in a local .env file.
5. Run the application using Streamlit.

## Run the application

streamlit run app.py

## Security

Never commit API keys, secrets, or your local .env file.
