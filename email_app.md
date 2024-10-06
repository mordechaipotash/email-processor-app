# Email Processing Application

## Components

### EmailList
- Display a list of emails with sender, subject, and date
- Include pagination or infinite scroll
- Allow sorting by date, sender, or subject
- Implement search functionality

### EmailDetail
- Show full email content including body, attachments, and headers
- Provide options to reply, forward, or delete the email
- Display attachments with download links

### SyncButton
- A prominent button to trigger email synchronization
- Show sync status (e.g., in progress, last synced time)

## Pages

### Home
- Layout with a sidebar containing EmailList
- Main content area for EmailDetail
- Header with SyncButton and user info

## API Endpoints

### /api/sync-emails
- POST request to trigger email synchronization
- Return sync status and last synced time

### /api/emails
- GET request to fetch processed emails
- Support pagination and filtering

### /api/email/:id
- GET request to fetch a single email's details

### /api/attachments/:id
- GET request to download an attachment