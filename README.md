# 📧 AI Email Classifier — n8n Workflow

Automatically classifies incoming Gmail emails into 
Work, Personal, or Junk using n8n workflow automation.

## 🔄 Workflow Overview
![Workflow](screenshots/workflow-overview.png)

## ⚙️ How It Works
1. **Gmail Trigger** — watches for new incoming emails
2. **Edit Fields** — extracts subject, sender, body content
3. **IF nodes** — applies keyword-based classification rules
4. **Gmail Label nodes** — auto-applies labels (Work/Personal/Junk)

## 🚀 How to Use
1. Install [n8n](https://n8n.io)
2. Import `email-classifier-workflow.json`
3. Connect your Gmail account
4. Activate the workflow

## 🛠 Tools Used
- n8n (workflow automation)
- Gmail API (trigger + labeling)
