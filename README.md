# Generative AI Voice Bot

This project is a voice-based chatbot that combines Speech to Text (STT), a Large Language Model (LLM), and Text to Speech (TTS) to enable real-time interaction with users. The bot processes spoken input, generates appropriate responses using an LLM, and returns the response as speech. The entire system is hosted in a Google Colab notebook and uses Gradio for an intuitive user interface.

## Features

- **Speech to Text (STT)**: Converts spoken language into text using [Whisper-Tiny English](https://huggingface.co/openai/whisper-tiny.en).
- **Large Language Model (LLM)**: Generates context-aware responses using [TinyLlama-1.1B-Chat-v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
- **Text to Speech (TTS)**: Converts text responses back into speech using [Parler-TTS-Mini-v1](https://huggingface.co/parler-tts/parler-tts-mini-v1).
- **Gradio UI**: Provides a simple interface for interaction with the bot using a microphone.

## Project Setup

This bot is designed to run in Google Colab. The following steps will guide you through setting it up.

### Prerequisites

- A Google Colab account and load the [Voice-Bot.ipynb](Voice-Bot.ipynb)
- Basic knowledge of Python and machine learning concepts.
