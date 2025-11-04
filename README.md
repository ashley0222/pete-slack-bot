# PETE Slack Bot (Render + Slack HTTP Mode)

## Env Vars
- SLACK_BOT_TOKEN (xoxb-…)
- SLACK_SIGNING_SECRET
- OPENAI_API_KEY
- DRIVE_LIBRARY_URL
- PORT (Render sets; default 10000)

## Start locally
npm install
SLACK_BOT_TOKEN=... SLACK_SIGNING_SECRET=... OPENAI_API_KEY=... node index.js

## Deploy on Render
Build: npm install
Start: node index.js
