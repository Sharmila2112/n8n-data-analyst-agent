# n8n Data Analyst AI Agent

An n8n workflow that lets you chat with an AI agent to read and update data in Google Sheets.

## How it works
- **Trigger:** When chat message received
- **Agent:** AI Agent with Simple Memory and an OpenAI chat model
- **Tools:** Google Sheets, either "Get row(s) in sheet" or "Append or update row in sheet"

## Setup
1. In n8n, go to Workflows, then Import from file, and select `workflows/data-analyst-agent.json`.
2. Upload `data/data_analyst_agent_sample_data.xlsx` to Google Drive and open it as a Google Sheet.
3. Add your own OpenAI and Google Sheets credentials.
4. In both Google Sheets nodes, select your spreadsheet and sheet tab.
5. Open the chat and ask a question, e.g. "Which category has the highest profit margin?"

## Sample data
Synthetic e-commerce data (orders, customers, products, marketing, support tickets), Jan to Sep 2026, in INR.
