# WhatsApp AI Customer Service — N8N Workflow
Automated customer service system built on N8N, connecting
WhatsApp Business API (Meta) with GPT-4o and human agent handoff.
## What it does
- Receives WhatsApp messages via official Meta Cloud API
- Responds automatically using GPT-4o with full conversation history
- Detects when a human agent is needed and triggers handoff
- Notifies the agent via Telegram with complete chat history
- Logs all conversations in Airtable
## Tech stack
- N8N (automation workflow)
- WhatsApp Cloud API — official Meta
- OpenAI GPT-4o
- Airtable (session management)
- Telegram (agent notifications)
## How the handoff works
When a customer uses trigger words like "speak to someone",
"urgent", or "complaint", the system automatically:
1. Notifies the customer that a human will follow up
2. Alerts the agent on Telegram with the full conversation history
3. Switches the session to HUMAN mode
4. Returns control to AI with a single click when the agent is done
## Screenshots
See /screenshots folder
## Available on Fiverr
[Link coming soon]