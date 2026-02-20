# n8n_projects
🤖 AI Automation Workflows with n8n

This repository contains a collection of AI-powered automation workflows built using n8n, integrating Telegram, OpenAI (LLMs), Gmail, and Google Calendar.

Each workflow is designed to demonstrate intent detection, tool orchestration, and real-world automation use cases such as email handling, reminders, and conversational agents.

📌 Projects Included
1️⃣ Telegram AI Character Bot

A conversational Telegram bot powered by an LLM that responds in a custom personality (e.g., Spider-Man).

Features

Telegram trigger for real-time messages

LLM-based response generation

Persona-driven system prompts

Clean separation between trigger, agent, and response

Use Case

AI character chatbots

Entertainment bots

Prompt-engineering demos

2️⃣ Email Automation Agent

An AI agent that intelligently decides what to do based on user intent sent via Telegram.

Supported Actions

📥 Get emails from Gmail

📤 Send emails via Gmail

⏰ Schedule calendar reminders

Key Highlights

Strict intent classification

Single-action execution per request

No accidental multi-tool execution

Tool-based decision making using LangChain Agent

3️⃣ Calendar-First Reminder Agent

A calendar-priority AI agent that automatically creates reminders when a date is detected.

Behavior

Detects dates and times in natural language

Creates exactly one calendar event

Defaults to 9:00–10:00 AM if no time is mentioned

Ignores email tools when a date is present

Example

“Project submission on June 23”
→ Google Calendar reminder created automatically
🧠 Tech Stack

n8n – Workflow automation

Telegram Bot API – User interaction

OpenAI (LLM) – Intent detection & reasoning

LangChain Agent Nodes – Tool orchestration

Gmail API – Email read/send

Google Calendar API – Event creation

🗂 Repository Structure
📁 n8n-ai-workflows
│
├── telegram-character-bot.json
├── email-automation-agent.json
├── calendar-reminder-agent.json
└── README.md

⚠️ All workflows are credential-free.
You must connect your own credentials after importing.

🚀 How to Use

Install and run n8n

Import any .json workflow into n8n

Reconnect required credentials:

Telegram API

OpenAI API

Gmail OAuth

Google Calendar OAuth

Activate the workflow

Interact via Telegram

🔐 Security & Privacy

No API keys or credentials are stored in this repository

All sensitive fields have been removed

Safe for public sharing and collaboration

🎯 Learning Outcomes

Through these projects, I explored:

Prompt engineering for strict AI behavior

Multi-tool AI agents

Event-driven automations

LLM decision-making in production workflows

Designing safe, deterministic AI systems

📈 Future Improvements

Persistent memory across conversations

Multi-user context handling

Logging and observability

Rate limiting & abuse prevention

UI dashboard for monitoring workflows
