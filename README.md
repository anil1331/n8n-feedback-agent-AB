# 🧠 n8n Feedback Automation Agent

An AI-powered workflow using **n8n**, **OpenAI**, **Airtable**, **Slack**, and **email** to categorize and route customer feedback in real-time.

## 💡 Features
- Detects form submissions and categorizes them into:
  - Complaints
  - Compliments
  - Feature Requests
- Uses OpenAI (GPT-3.5 Turbo) to analyze and classify feedback
- Routes categorized feedback to relevant Slack channels
- Sends confirmation emails to users for complaint submissions
- Stores all feedback data in Airtable for long-term tracking
- Automatically identifies user roles for customized handling

## ⚙️ Tech Stack
- [n8n](https://n8n.io/)
- [OpenAI API](https://platform.openai.com/)
- [Slack API](https://api.slack.com/)
- [Airtable](https://airtable.com/)
- Gmail or any SMTP email node

## 📁 File Info
- `n8n-feedback-workflow.json`: Full export of the automation workflow

## 🚀 Usage
1. Import the JSON file in your local or cloud n8n instance
2. Set up credentials for OpenAI, Airtable, Slack, and email
3. Connect with a form platform like Typeform, Google Forms, or Webhooks
4. Activate the workflow
