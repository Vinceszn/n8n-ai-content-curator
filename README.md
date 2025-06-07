# 🤖 AI Content Curator (n8n Workflow)

This is a fully automated workflow built in [n8n](https://n8n.io) that curates top tech content from Reddit and Hacker News using AI-style logic — then formats and posts it to Discord, Reddit, and more.

## 🧠 Features
- Pulls data from r/all, r/programming, and Hacker News
- Scores each post using custom logic (engagement, recency, quality)
- Assigns sentiment + topic category
- Formats posts into Discord embeds, Reddit markdown, and email summaries
- Auto-posts to Discord every 6 hours

## 🚀 Quick Start
1. Import the `ai-curator-workflow.json` into your n8n instance
2. Update webhook URLs and API keys where needed
3. Enable the schedule trigger
4. Done! Your AI curator is live

## 📂 File Structure
- `workflows/ai-curator-workflow.json` — the main n8n export

## 💬 Want to Contribute?
Open issues or submit PRs! Feedback is welcome.

## 📄 License
MIT
