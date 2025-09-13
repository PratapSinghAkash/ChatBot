🤖 AI Chatbot

An AI-powered chatbot built with Assistant-UI
, integrated with Google AI SDK, and deployed on Vercel.

🌐 Live Demo: Deployed Chatbot

🚀 Features

Conversational AI chatbot

Powered by Google Gemini API

Built with Assistant-UI and React SDK

Secure API key management via environment variables

One-click deployment on Vercel

📂 Project Setup
1. Create Project Folder
mkdir chatbot
cd chatbot

2. Open in VS Code
code .

3. Initialize Chatbot Project
npx assistant-ui@latest create

4. Install Dependencies
npm install ai @assistant-ui/react-ai-sdk @ai-sdk/google

🔑 Environment Variables

Create a .env.local file in the project root.

Add your Gemini API key:

GOOGLE_API_KEY=your_api_key_here


Make sure .env.local is in your .gitignore file (to keep it private).

▶️ Run Locally
npm run dev


Open http://localhost:3000
 in your browser.

📦 Deployment

Push your code to GitHub.

Connect the repo to Vercel
.

In Vercel → Project Settings → Environment Variables, add:

Key: GOOGLE_API_KEY
Value: your_api_key_here


Deploy 🎉

🛡️ Notes

Never share your API keys publicly.

Use .env.local for local development.

Use Vercel Environment Variables for production.

📝 License

This project is for educational and learning purposes only.
