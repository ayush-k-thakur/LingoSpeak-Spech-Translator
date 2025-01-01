# Real-Time Voice Translator

This project is a real-time voice translator GUI application built using Python. It uses various libraries to recognize speech, translate it into different languages, and play the translated text as speech.

## Features

- Real-time speech recognition
- Translation between multiple languages
- Text-to-speech for translated text
- Graphical User Interface (GUI) using Tkinter
- Multi-threading for efficient CPU usage

## Requirements

- Python 3.7+
- gTTS
- pyaudio
- playsound==1.2.2
- cx-Freeze
- deep-translator
- SpeechRecognition
- google-transliteration-api

## Installation

1. Clone the repository:
    ```sh
    gh repo clone ayush-k-thakur/LingoSpeak-Spech-Translator
    cd voice-translator
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv env
    source env/bin/activate  # On MAC 
    env\Scripts\activate    #On Windows
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```sh
    python main.py
    ```

2. Select the input and output languages from the dropdown menus.

3. Click the "Start Translation" button to start the real-time translation.

4. Speak into the microphone. The recognized text will be displayed in the "Recognized Text" box, and the translated text will be displayed in the "Translated Text" box.

5. The translated text will also be played as speech.

6. Click the "Kill Execution" button to stop the translation.

## Building the Executable

1. Install `cx-Freeze`:
    ```sh
    pip install cx-Freeze
    ```

2. Build the executable:
    ```sh
    python setup.py build
    ```

3. The executable will be created in the `build` directory.


## Acknowledgements

- [gTTS](https://pypi.org/project/gTTS/)
- [pyaudio](https://pypi.org/project/PyAudio/)
- [playsound](https://pypi.org/project/playsound/)
- [cx-Freeze](https://pypi.org/project/cx-Freeze/)
- [deep-translator](https://pypi.org/project/deep-translator/)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [google-transliteration-api](https://pypi.org/project/google-transliteration-api/)