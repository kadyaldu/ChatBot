# ChatBot

This is a Python script that creates a conversational assistant using the AssemblyAI, OpenAI, and ElevenLabs APIs. The assistant can transcribe the user's speech, generate a response using OpenAI's language model, and then convert the response to audio and play it back using ElevenLabs.

## Features

- Real-time speech transcription using AssemblyAI
- Response generation using OpenAI's GPT-4 language model
- Text-to-speech conversion and audio playback using ElevenLabs

## Requirements

- Python 3.x
- The following Python packages:
  - assemblyai
  - openai
  - elevenlabs
  - queue

## Installation

1. Clone the repository:

  
   git clone https://github.com/your-username/ai-powered-assistant.git
   
2. Install the required Python packages:

  
   pip install assemblyai openai elevenlabs
   
3. Obtain API keys for the following services:
   - AssemblyAI
   - OpenAI
   - ElevenLabs

4. Update the API keys in the script:

  
   aai.settings.api_key = "YOUR_ASSEMBLYAI_API_KEY"
   openai.api_key = "YOUR_OPENAI_API_KEY"
   elevenlabs.set_api_key("YOUR_ELEVENLABS_API_KEY")
   
## Usage

1. Run the script:

  
   python ai-powered-assistant.py
   
2. Speak into your microphone, and the assistant will transcribe your speech, generate a response, and play the response back to you.

3. To exit the conversation, press Ctrl + C.
