# AeriumCraft AI Discord Bot

## Setup on Railway
1. Push this repo to GitHub
2. Create new project on Railway → Deploy from GitHub repo
3. Add environment variables:
   - `DISCORD_TOKEN` = your Discord bot token
   - `OPENROUTER_KEY` = your OpenRouter API key
   - `CHANNEL_ID` = Discord channel ID to listen in

## How it works
- Bot listens ONLY in the specified channel
- Responds when:
  - User **mentions** the bot (@AeriumCraft AI)
  - Message **starts with ?** (e.g. `?what is the server IP?`)
- Replies directly and mentions the user
- Remembers last 6 messages per user for context
