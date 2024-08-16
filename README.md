# Voice Assistant with Whisper and LLaMA

This project is a Python-based voice assistant that listens for a wake word, processes spoken prompts, and generates responses using the Whisper and ollama models. The assistant runs continuously, listening for the wake word "trinity," and responds to user prompts using state-of-the-art AI models.

## Features

- **Wake Word Detection**: The assistant listens for a predefined wake word ("trinity") to activate.
- **Speech Recognition**: Utilizes Whisper models (`tiny.en` and `base.en`) for accurate speech transcription.
- **AI-Powered Responses**: Generates responses using the chosen ollama model model, specifically the `llama2-uncensored` variant.
- **Text-to-Speech**: Responds to users through text-to-speech (TTS) using platform-specific tools.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Have downloaded ollama via their website ollama.com/download and follow the instructions there.

- Python 3.8 or higher
- The following Python libraries:
  - `ffmpeg`
  - `pyaudio`
  - `speech_recognition`
  - `whisper`
  - `ollama`
  - `pyttsx3` (for non-macOS platforms)

You are going to need brew in order to download ffmpeg and use pip for the other python libraries.
IMPORTANT: Some of these python libraries were giving me greif so I reccomend setting up a python vm in order to download them.
