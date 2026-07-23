# Resume-Automation-System

An automated recruitment workflow that extracts candidate information from resumes uploaded to Google Drive and stores structured data into Google Sheets. This project eliminates manual resume screening and helps streamline the initial recruitment process.

## Overview

Recruiters often receive multiple resumes that need to be manually reviewed and entered into tracking sheets. This automation system solves that problem by automatically detecting new resumes, extracting candidate details, and updating a recruitment database.

The workflow is built using **n8n automation**, integrating Google Drive, resume parsing, and Google Sheets.

## Features

- 📂 Automatically monitors a Google Drive recruitment folder
- 📄 Detects newly uploaded resumes
- 🔍 Extracts candidate information from resumes
- 📊 Automatically updates Google Sheets with candidate details
- ⚡ Reduces manual data entry
- 🔄 Supports continuous workflow execution
- 🛠 No-code/low-code automation using n8n


## Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation |
| Google Drive API | Resume storage & monitoring |
| Google Sheets API | Candidate database management |
| Resume Parser | Information extraction |
| AI/NLP | Text processing |
| JSON | Data handling |


## Extracted Information

The system extracts details such as:

- Candidate Name
- Email Address
- Phone Number
- Skills
- Education
- Experience
- Resume Link
- Upload Date
