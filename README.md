# Bibliotech AI
BiblioTech AI is a cutting-edge AI research productivity platform that aids in research based on bibliographies. It allows users to radically increase their cognitive bandwidth when interfacing with source data and scientific literature. Bibliotech AI leverages large language models orchestrated in an agent to provide RAG functionality across a user's bibliography. Unlock Generative AI for summarization, smart semantic search, and auto-citation. User feedback, contributions, and attrributions are welcome.

Features

Quick Start
Prerequisites

Python 3.8+
Node.js 14+
An Anthropic API key for Claude models
A Pinecone API key for vector database

Installation

Clone the repository:
Copygit clone https://github.com/jaredgrogan/bibliotech.git
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
For support or inquiries, please open an issue or contact us at support@bibliotech.ai

Made with ❤️ by the BiblioTech AI Team
