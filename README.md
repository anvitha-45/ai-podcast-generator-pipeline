# Full-Stack AI Podcast Generator Pipeline

An end-to-end web application that accepts structural topic parameters from an interactive front-end web UI, executes generative script building via LLMs, synthesizes advanced voice data via third-party APIs, and returns downloadable media content in real time.

## 🚀 Features
- **Webhook API Interface:** Exposes a secure POST endpoint to receive event payloads from client architectures.
- **Generative AI Script Engine:** Chains structured prompt logic using Google Gemini models to construct conversational dialogue.
- **Audio Synthesis Engine:** Orchestrates custom outbound POST parameters to Murf AI endpoints for studio-quality Text-to-Speech (TTS) formatting.
- **Streamlined Media Response:** Automatically handles file downloads and passes structural binary data streams back to resolve the waiting client webhook hook.

## 🛠️ Tech Stack
- **Frontend App:** Lovable (https://cute-sound-studio.lovable.app/)
- **Backend Orchestration:** n8n Workflow Engine
- **AI Synthesis:** Google Gemini Chat Model & Murf AI API
- **Data Transport:** Webhooks, REST HTTP Request JSON payloads
