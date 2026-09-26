# AI Performance Marketing Analyst

An automated AI-powered Performance Marketing analysis workflow built with **n8n, Google Sheets, Gemini AI, and JavaScript**.

The system reads campaign performance data, analyzes key advertising metrics, identifies high-performing and underperforming campaigns, and generates actionable optimization recommendations automatically.

## 🚀 Project Overview

This project automates the initial performance marketing analysis process that marketers often perform manually.

The workflow:

1. Reads campaign data from Google Sheets
2. Processes and prepares campaign metrics
3. Calculates important performance indicators
4. Sends campaign data to Gemini AI
5. Generates an AI-powered performance analysis
6. Identifies campaigns that need attention
7. Provides optimization recommendations
8. Stores the generated report back into Google Sheets
9. Runs automatically on a daily schedule

## 🔄 Workflow

```text
Schedule Trigger
       ↓
Google Sheets
       ↓
Data Processing
       ↓
JavaScript Analysis
       ↓
AI Agent
       ↓
Gemini AI
       ↓
Performance Analysis
       ↓
Google Sheets
📊 Metrics Analyzed

The workflow analyzes metrics such as:

Spend
Impressions
Clicks
Conversions
Revenue
CTR
CPC
CPM
CVR
CPA
ROAS
🤖 AI Analysis

The AI analyst generates:

Executive Summary

Overview of the overall advertising portfolio.

Top Performers

Identifies campaigns showing strong performance.

Campaigns Needing Attention

Highlights campaigns with inefficient performance or negative ROI.

Recommended Actions

Provides optimization suggestions such as:

Budget adjustments
Campaign optimization
Creative testing
Bid adjustments
Targeting improvements
Efficiency improvements
🛠️ Tech Stack
n8n — Workflow automation
Google Sheets — Campaign data & report storage
Google Gemini AI — AI-powered campaign analysis
JavaScript — Data processing and metric analysis
⏰ Automation

The workflow is configured to run automatically on a daily schedule.

New campaign analysis reports are generated and stored in Google Sheets without requiring manual execution.

📸 Workflow Architecture

The automation follows this structure:

Schedule Trigger → Google Sheets → JavaScript → AI Agent → Gemini AI → Google Sheets

💡 Use Case

This project demonstrates how AI and workflow automation can be used in Performance Marketing to reduce repetitive analysis work and speed up campaign optimization.

It can be adapted for:

Google Ads
Meta Ads
Multi-platform campaign reporting
Automated marketing dashboards
Daily performance monitoring
🔮 Future Improvements
Automated email delivery of daily reports
Slack/Telegram notifications
Looker Studio dashboard integration
Google Ads API integration
Meta Ads API integration
Automated anomaly detection
Campaign budget recommendations
👨‍💻 Built By

Harikrishna

Performance Marketing | SEO | AI Automation
