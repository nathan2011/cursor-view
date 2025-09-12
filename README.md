<div align="center">

# Cursor View

Cursor View is a local tool to view, search, and export all your Cursor AI chat histories in one place. It works by scanning your local Cursor application data directories and extracting chat data from the SQLite databases.

**Privacy Note**: All data processing happens locally on your machine. No data is sent to any external servers.

<p>
<a href="https://www.linkedin.com/in/sahar-mor/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue" alt="LinkedIn"></a>
<a href="https://x.com/theaievangelist" target="_blank"><img src="https://img.shields.io/twitter/follow/:theaievangelist" alt="X"></a>
<a href="http://aitidbits.ai/" target="_blank"><img src="https://github.com/saharmor/saharmor.github.io/blob/main/images/ai%20tidbits%20logo.png?raw=true" alt="Stay updated on AI" width="20" height="20" style="vertical-align: middle;"> Stay updated on AI</a>
</p>

<img width="761" alt="Screenshot 2025-05-01 at 8 22 43 AM-min" src="https://github.com/user-attachments/assets/39dbfa63-8630-4287-903c-f87833a9b435" />

</div>


## Setup & Running

1. Clone this repository
2. Install Python dependencies:
   ```
   python3 -m pip install -r requirements.txt
   ```
3. Install frontend dependencies and build (optional, pre-built files included):
   ```
   cd frontend
   npm install
   npm run build
   ```
4. Start the server:
   ```
   python3 server.py
   ```
5. Open your browser to http://localhost:5000

## Features

- Browse all Cursor chat sessions
- Search through chat history
- Export chats as JSON or standalone HTML
- Organize chats by project
- View timestamps of conversations

## Connect

Built by [Sahar Mor](https://www.linkedin.com/in/sahar-mor/) • Follow [@theaievangelist](https://x.com/theaievangelist) • [Stay updated on AI](http://aitidbits.ai/)
