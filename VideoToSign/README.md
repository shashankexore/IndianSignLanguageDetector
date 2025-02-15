# Indian Sign Language Detector

## About the Project
Indian Sign Language Detector is a machine learning-based project that translates hand gestures into corresponding letters and numbers. Using MediaPipe for hand tracking and a deep learning model for classification, it helps recognize Indian Sign Language (ISL) from real-time video input.

## Features
- Hand landmark detection using MediaPipe
- Gesture normalization and feature extraction
- Deep learning model for sign language recognition
- Real-time sign detection via webcam
- Dataset generation for training new models

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- TensorFlow/Keras
- MediaPipe
- NumPy & Pandas

Install dependencies using:
```sh
pip install opencv-python mediapipe tensorflow numpy pandas
```

### Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/shashankexore/IndianSignLanguageDetector.git
   ```
2. Navigate to the project directory:
   ```sh
   cd IndianSignLanguageDetector/VideoToSign
   ```
3. Ensure the trained model (`model.h5`) is present in the directory.

## Usage

### Dataset Generation
Run `dataset_keypoint_generation.py` to generate landmark-based training data:
```sh
python dataset_keypoint_generation.py
```

### Sign Detection
Run `isl_detection.py` for real-time ISL recognition using your webcam:
```sh
python isl_detection.py
```
The detected sign will be displayed on the screen and printed in the console.

## File Structure
- `dataset_keypoint_generation.py` - Generates keypoint-based dataset from images
- `isl_detection.py` - Detects hand gestures and predicts the corresponding ISL character
- `model.h5` - Pretrained deep learning model for classification
- `images/` - Directory containing image data for training
- `keypoint.csv` - CSV file storing hand landmark coordinates

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

## Credits
Created by Shashank Singh[@shashankexore](https://github.com/shashankexore) and Anushka Banerjee [@anushka369](https://github.com/anushka369).

