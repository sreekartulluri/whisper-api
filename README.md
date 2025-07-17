# 🎙️ Whisper AI Speech-to-Text Transcription Project

This project leverages OpenAI's Whisper ASR (Automatic Speech Recognition) system to transcribe audio files into text with high accuracy. It includes advanced optimization techniques for model selection, decoding parameters, audio preprocessing, and long audio handling.

---

## 🚀 Features

- 📦 Supports all Whisper model sizes (`tiny`, `base`, `small`, `medium`, `large`)
- 🎛️ Customizable decoding parameters (`temperature`, `beam_size`, `best_of`)
- 🌍 Language selection (auto-detect or manual override)
- 🎧 Audio preprocessing (noise reduction)
- ✂️ Long audio chunking for consistent accuracy
---

## 🛠 Installation

Install all dependencies in one line:

```bash
pip install sounddevice scipy noisereduce numpy librosa soundfile openai-whisper

