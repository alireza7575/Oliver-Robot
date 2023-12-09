# README for Oliver Robot Application

## Overview
This README provides instructions for setting up and running the `main.py` script for the Oliver Robot application, a voice-interactive robot designed for office assistance tasks.

## Prerequisites
- Python 3.11 or lower
- Internet connection

## Installation
**Step 1: Clone the Repository**
First, clone the repository containing the `main.py` and `OliverRobot` class to your local machine:
```bash
git clone [URL_of_the_Repository]
cd [Repository_Name]
```

**Step 2: Set Up Python Environment**
Ensure that Python 3.11 or lower is installed on your system. You can download it from the official Python website.

**Step 3: Install Required Libraries**
Install the necessary Python libraries using pip:
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
After starting the application, follow these steps:
1. Speak to Oliver Robot. Begin your command with "Oliver" to ensure the robot recognizes the command.
2. The robot will respond and perform actions based on the given commands. It can interact, provide status updates, or acknowledge requests like "empty trash."

## Troubleshooting
- Ensure your microphone is properly set up and working.
- Check your internet connection as the application requires online access for API calls.
- If you encounter any errors with API limits or keys, verify your OpenAI account and API key status.