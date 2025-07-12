# LanguageBridge 🌐📞

**Real-time language translation for phone and SMS conversations using OpenAI, Laravel, Asterisk, and JsSIP.**

## Features

- 🧠 AI-powered real-time translation
- 📱 Browser-based SIP phone via JsSIP
- 📞 Conference calling via Asterisk ARI
- 💬 SMS webhook support via Laravel
- 🔄 Proxy number & shared session management
- 🏠 Self-hostable with Docker
- 🌍 Designed for cross-border communication

## Use Case

Immigrants struggling with local language barriers can use shared numbers or browser phones to talk to locals, doctors, or agencies—while AI translates the conversation in real time.

## Tech Stack

- Laravel (API & SMS handling)
- Python (Asterisk ARI bridge & OpenAI integration)
- JsSIP (Browser-based SIP client)
- Asterisk (Call routing & conferencing)
- OpenAI (Transcription & Translation)

## Getting Started

1. Clone repo and set up `.env` (sample provided)
2. Install Laravel dependencies and migrate DB
3. Set up Asterisk config (see `/config/asterisk`)
4. Run Python bridge server
5. Access JsSIP client via `/public-client`

## Contribution Guide

Coming soon – we welcome PRs and community translations.

## License

MIT
