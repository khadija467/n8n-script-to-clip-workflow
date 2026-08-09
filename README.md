# n8n-script-to-clip-workflow
🎬 AI Script-to-YouTube Clips Automation

An AI-powered n8n workflow that turns a video script into structured YouTube footage research automatically.

🚀 What It Does

Script Lines
     ↓
Gemini AI Analysis
     ↓
Identify Main Subject
     ↓
Subject-Focused YouTube Search
     ↓
Select Best Video
     ↓
Google Sheets Results

✨ Key Features

📄 Processes scripts line-by-line

🧠 Uses Google Gemini to understand context

🎯 Identifies the main person/entity being discussed

🔎 Creates subject-focused YouTube searches

🎥 Finds and selects relevant footage

📊 Saves results automatically to Google Sheets

🔁 Loops through the complete script automatically

❌ Handles cases where no suitable video is found

Example

Script:

Fans are divided, critics are questioning it, and Fernando Alonso doesn't seem to care.

Search generated:

Fernando Alonso reaction interview contract controversy

Instead of a generic search, the workflow keeps the research focused on the actual subject.

🛠️ Built With

n8n — Workflow automation

Google Gemini API — Context & subject analysis

YouTube Data API — Video discovery

Google Sheets — Input & results storage

📂 Workflow

Start → Read Script → Loop → Gemini Analysis → Identify Subject → YouTube Search → Select Video → Save Result

🔐 Security

API keys and credentials are not included. Add your own Gemini, YouTube and Google Sheets credentials when importing the workflow.

📌 Setup

Import the workflow JSON into n8n.

Connect your Google Sheets credential.

Add your Gemini API key.

Add your YouTube Data API key.

Set your Google Sheet ID and tab names.

Test with a few script lines.

Run the complete workflow.

Tip: Never commit real API keys or private credentials to GitHub.

💼 Project Highlight

This project demonstrates practical AI automation, API integration, workflow orchestration, contextual search, and automated content research using n8n.
