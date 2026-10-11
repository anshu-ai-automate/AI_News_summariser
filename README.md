# AI News Summarizer Agent

An automated AI agent that fetches the latest news daily, summarizes it using LLM, and delivers it straight to Telegram.

## What it does
- Fetches news from TechCrunch RSS feed on a daily schedule
- Filters articles by category (AI & Tech vs Other)
- Summarizes each article into 3 bullet points
- Stores summaries in Airtable
- Sends formatted summary to Telegram automatically

## Tech Stack
- n8n (workflow automation)
- Google Gemini 2.5 Flash (LLM)
- Groq — LLaMA (fallback LLM)
- Airtable (storage)
- Telegram (delivery)

## Setup
1. Import the JSON file into your n8n instance
2. Connect your own credentials (Gemini, Groq, Airtable, Telegram)
3. Set your Telegram Chat ID in the Telegram node
4. Set your Airtable Base and Table IDs
5. Activate the workflow — it runs daily at 8AM automatically

## Note
All credentials and IDs have been removed from the workflow JSON. Add your own before, RUNNING.....
