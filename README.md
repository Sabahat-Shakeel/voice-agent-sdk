# Voice Refund Agent 📞💬

A simple voice agent built with OpenAI's Agents SDK that acts as a refund assistant. It can listen to customer refund requests via voice, process them intelligently, and respond naturally.

Perfect for learning how to build AI-powered voice agents with OpenAI tools. 

## ✨ Features

- 🗣️ Voice input & output (real-time conversation)
- 🤖 Powered by OpenAI Agents SDK
- 💳 Handles refund-related queries (order status, refund requests, etc.)
- 🖥️ Fullstack: Next.js frontend + FastAPI (uvicorn) backend
- 🎯 Great for beginners exploring voice AI

## 🛠️ Tech Stack

- **Backend**: Python, FastAPI, Uvicorn, OpenAI Agents SDK
- **Frontend**: Next.js, React, Tailwind CSS (or your styling choice)

## 🚀 Quick Start

### Prerequisites

- Python 3.10+
- Node.js 18+
- OpenAI API key (set as environment variable: `OPENAI_API_KEY`)

### Backend Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Go to backend folder
cd backend

# Install dependencies with uv (recommended for faster installs)
uv sync

# Run the server
uvicorn main:app --reload --port 8000
Backend will run at http://localhost:8000
```
### Frontend Setup
```Bash
# From root directory (or open new terminal)
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
Frontend will run at http://localhost:3000
```
### 🎤 How to Use

Open the app in your browser (localhost:3000)
Allow microphone access
Click "Start Talking" or press the mic button
Speak your refund query (e.g., "I want to refund my order #12345")
The agent will listen, process, and reply via voice/text

### 🔧 Environment Variables
```
Create a .env file in the backend folder:
envOPENAI_API_KEY=your_openai_key_here
```

### 🤝 Contributing
Contributions are welcome! Feel free to:

Open issues
Submit PRs
Improve voice flow
Add better UI



learning AI voice agents ⭐
------------------------------------------------------------------
