# Auto Email Reply Workflow

This project is an automated email reply system built with n8n, Gmail, and OpenAI.

The workflow listens for incoming Gmail messages, classifies the email text, generates an AI-powered response, and replies automatically through Gmail.

## Features

- Gmail trigger for incoming emails
- Text classification using OpenAI
- AI-generated email response
- Automatic Gmail reply
- Separate reply paths for different email categories

## Workflow Preview

![Workflow Preview](screenshot.png)

## Tech Stack

- n8n
- Gmail API
- OpenAI
- Workflow automation

## How It Works

1. A new email arrives in Gmail.
2. The Gmail Trigger node sends the email content to the workflow.
3. The Text Classifier checks the email type.
4. OpenAI generates a suitable reply.
5. Gmail sends the reply automatically.

## Setup

1. Import the workflow JSON into n8n.
2. Connect your Gmail credentials.
3. Connect your OpenAI credentials.
4. Update the prompts if needed.
5. Test the workflow.
6. Activate the workflow.

## Security Note

This repository does not include API keys, Gmail credentials, or private environment variables.
Use `.env.example` as a reference only.

## Use Cases

- Customer support email automation
- Order inquiry replies
- Basic inbox triage
- Personal assistant-style Gmail automation

## Status

Prototype / working automation.
