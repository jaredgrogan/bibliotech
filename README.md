# Bibliotech AI
BiblioTech AI is a cutting-edge AI-powered writing assistant that transforms spoken words into polished prose. It leverages advanced language models and natural language processing techniques to provide a seamless dictation-to-writing experience.
Features

🎙️ Real-time speech-to-text conversion
🧠 AI-powered text refinement and enhancement
📝 Multiple writing styles (e.g., academic, journalistic, creative)
💻 Cross-platform support (iOS app and web interface)
🔒 Privacy-focused with optional on-device processing

Quick Start
Prerequisites

Python 3.8+
Node.js 14+
An Anthropic API key for Claude models
A Pinecone API key for vector database

Installation

Clone the repository:
Copygit clone https://github.com/yourusername/bibliotech-ai.git
cd bibliotech-ai

Install backend dependencies:
Copypip install -r requirements.txt

Install frontend dependencies:
Copycd frontend
npm install

Set up environment variables:
Copycp .env.example .env
Edit .env and add your API keys.

Running the Application

Start the backend server:
Copyuvicorn main:app --reload

In a new terminal, start the frontend:
Copycd frontend
npm start

Open your browser and navigate to http://localhost:3000

Architecture
BiblioTech AI uses a modular architecture combining on-device processing with cloud-based AI models:
Copy[iOS/Web Client] <-> [FastAPI Backend] <-> [Claude AI Models]
                                       <-> [Pinecone Vector DB]
Contributing
We welcome contributions! Please see our Contributing Guide for more details.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

Anthropic for their Claude AI models
Pinecone for vector embedding storage
FastAPI for the efficient Python web framework
React for the frontend framework

Contact
For support or inquiries, please open an issue or contact us at support@bibliotech-ai.com.

Made with ❤️ by the BiblioTech AI Team
