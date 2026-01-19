Automated-Ocr-Invoice-Processing

Overview This project is an automated document processing workflow built in n8n. It allows users to upload invoice files through a form, extracts text using OCR, identifies key invoice information with AI, and automatically sends the extracted details via email. The system reduces manual data entry, saves time, and improves accuracy in invoice handling.

How It Works

A user submits a form with an invoice file and email address.

The uploaded file is sent to the Mistral OCR API for text extraction.

A temporary secure URL is generated for the document.

OCR results are processed to extract important fields such as invoice number, customer name, and company address.

The workflow checks whether the invoice number is successfully extracted.

If valid data is found, an automated email is sent with the invoice details.

Key Features • Automated file upload using n8n Form Trigger • OCR-based text extraction using Mistral OCR • AI-powered information extraction • Conditional logic to validate extracted data • Automatic email notification with invoice details • End-to-end automation without manual intervention

Technologies Used • n8n workflow automation • Mistral OCR API • OpenAI language model for data extraction • Gmail API for email notifications

Use Cases • Invoice processing and validation • Accounts and finance automation • Document digitization systems • Internship or academic automation projects • Small business workflow automation

Setup Instructions

Import the workflow JSON file into n8n.

Configure API credentials for Mistral OCR and OpenAI.

Connect and authorize a Gmail account in n8n.

Activate the workflow.

Submit an invoice through the form to test the automation.

Benefits This workflow minimizes human effort, speeds up invoice processing, and ensures consistent and accurate extraction of important business data. It is suitable for both learning purposes and real-world automation use.

Status The workflow is currently inactive by default and can be activated after proper credential configuration.
