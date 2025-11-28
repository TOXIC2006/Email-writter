Email Reply Generator with Tone Selection + Chrome Extension

An AI-powered tool that generates smart, context-aware email replies with customizable tones.
This project includes a web-based email reply generator and a Chrome Extension for seamless, real-time usage inside Gmail or any email platform.

🚀 Features

✨ AI-powered email reply generation

🎭 Tone selection (Formal, Friendly, Concise, Professional, etc.)

⚡ One-click Chrome Extension integration

📥 Automatically detects selected email text

🧠 Context-aware, human-like responses

🔒 API-based secure communication

📱 Lightweight, fast, and easy to use

🧩 Tech Stack

Frontend: HTML, CSS, JavaScript

Chrome Extension: Manifest v3, JS

Backend / AI Model: OpenAI API (or your chosen LLM API)

Other Tools: Prompt Engineering, DOM Content Extraction

📌 Project Structure
📦 Email-Reply-Generator
│
├── extension/
│   ├── popup.html
│   ├── popup.js
│   ├── styles.css
│   ├── manifest.json
│   └── icon.png
│
├── web-app/
│   ├── index.html
│   ├── script.js
│   ├── styles.css
│
├── screenshots/
│   ├── extension-ui.png
│   ├── sample-reply.png
│
└── README.md

🛠️ How It Works

User selects or pastes an email message

User chooses a tone from the dropdown

System sends the input + tone to the AI model

AI generates a refined, context-appropriate reply

Chrome extension displays it instantly (copy/paste ready)

🌐 Chrome Extension Setup

Clone/download the repository

Open chrome://extensions in Chrome

Enable Developer Mode (top right)

Click Load Unpacked

Select the extension/ folder

Extension will be added and ready to use


Methodology

NLP/LLM-based generation using prompt engineering

Extract selected text from the active page

Use AI to generate response variations based on tone

Render the reply within extension UI

Provide copy-to-clipboard functionality

📈 Results

High-quality, natural email replies

Supports multiple tones

Improves communication speed and consistency

Works directly inside browser → saves time

📌 Future Enhancements

Multi-language support

Email summarization

Custom tone slider (tone strength control)

Integration with Outlook, Yahoo, and other platforms

Auto-insert reply directly into Gmail compose box

🤝 Contributing

Contributions are welcome!
Feel free to submit issues or pull requests.
