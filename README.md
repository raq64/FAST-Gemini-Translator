# FAST Gemini Translator

A simple desktop translator overlay that uses [Gemini 2.5 Flash Lite](https://ai.google.dev/) for intelligent translation.

## Features

- Always-on-top window.
- Input box with `Enter` to send and `Shift+Enter` for newline.
- Chat area displaying conversation.
- Conversation history persisted to `chat_history.json`.

## Setup

1. Install dependencies:

```bash
pip install requests
```

2. Set your Gemini API key:

```bash
export GEMINI_API_KEY="your_api_key"
```

3. Run the app:

```bash
python translator.py
```

## Default Model and System Prompt

- **Model**: `gemini-2.5-flash-lite`
- **System Prompt**: see `translator.py` for the detailed prompt defining translation behaviour.

