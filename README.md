# 🎥 YouTube AI Video Summarizer with Discord Notifications

An AI-powered automation workflow built using **n8n** that monitors a YouTube channel, downloads English captions, summarizes the transcript using OpenAI GPT, and automatically posts a concise summary to a Discord channel.

---

## Features

- Automatically detects newly uploaded YouTube videos
- Retrieves video captions using the YouTube Data API
- Extracts transcript text from caption files
- Generates AI-powered summaries using OpenAI GPT
- Sends formatted notifications to Discord
- Fully automated workflow with no manual intervention

---

## Workflow Overview

RSS Feed Trigger (New Video)
        ↓
Retrieve Caption Metadata
        ↓
Find English Captions
        ↓
Download Captions
        ↓
Extract Transcript Text
        ↓
OpenAI GPT Summary
        ↓
Discord Notification

---

## Technologies Used

- n8n
- OpenAI API
- YouTube Data API v3
- Discord Webhooks
- RSS Feed
- HTTP Request Nodes
- JSON
- OAuth2 Authentication

---

## Use Cases

- YouTube creators
- Discord communities
- Content marketing
- AI-powered content automation
- Social media management

---

## Setup

1. Install n8n
2. Import `workflow.json`
3. Configure:
   - YouTube OAuth
   - OpenAI API Key
   - Discord Webhook
4. Replace the YouTube Channel ID
5. Activate the workflow

---

## Credentials Required

- OpenAI API
- YouTube OAuth2
- Discord Webhook

---

## Future Improvements

- Multi-language support
- Email notifications
- Telegram integration
- Slack integration
- Sentiment analysis
- Keyword extraction
- Automatic blog generation

---

## License

MIT License
