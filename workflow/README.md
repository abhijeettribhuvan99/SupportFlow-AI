# Main workflow export

`SupportFlow main.json` is a sanitized export of the main SupportFlow AI workflow.

## What it does

It receives a support form submission, validates the email address, uses Gemini to suggest a category and priority, records the ticket in Google Sheets, and routes email notifications through Gmail.

## Before running it

1. Import the JSON file into your n8n instance.
2. Connect your own Gemini, Google Sheets, and Gmail accounts. Credentials are not included.
3. Choose your own spreadsheet and confirm its columns match the workflow.
4. Review the form, priority rules, and notification recipients.
5. Test with fictional ticket details and confirm the expected row and email are created before publishing the workflow.

The export is inactive. The separate error-alert workflow is not included in this file.
