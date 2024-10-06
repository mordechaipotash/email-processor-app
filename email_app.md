# Email Processing Application

## Description
An application to process and display emails fetched from Gmail.

## Components

### EmailList
A component to display a list of emails.

### EmailDetail
A component to display the details of a selected email.

### SyncButton
A button to trigger email synchronization.

## Pages

### Home
The main page of the application, containing the EmailList, EmailDetail, and SyncButton components.

## API

### /api/sync-emails
An API endpoint to trigger email synchronization.

### /api/emails
An API endpoint to fetch processed emails.

## Database

### emails
A table to store processed email data.

### attachments
A table to store email attachment data.

## Integration
This application should integrate with the existing email_processor.py script for email processing and database operations.