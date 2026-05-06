**Jarvis Realtime Voice Assistant**

A low-latency realtime AI voice assistant built using Python, LiveKit, and the Gemini Realtime API. The assistant supports natural voice conversations with streaming responses, voice activity detection, and noise cancellation for a smooth conversational experience. The project is designed with a modular architecture and Docker-based deployment support for scalable AI applications.

The assistant uses the Gemini native audio model for realtime speech interaction and integrates with LiveKit for communication and session management

**Features**
• Realtime AI voice interaction
• Gemini Realtime API integration
• LiveKit-based communication framework
• Streaming speech responses
• Voice activity detection using Silero VAD
• Noise cancellation support
• Modular and extensible Python architecture
• Docker deployment support
• Environment-based configuration handling

**Tech Stack**
• Python
• LiveKit Agents
• Gemini Realtime API
• Silero VAD
• Docker
• python-dotenv

Dependencies are managed using requirements.txt

1. Clone the Repository
   git clone https://github.com/perumal220606-hub/jarvis-gemini.git
   cd jarvis-gemini
2. Create Virtual Environment
   python -m venv .venv
3. Activate Environment
   .venv\Scripts\activate
4. Install Dependencies
   pip install -r requirements.txt
5. Configure Environment Variables
   GOOGLE_API_KEY=your_api_key
   LIVEKIT_API_KEY=your_livekit_key
   LIVEKIT_API_SECRET=your_livekit_secret
   LIVEKIT_URL=your_livekit_url
6. Download required files
   python gemini.py dowload-files
7. Running the agent
   python gemini.py console

**Future Improvements**
• Wake-word activation
• Edge-device optimization
• Local model fallback
• Advanced conversation memory


--Developed as a realtime conversational AI assistant project using LiveKit and Gemini Realtime APIs.

