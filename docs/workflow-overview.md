# Workflow overview

SupportFlow AI connects a series of steps in n8n to help organize incoming support tickets.

## Ticket flow

1. **Receive a ticket** — The workflow takes in the ticket details.
2. **Check the email** — It validates the sender’s email address.
3. **Classify the request** — Google Gemini suggests a category and priority.
4. **Record the ticket** — The ticket and its classification are saved in Google Sheets.
5. **Route a notification** — Gmail sends an email according to the workflow’s priority rules.
6. **Handle errors** — Global error handling helps catch workflow failures.

## Tools and roles

- **n8n** connects the steps and controls the workflow.
- **Google Gemini** assists with ticket classification and priority.
- **Google Sheets** stores ticket records.
- **Gmail** sends notifications.

## Privacy

Use fictional data in examples and screenshots. Do not publish credentials, API keys, real email addresses, customer messages, or other private information.
