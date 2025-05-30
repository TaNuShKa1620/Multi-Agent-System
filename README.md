# Multi-Agent-System Dashboard

A modern frontend interface for managing and visualizing the flow of documents (Emails, PDFs, JSON) through a multi-agent AI system. This system supports intelligent routing, context sharing, and process history tracking using a React + Tailwind CSS frontend and an AI-powered backend.

---

## 🚀 Features

- 🌐 Format and Intent Classification UI
- 📩 Email, JSON, and PDF Agent Interfaces
- 🧠 Shared Memory & Context Visualization
- 📊 Processing History & Logs Viewer
- 🛠️ Configurable Agent Settings
- 🌈 Built with React (TypeScript), Tailwind CSS, Vite

---

## 🏗️ Project Structure
project/
├── src/
│ ├── context/ # Global context providers (Memory, Toast)
│ ├── pages/ # Main pages (Dashboard, Settings, History)
│ ├── App.tsx # Main app component
│ ├── main.tsx # Entry point
│ └── index.css # Tailwind base styles
├── public/ # Static assets
├── tailwind.config.js # Tailwind config
├── tsconfig.json # TypeScript config
├── vite.config.ts # Vite dev/build config
└── package.json # Dependencies and scripts

# Images of the project
![image](https://github.com/user-attachments/assets/7a8b5126-d2fe-431b-99cd-d42a5b89a20f)
![image](https://github.com/user-attachments/assets/ab508f32-6a28-4ca7-b58e-3c4b8e5b5937)
![image](https://github.com/user-attachments/assets/16b58ef1-d580-4a0d-82bf-afc80266be72)
![image](https://github.com/user-attachments/assets/ae62ab40-e133-4f97-a542-8e131859abd6)
![image](https://github.com/user-attachments/assets/cf04defd-32af-4148-9f04-3b8bc828715c)

## 📦 Installation

git clone https://github.com/yourusername/project-bolt.git
cd project-bolt/project
npm install
📂 Pages
Dashboard: Entry point showing overall status and agents

Processing History: Shows previously classified and processed inputs

Settings: Toggle and configure agent behaviors

🎯 Future Enhancements
Integration with backend agents (Classifier, JSON Agent, Email Agent)

Real-time event handling (via WebSockets)

PDF Upload and Parsing UI

Auth + Role-based views

License
MIT © 2025 – Built with ❤️ for intelligent document processing

