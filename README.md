# VoiceBot
Run it by first installing all the dependencies
# Voicebot with LiveKit and OpenAI GPT-4

This project is a real-time voice assistant built using **LiveKit** for real-time communication and **OpenAI GPT-4** for natural language processing (NLP). The system captures audio input, transcribes it using Whisper, processes the text using OpenAI GPT-4, and then converts the response into speech using a Text-to-Speech (TTS) service.

## Features

- Real-time voice interaction using **LiveKit**.
- Speech-to-Text (STT) for transcribing user audio input.
- Natural language conversation powered by **OpenAI GPT-4**.
- Text-to-Speech (TTS) for generating audio responses.
- Easy integration with **LiveKit** WebRTC for audio/video streams.

## Requirements

### Backend Requirements
- Python 3.8+
- Flask (or any Python web framework you prefer)
- OpenAI GPT-4 API key
- LiveKit for real-time communication (WebRTC)
- Whisper for Speech-to-Text (STT) (Optional)
- Coqui TTS or other TTS service

### Frontend Requirements
- JavaScript (React.js or Vue.js)
- LiveKit WebRTC Client SDK

### Libraries to Install

#### Python
Install the following Python libraries:

```bash
pip install flask openai livekit python-dotenv
