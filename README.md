# Oliver Robot Application

## Overview
Oliver Robot is a voice-interactive assistant with a friendly and helpful character, designed to make office tasks more enjoyable. Using the power of OpenAI's ChatGPT API, Oliver can understand and conversationally respond to voice commands.

## Prerequisites
- Python 3.11 or lower
- Internet connection

## Installation
**Step 1: Clone the Repository**
First, clone the repository containing the `main.py` and `OliverRobot` classes to your local machine:
```bash
git clone [URL_of_the_Repository]
cd [Repository_Name]
```

**Step 2: Set Up Python Environment**
Ensure that Python 3.11 or lower is installed on your system. You can download it from the official Python website.

**Step 3: Install Required Libraries**
Install the necessary Python libraries using pip, including the `OpenAi` library which allows Oliver to use the ChatGPT API for natural language understanding and response generation:
```bash
pip install speechrecognition pygame openai
```
- **SpeechRecognition**: For processing and transcribing audio input.
- **Pygame**: For handling audio playback.
- **Openai**: For accessing GPT models and Whisper API for text and audio processing.

**Step 4: Obtain OpenAI API Key**
You will need an API key from OpenAI to use their models. Sign up or log in to your OpenAI account and generate an API key from the OpenAI API Dashboard.

**Step 5: Set API Key**
Replace the placeholder in main.py with your actual OpenAI API key:
```python
api_key = "your-openai-api-key"
``` 

## Running the Application
Run the application using Python:
```bash
python main.py
```

## Usage
Interact with Oliver Robot as you would with a friendly office colleague. Begin your command with "Oliver" to catch his attention, and feel free to chat about your day or ask for assistance with tasks. Oliver's character is designed to be:
- **Engaging**: Oliver has a warm and inviting personality, making interactions pleasant.
- **Helpful**: Whether it's setting reminders or providing updates, Oliver is here to help.
- **Witty**: Expect a clever quip or a light-hearted joke to brighten your day.

The robot will respond and perform actions based on the given commands. It can interact, provide status updates, or acknowledge requests like "empty trash."
For example, you might say, "Oliver, can you pick up the trash on the first floor?" and Oliver will take care of trash for you.

## Demonstration
Watch Oliver in action and see how he interacts with users in this video: 
[![Oliver Robot](https://github.com/alireza7575/Oliver-Robot/assets/41507280/e2231655-53b0-4954-8154-5d56f54e43ee)](https://youtu.be/bHiHujXHWiA "Oliver Robot")

## Troubleshooting
- Ensure your microphone is properly set up and working.
- Check your internet connection as the application requires online access for API calls.
- If you encounter any errors with API limits or keys, verify your OpenAI account and API key status.
