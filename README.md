# AI Assistant with Speech Recognition and OpenAI Integration

## Discription

This Python script is an AI assistant that utilizes speech recognition to understand user queries, interacts with the OpenAI API to generate responses, and uses text-to-speech conversion to communicate the responses back to the user.

## Table of Contents

- Description
- Table of Contents
- Technology
- Installation
- Usage
- Notes
- Link

## Technology Used

- **Python**: The core programming language used for developing the AI assistant.
- **OpenAI API**: Integrated to generate responses based on user queries.
- **SpeechRecognition**: Python library used for speech recognition to transcribe user queries.
- **pyttsx3**: Python library used for text-to-speech conversion to communicate responses back to the user.

## Installation

Before running the script, ensure you have Python installed on your system. You can download Python from [here](https://www.python.org/downloads/).

1. Install the required dependencies using pip:

```bash
pip install openai pyttsx3 SpeechRecognition

**Note** If you have the new version of Python installed, you will have to use pip3 instead of pip.

2. Obtain OpenAI API Key:

You need to sign up for an account on the OpenAI platform and obtain an API key. Once you have the API key, replace the empty string ('') in the script with your API key:

Set OpenAI key
openai.api_key = 'YOUR_API_KEY'

## Usage

1. Run the script python <YOUR_FILE_NAME> 
    Example:
    python chtgtp_voice.py 
    **Note** If you have the new version of Python installed you will need to run python3 chtgtp_voice.py
2. Wait for the assistant to prompt you to say the keyword "Geanie" 
    to start recording a question.
3.  After saying "Geanie," ask your question. The assistant 
    will transcribe your speech, generate a response using the OpenAI API, and speak the response back to you.

    You can continue asking questions by repeating steps 2 and 3.


## Notes
Please note that the text-to-speech library pyttsx3 may have compatibility issues with Python 3.12. It's recommended to use Python 3.7 for compatibility. If you encounter installation errors related to pyttsx3 with Python 3.12, consider using Python 3.7 instead.

## Link
https://github.com/sarahizar/Text_Editor