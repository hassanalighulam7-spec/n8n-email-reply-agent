## n8n-email-reply-agent
 Automated email reply agent built with n8n
 ## AI Email Reply Agent — Built with n8n

An automated workflow built in n8n that reads incoming emails, understands the query using AI, and sends back a relevant, automatic reply — no manual work needed.

# What It Does
Watches an inbox for new incoming emails (Gmail Trigger)
Passes the email content to an AI Agent node to understand the sender's query
Based on the query, generates a natural, context-aware reply
Sends the reply back automatically through Gmail
Logs each processed email for review
# Tech / Tools Used
n8n – workflow automation platform<img width="800" height="426" alt="ScreenRecording2026-09-02211411-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/13ba2c15-3abd-4fc0-b34a-d7a3f83e3f46" />

Gmail node – for receiving and sending emails
AI Agent node – for understanding queries and generating replies
# Workflow Overview
Gmail Trigger → New email received
AI Agent → Reads and understands the email query
Branching Logic → Routes different types of queries appropriately
Gmail (Send) → Sends the automated reply
Logging → Records the processed email and response
# Demo
<img width="800" height="426" alt="ScreenRecording2026-09-02211411-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/313658fb-89b1-40e2-8d64-f3a18e5d3e80" />

# Status

This is an early-stage personal automation project, built while learning n8n and exploring AI agents. Planned improvements:

Multi-language reply support
CRM integration for logging conversations
Expanding into a full customer support agent
## About

Built by Ghulam Hassan — Cybersecurity student and beginner in automation/no-code tools, documenting the learning journey through hands-on projects.
