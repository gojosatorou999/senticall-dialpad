# Senticall — Dial Pad

Static front-end for the Senticall coastal-hazard voice agent. Enter a phone
number and the agent calls you to take a hazard report.

Hosted on GitHub Pages because the agent's backend uses an ngrok free tunnel,
which allows only one endpoint — that one is reserved for Twilio's webhooks.

No credentials are stored in this repo: the page prompts for the dial password
once and keeps it in the browser's localStorage only.

The backend must be running for calls to work.
