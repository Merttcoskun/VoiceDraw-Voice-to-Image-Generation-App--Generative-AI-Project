# VoiceDraw-Voice-to-Image-Generation-App

![{21AF9B60-9A13-44C4-B16A-9BB99D34B15F}](https://github.com/user-attachments/assets/91f9a7b8-8304-449a-b794-c036d79b2220)

VoiceDraw is a Streamlit-based app that allows users to create AI-generated images using voice commands. The app records audio, transcribes it into text, and generates images based on the transcription using DALL-E 3 and Gemini Vision models.

Key Features:

- Voice Recording
Users can start and stop voice recordings, which are then processed and saved locally.

- Transcription
The app utilizes OpenAI's Whisper model to convert recorded audio into text.

- Image Generation
The transcribed text is used to generate images either with DALL-E 3 (text-to-image) or Gemini Vision (image enhancement).

- Session Management
The app leverages Streamlit's session state to manage the audio recording process and store generated images for easy access.

Technologies:
- Streamlit, OpenAI Whisper, DALL-E 3, Gemini Vision, PyAudio, FAISS
