# Tri-Valley AI Agent

AI-powered content tool for real estate agents — listing copy, lead follow-up, CMA letters, and review requests.

## Setup

1. Connect this repo to [Netlify](https://netlify.com)
2. In Netlify → Site Settings → Environment Variables → add:
   - Key: `ANTHROPIC_API_KEY`
   - Value: your `sk-ant-...` key
3. Deploy

The API key is stored securely in Netlify — it never appears in this repository.

## Tech
- Frontend: Vanilla HTML/CSS/JS
- Backend proxy: Netlify Functions (Node.js)
- AI: Anthropic Claude via secure server-side proxy
