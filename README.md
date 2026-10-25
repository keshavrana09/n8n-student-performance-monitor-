# Student Performance Monitor — n8n Workflow Automation

An automated student performance monitoring workflow designed to process student marks, generate reports, and streamline notifications using n8n and connected tools.

## About the Project

This project explores how workflow automation can reduce the manual effort required to monitor student performance. Student records are processed against predefined performance criteria, and the results can be shared with relevant stakeholders through automated reporting and notifications.

## Key Features

- **Data Integration:** Retrieve student records from Google Sheets.
- **Performance Analysis:** Categorize results using configured marks thresholds.
- **Report Generation:** Organize processed results into a report or CSV file.
- **Slack Integration:** Share reports or updates with a configured Slack destination.
- **Email Notifications:** Send completion notifications or alerts through the configured workflow.
- **Workflow Automation:** Connect multiple steps into a repeatable process.

## Tech Stack

- **Workflow Automation:** n8n
- **Data Source:** Google Sheets
- **Communication:** Slack and email
- **Output:** CSV / spreadsheet reports

## Workflow

1. Retrieve student marks from Google Sheets.
2. Process the records using predefined rules.
3. Categorize student performance.
4. Generate the required report.
5. Upload or share the report through the configured integration.
6. Send email notifications when the workflow completes.

## Getting Started

1. Install or access an n8n instance.
2. Import the workflow JSON file from this repository, if included.
3. Configure the required Google Sheets, Slack, and email credentials.
4. Update the spreadsheet ID, destination settings, and marks thresholds.
5. Test the workflow with sample student records before using real data.

**Security:** Do not commit credentials, API keys, or private student information to the repository.

## What I Learned

- Designing automated workflows with n8n.
- Integrating spreadsheets and communication tools.
- Applying rules to structured data.
- Automating reporting and notifications.
- Connecting multiple services into an end-to-end workflow.

## Developer

**Keshav Rana**

- GitHub: https://github.com/keshavrana09
- LinkedIn: https://www.linkedin.com/in/keshavrana09/

---

*An educational workflow automation project focused on data processing and reporting.*
