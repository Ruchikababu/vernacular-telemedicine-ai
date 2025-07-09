# Vernacular Telemedicine AI Assistant (n8n + Gemini)

This project is an AI-powered medical assistant built using n8n and Google Gemini.
It accepts symptoms in any language and returns a short medical suggestion in the same language.

## Features
- Supports multilingual symptom input
- AI diagnosis using Gemini-Pro
- Built with n8n (no-code automation)

## How it Works
1. User sends a POST request to a webhook with a symptom (e.g. Tamil, Hindi, Chinese)
2. Gemini processes and replies in the same language
3. Ideal for vernacular telemedicine systems

## Test it with Postman
POST to: `https://your-n8n-url/webhook-test/symptom-input`

Example Body:
```json
{ "symptom": "எனக்கு தலைவலி உள்ளது" }
