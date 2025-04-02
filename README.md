# English to Arabic Conversational AI 🌐

This project transcribes English audio to text, translates it to Arabic, and generates **natural, conversational Arabic responses** using open-source machine learning models. It includes a user-friendly Gradio interface for testing.

---

## Features ✨
- **Speech-to-Text**: Transcribe English audio using OpenAI's Whisper.
- **Translation**: Convert English text to Arabic with MarianMT.
- **Conversational Arabic**: Generate informal/colloquial Arabic using AraGPT2.
- **Interactive UI**: Upload audio files and view results in real-time.

---

## Tech Stack 🛠️
- **Models**:
  - [Whisper](https://github.com/openai/whisper) (Speech-to-Text)
  - [MarianMT](https://huggingface.co/Helsinki-NLP/opus-mt-en-ar) (Translation)
  - [AraGPT2](https://huggingface.co/aubmindlab/aragpt2) (Conversational Arabic)
- **Framework**: Hugging Face Transformers, Gradio
- **Languages**: Python

---

## Setup & Installation 🚀

### Prerequisites
- Python 3.8+
- FFmpeg (for audio conversion)
- GPU recommended for faster inference

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kandil7/english-to-arabic-convo.git
   cd english-to-arabic-convo
