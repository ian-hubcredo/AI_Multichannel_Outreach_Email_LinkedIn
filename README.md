# Sales Automation AI - Outreach Campaign

## Overview

An AI-powered multi-channel outreach campaign workflow. After the main lead qualification workflow completes, it filters approved prospects, generates personalized emails using GPT-4, generates LinkedIn messages using a separate GPT-4 instance, pushes email leads to Instantly and LinkedIn leads to Aimfox, and logs all outreach activity. It merges results from both channels for unified tracking.

## How It Works

```
Main Workflow Complete -> Filter Approved Prospects -> GPT-4 Generate Email + LinkedIn Message -> Push to Instantly (email) + Aimfox (LinkedIn) -> Log Outreach Activity -> Merge Results
```

## Integrations

- **OpenAI (GPT-4)** - Personalized email and LinkedIn message generation
- **Instantly** - Email campaign
- **Aimfox** - LinkedIn campaign

## Setup

1. Import `Sales_Automation_AI_Outreach_Campaign.json` into your n8n instance.
2. Configure OpenAI, Instantly, and Aimfox credentials.
3. Connect to the main lead qualification workflow.
4. Activate the workflow.
