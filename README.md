# ToneBridge
A human-centered AI tool that analyzes emotional tone and rewrites messages for clarity and empathy using Gemini AI.

# ToneBridge

ToneBridge is a human-centered AI tool that helps prevent miscommunication in digital messages by analyzing emotional tone and rewriting messages for clarity and empathy.

## 🚀 What It Does
- Analyzes text for emotional tone and misinterpretation risk
- Explains why a message may be misunderstood
- Rewrites messages into:
  - Calm & Friendly
  - Professional & Clear
  - Empathetic & Supportive

## 🛠️ Built With
- HTML, CSS and JavaScript
- PHP (Backend API)
- MySQL (Data Storage)
- Google Gemini AI (gemini-2.5-flash)

## 🧠 How It Works
1. User enters a message
2. Backend sends it to Gemini AI with a mediator-style prompt
3. AI returns tone analysis + rewritten versions
4. Results are displayed instantly in the UI

## 📸 Demo
https://www.youtube.com/watch?v=oOqmkjJGxn4

## 📦 Setup (Local)
1. Clone the repo
2. Import `database/tonebridge.sql` into MySQL
3. Add your DB credentials in `config/db.php`
4. Add your Gemini API key
5. Run on a local PHP server

## 🏁 Hackathon Project
Built as a solo hackathon submission focused on Human Interaction and AI-powered communication.
