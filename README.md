# Text to Speech Converter

This Python script utilizes the Tkinter library to create a simple GUI application for converting text to speech. The application uses the `gTTS` (Google Text-to-Speech) library to convert the entered text into speech and the `playsound` library to play the generated audio.

## Prerequisites

Before running the script, make sure you have the required libraries installed. You can install them using the following:

```bash
pip install tk
pip install gtts
pip install playsound
```
## Usage

1. Run the script.
2. Enter the desired text in the provided text entry field.
3. Click the "PLAY" button to convert the text to speech and play the generated audio.
4. Click the "EXIT" button to close the application.
5. Click the "RESET" button to clear the text entry field.

## Script Explanation

- **import libraries**: Import necessary libraries, including Tkinter for the GUI, gTTS for text-to-speech conversion, and playsound for playing audio.

- **Initialized window**: Set up the main window using Tkinter with specific dimensions, title, and background color.

- **heading**: Display the heading and a subheading in the GUI.

- **Enter Text label**: Display a label instructing the user to enter text.

- **text variable**: Create a Tkinter StringVar to store the text entered by the user.

- **Entry**: Provide an entry field for the user to input text.

- **define functions**: Define three functions:

  - `Text_to_speech()`: Retrieves the entered text, converts it to speech using gTTS, saves it as an audio file, and plays the audio using playsound.
  - `Exit()`: Closes the application.
  - `Reset()`: Resets the text entry field.

- **Buttons**: Create three buttons for "PLAY," "EXIT," and "RESET," associating each with its corresponding function.

- **Infinite loop**: Start the Tkinter main loop to run the program.

