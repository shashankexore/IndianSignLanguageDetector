# Indian Sign Language Translator (AudioToSign)

## Overview

The Indian Sign Language Converter is an assistive tool designed to bridge the communication gap between the hearing-impaired community and others. It converts spoken words into sign language representations using images and GIFs.

## Features

- Real-time voice recognition using `speech_recognition`.
- Displays corresponding Indian Sign Language (ISL) signs in the form of images and GIFs.
- Supports a wide range of predefined phrases and alphabets.
- Simple graphical user interface using `easygui`.
- Interactive Tkinter-based sign display for recognized words.

## Prerequisites

Ensure you have the following dependencies installed:

```bash
pip install speechrecognition numpy matplotlib opencv-python easygui pillow
```

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run the main script:

```bash
python main1.py
```

## Usage

- On running the script, a GUI pops up with an option to start live voice recognition.
- Speak into the microphone.
- The program identifies words/phrases and displays corresponding ISL signs.
- Say "goodbye" to exit.

## To run the application.
1. Open the Downloads folder and then open the terminal.
2. From the terminal, run the *main* python file using the command **python main.py**.
3. The application interface appears on the screen.
4. Hit the record button to start taking speech as input.
5. Any speech recorded is then processed and respective outputs are shown accordingly.
6. To exit the application using speech, say *goodbye*.

## Algorithm
Audio to Sign Language Translator
1. Start
2. Getting the Speech
   1. Listen for 1 second and calibrate the energy threshold for ambient noise
levels.
   2. Listen the Speech using Microphone.
Now the energy threshold is already set to a good value, and we can
reliably catch speech right away.
3. Recognise the Speech.
4. Convert Speech to Text.
   1. Make the Text to lowercase for further manipulation.
5. Detected Text
   1. If “goodbye” then exit.
   2.Else if Detected Text in predefined Dictionary Words. Display
respective GIFs of the Phrase.
   3. Else Count the Letters of the Word/Phrase.
      1. Display the Visual of the phrase with some delay of Actions.
   4. Continue all the steps from Step 3, and continue till the Speech Ends.
6. If Error in Step 2, That is if no Speech Detected then display error message
“Could not listen”.

## File Structure

- `main1.py` - Core script for speech-to-sign conversion.
- `main2.py` - Alternative implementation with additional features.
- `ISL_Gifs/` - Folder containing GIF representations of ISL phrases.
- `letters/` - Folder containing images for alphabet representation.
- `signlang.png` - Image used in the GUI.

## Future Enhancements

- Expand vocabulary with additional ISL signs.
- Improve recognition accuracy.
- Add a text-to-sign translation feature.
- Develop a mobile application for broader accessibility.

## Contributing

Feel free to fork the repository, enhance features, and submit pull requests.

## License

Created by Shashank Singh[@shashankexore](https://github.com/shashankexore) and Anushka Banerjee [@anushka369](https://github.com/anushka369).
