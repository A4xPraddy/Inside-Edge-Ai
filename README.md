# INSIDE EDGE — AI Powered Productivity Chrome Extension

INSIDE EDGE is an intelligent Chrome extension designed to enhance your browsing experience with
AI summaries, smart translations, quick definitions, and instant note-saving — all accessible directly from your right-click menu.

It provides a smooth UI with animated floating bubbles, language selection popups, and powerful Gemini-based reasoning.

#   Features
🔹 1. AI Summaries (Gemini-Powered)

Right-click any selected text → Summarize selected text

Generates clean, concise summaries

Displayed instantly inside an animated floating bubble

🔹 2. AI Definition Lookup

Right-click → Define selected word

Part of speech

1–2 simple definitions

A clear example sentence

Uses Gemini AI for dictionary-style responses

🔹 3. Smart Multi-Language Translation

Right-click → Translate selected text

Auto-detects source language

Supports: English, Spanish, French, German, Hindi, Italian, Japanese, Chinese, Arabic, Portuguese, Russian

Uses MyMemory API

Handles long text by safely splitting it into chunks

Translation result appears in a bubble

🔹 4. Save Selected Text to Notes

Right-click → Save selected text to Notes

Saved using chrome.storage.sync

Stored notes persist across sessions

Bubble shows confirmation + auto-closes

🔹 5. Beautiful Inline Floating Bubbles

Every AI response appears inside a smooth UI bubble with:

Slide-in animation

Close button

Clickable links

Adjustable size

Light pink modern theme

Optional Save to Notes button

🔹 6. Article Text Extraction

Used internally for page summaries and popups.

Prefers <article>

Falls back to <p>

Extracts full visible text as last resort

🔹 7. API Key Setup Page

INSIDE EDGE uses the Gemini API.

Add your API key inside options.html

Saved securely via Chrome sync storage

Automatically opens the options page if the key is missing

# Project Structure
INSIDE-EDGE/
│── manifest.json
│── background.js
│── content.js
│── options.html
│── options.js
│── icons/
└── README.md

# Tech Stack

Chrome Extensions (Manifest V3)

JavaScript (ES6+)

Google Gemini API

MyMemory Translation API

Chrome Storage API

Chrome Scripting API

Custom animated UI bubbles

# How It Works
1. User selects text
2. Right-click → chooses an action
3. background.js processes the request

Calls Gemini for summaries/definitions

Uses MyMemory for translation

Saves text to notes

Sends results back to content script

4. content.js displays a bubble

Animated popup

Buttons

Language selection UI for translations

# Setup Instructions
1️⃣ Add your Gemini API Key

Install the extension

It automatically opens the options page

Enter your Gemini API Key

Done! The key is saved securely

# Running the Extension Locally

[Visit : (https://chromewebstore.google.com/detail/inside-edge/ceenpgncllidogilkmbgkblopjeapnme?utm_source=ext_app_menu)}

Enable Developer Mode

Click Load unpacked

Select the project folder

Start using INSIDE EDGE 🎉

🛡 Permissions Used

contextMenus – Right-click actions

storage – Save API key & notes

scripting – Inject content.js

activeTab – Access webpage context

tabs – Script communication

# Future Enhancements

Export Notes (PDF/Notion/MD)

Full-page AI summarizer

AI rewrite/paraphrase mode

Advanced dictionary mode

Custom bubble themes

# Contributors

Prasad Mitnapure | Arya Sagar<br>
Full-Stack Developer | AI/ML Developer

# ⭐ Support

If you like this project, please ⭐ star the repository on GitHub — it helps a lot!
