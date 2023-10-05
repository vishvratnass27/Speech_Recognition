# Simple Speech Recognition with Text-to-Speech

This repository contains a Python script for simple speech recognition using the `speech_recognition` library and includes a text-to-speech component for audio feedback. The code listens to your speech, transcribes it using Google's speech recognition service, and provides audio feedback. 

## Getting Started

1. Clone the repository to your local machine:
   ```
   git clone (https://github.com/vishvratnass27/Speech_Recognition.git)
   ```

2. Install the required Python libraries:
   ```
   pip install SpeechRecognition
   pip install text_to_speech
   ```

3. Run the Python script `speech_recognition.py` to use the speech recognition feature with text-to-speech feedback.

## How it Works

- The script initializes the speech recognition component, configures the microphone as the audio source, and adjusts for ambient noise levels.

- You can set the recording duration (in seconds) to control how long the script listens for your speech.

- When you run the script, it will display "Listening..." and start listening for your speech.

- After you speak, it will transcribe your speech using Google's speech recognition service and print the result to the console.

- If it can't understand what you said, it will provide an error message and prompt you to try speaking again.

- The script also includes a text-to-speech component for audio feedback. It will announce the result of the speech recognition.

## Example Usage

- In the example provided, the script listens for 5 seconds (`duration = 5`) but you can adjust this as needed.

- Run the script and speak into your microphone. It will transcribe what you say and provide audio feedback with the result.

## Dependencies

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/): Used for speech recognition.
- [text_to_speech](https://pypi.org/project/text-to-speech/): Used for text-to-speech audio feedback.

Feel free to explore and modify the code for your specific use cases. If you encounter any issues or have questions, please create an [issue](https://github.com/your_username/your_repository/issues) in the GitHub repository.

Enjoy using this simple speech recognition tool with text-to-speech feedback!
