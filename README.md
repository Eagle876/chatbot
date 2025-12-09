💬 Chat-Bot (HTML, CSS, JavaScript + Gemini API)

A responsive, interactive, and visually appealing AI-powered chatbot built using HTML, CSS, JavaScript, and Google Gemini API.
This chatbot supports custom knowledge-base responses, making it ideal for businesses, portfolios, educational platforms, or any website requiring smart automated interactions.

🚀 Features

🎨 Modern & User-Friendly UI
Designed with a clean, attractive interface for smooth user interaction.

🧠 Custom Knowledge-Base Support
Chatbot replies are generated based on your provided dataset, ensuring accurate and relevant responses.

🔗 Easy Website Integration
Easily embeddable into any website—just copy and paste the widget or script.

⚡ Fast & Precise Responses
Powered by Gemini API for quick and intelligent replies tailored to your knowledge base.

📦 Tech Stack

HTML5

CSS3

Vanilla JavaScript

Gemini API (Google AI Studio)

📁 Project Setup

Follow the steps below to run the chatbot locally:

1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

2️⃣ Add your Gemini API Key

Create a new file named config.js in the project folder and add:

const GEMINI_API_KEY = "YOUR_API_KEY_HERE";


🔐 Important:

Replace "YOUR_API_KEY_HERE" with your actual Gemini API key.

Do NOT commit your API key to GitHub.

Add config.js to your .gitignore.


No server required — it works directly in the browser.

🧠 Using a Custom Knowledge Base

You can modify knowledgeBase.js or similar file (if included) to customize/respond based on your own data.

Example:

const knowledgeBase = {
  "hello": "Hi! How can I assist you today?",
  "pricing": "Here is our pricing information..."
};


🔑 How to Get a Gemini API Key

Go to Google AI Studio → https://aistudio.google.com

Sign in using your Google account

Go to API keys

Generate a new key

📜 License

This project is open-source under the MIT License.

🤝 Contributions

Feel free to open issues, submit pull requests, or suggest enhancements!
