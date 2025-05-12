# 🗣️ Simple Speech-to-Text System

## Overview

This project is a basic implementation of a Speech-to-Text (STT) system using Python. It utilizes microphone input to capture spoken language and converts it into written text using open-source speech recognition libraries.

## Key Components

- **Audio Capture:** Uses the microphone to collect real-time speech input.
- **Speech Recognition:** Employs the `speech_recognition` library to transcribe audio into text.
- **Error Handling:** Provides basic error handling for silence, unclear speech, or connection errors.
- **Interactive Output:** Displays the transcribed text in the notebook environment for immediate feedback.

## Installation

1. **Install required libraries:**
    ```bash
    pip install speechrecognition pyaudio
    ```

    > If `pyaudio` fails to install on your system:
    ```bash
    pip install pipwin
    pipwin install pyaudio
    ```

2. **Ensure microphone access is enabled** on your system.

## Usage

1. Open the notebook `Speech2text.ipynb` in Jupyter or Google Colab.
2. Execute the cells in order.
3. When prompted, speak into the microphone.
4. The system will convert your speech into text and display it.

## Plain Explanation

Think of this project like teaching your computer to listen and write down what you say. When you speak into your microphone, the computer:
1. **Listens** to your voice.
2. **Understands** what you're saying using a language processing tool.
3. **Writes down** the words it heard.

It’s a simple version of the technology behind voice assistants like Siri or Google Assistant.

This project is ideal for learning how speech recognition works at a basic level, without diving into complex machine learning or deep learning models.

## License

This project is open-source and licensed under the MIT License.
