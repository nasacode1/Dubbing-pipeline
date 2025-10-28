English → Hindi Dubbing Pipeline

This project implements a **complete multilingual dubbing pipeline** that converts English audio into natural-sounding Hindi speech.  

🚀 Features
- 🎧 **Audio Preprocessing:** Converts uploaded `.m4a` or `.wav` files into a uniform WAV format using `pydub`.
- 🗣️ **Voice Activity Detection (VAD):** Detects speech regions using **Silero VAD**.
- 📝 **Automatic Speech Recognition (ASR):** Transcribes English speech using **OpenAI Whisper**.
- 🌐 **Machine Translation:** Translates English text to Hindi via **Helsinki-NLP MarianMT**.
- 🔊 **Text-to-Speech (TTS):** Synthesizes Hindi audio with **Bark (suno/bark-small)**.
- 📊 **Visualization:** Plots waveform with detected speech segments using `matplotlib`.
