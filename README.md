# Multilingual Voice & Text Telegram Bot

An automated Telegram bot workflow capable of receiving, processing, and responding to both voice and text messages across multiple languages using AI translation and speech processing.

## 📌 Features
- **Voice & Text Input**: Accepts audio voice notes and text messages directly via Telegram.
- **Speech-to-Text Transcribe**: Converts incoming voice messages into structured text.
- **Multilingual Translation**: Automatically detects input language and translates content using AI models.
- **Smart Response Generation**: Generates contextual replies in the user's preferred language.

## 🚀 Getting Started

### Prerequisites
- An active account on your automation platform (e.g., n8n, Make).
- A Telegram Bot token (obtained via `@BotFather`).
- API keys for AI / Audio Translation services (e.g., OpenAI Whisper / GPT API).

### Setup & Installation
1. Download the `Multilingual Voice & Text Telegram Bot file.json` file from this repository.
2. Open your workflow automation platform and import the JSON file.
3. Configure your Telegram Bot credential and API keys in the node parameters.
4. Set up the Telegram Webhook trigger and activate the workflow.

## ⚠️ Security Notice
Never expose your Telegram Bot Token or secret API keys in public code. Always configure them inside secure credential managers or environment variables within your automation host.
