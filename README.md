# Salesforce Account & Contact Automation with n8n

Automates creating or updating Salesforce accounts and contacts from Google Sheets.

## Features
- Reads contact and account data from Google Sheets
- Searches for existing Salesforce accounts
- Creates accounts if they do not exist
- Normalizes data
- Creates or updates contacts accordingly
- No code approach, fully automated

## Setup Steps
1. Authenticate Google Sheets and Salesforce in n8n
2. Prepare Google Sheet with contacts and account names
3. Copy Sheet ID and add it to the Google Sheet node
4. Import workflow JSON into n8n
5. Execute workflow

## Workflow Overview
- Searches Salesforce for existing accounts
- Branches based on account existence
- Normalizes data
- Creates/updates contacts
