🤖 AI Chatbot

An AI-powered chatbot built with Assistant-UI
, integrated with Google AI SDK, and deployed on Vercel.

🌐 Live Demo: Chatbot on Vercel

🚀 Features

Simple UI powered by Assistant-UI

Google AI SDK integration

Easy to deploy on Vercel

Works out-of-the-box with minimal setup

📂 Project Setup
1. Create Project Folder
mkdir chatbot
cd chatbot

2. Open in VS Code
code .

3. Initialize Chatbot Project

Run this command in terminal:

npx assistant-ui@latest create

4. Install Dependencies
npm install ai @assistant-ui/react-ai-sdk @ai-sdk/google

5. Get API Key

▶️ Run Locally

Start the development server:

npm run dev


Open browser at http://localhost:3000

📦 Deployment

This chatbot is deployed on Vercel.
You can deploy your own by connecting the repo to Vercel
.

Live project: 👉 https://chat-bot-eight-sigma.vercel.app/

🛡️ Important Notes

Never commit your real API key in public repos. Use .env files instead.

Replace demo API key with your own for production.

📝 License

This project is for learning & educational purposes only.

👉 Ye README tumhare GitHub repo ke README.md file me paste kar do.

Chahoge mai tumhare liye ek .env setup guide bhi dal du is README me, taaki API key safe rahe?

You said:
hnn
ChatGPT said:

Perfect 🔥 Mai ab tumhare README me .env setup guide bhi add kar deta hoon taaki API key safe rahe aur professional lage.

🤖 AI Chatbot

An AI-powered chatbot built with Assistant-UI
, integrated with Google AI SDK, and deployed on Vercel.

🌐 Live Demo: Chatbot on Vercel

🚀 Features

Simple UI powered by Assistant-UI

Google AI SDK integration

Secure API key management with .env

Easy to deploy on Vercel

📂 Project Setup
1. Create Project Folder
mkdir chatbot
cd chatbot

2. Open in VS Code
code .

3. Initialize Chatbot Project

Run this command in terminal:

npx assistant-ui@latest create

4. Install Dependencies
npm install ai @assistant-ui/react-ai-sdk @ai-sdk/google

🔑 API Key Setup (Environment Variables)

Visit Google Gemini API
 and generate your API key.

In your project root, create a file named .env.local

Add your API key inside it like this:

GOOGLE_API_KEY=your_api_key_here


⚠️ Important: Never push .env.local file to GitHub. Add it to .gitignore (already default in Next.js projects).

▶️ Run Locally

Start the development server:

npm run dev


Now open browser at http://localhost:3000

📦 Deployment

This chatbot is deployed on Vercel.
For your own deployment:

Push code to GitHub.

Connect repo to Vercel
.

In Vercel dashboard → Project Settings → Environment Variables, add your API key:

Key: GOOGLE_API_KEY
Value: your_api_key_here


Live project: 👉 https://chat-bot-eight-sigma.vercel.app/

🛡️ Important Notes

Never expose your API key directly in code.

Use .env for local development and Vercel Environment Variables for deployment.

📝 License

This project is for learning & educational purposes only.
