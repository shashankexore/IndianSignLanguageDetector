# Indian Sign Language Converter (AudioToSign)

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
