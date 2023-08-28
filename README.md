
# Hand Gesture Recognition and Classification


## Description

The Hand Gesture Recognition and Classification project focuses on real-time recognition of hand gestures and translating them into text labels using computer vision techniques. This repository contains the source code and resources for the Hand Gesture Recognition and Classification application.

## Features

- Real-time hand gesture recognition and classification
- Translation of recognized gestures to text labels
- Text-to-speech functionality for announcing recognized gestures

## Installation

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/rishwanthvallala/hand-gesture-recognition.git
   ```

2. Navigate to the project directory:
   ```sh
   cd hand-gesture-recognition
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the gesture recognition and classification application:
   ```sh
   python gesture_classification.py
   ```

2. Perform hand gestures in front of the camera and observe the recognized text labels and spoken announcements.

## Components

### Gesture Data Collection
The `gesture_data_collection.py` script captures hand gestures and creates white canvas images with resized hand gestures. These images are saved in the "Data" folder for further use.

### Gesture Classification
The `gesture_classification.py` script utilizes a pre-trained gesture classification model to recognize hand gestures from the captured images. The recognized gestures are then translated into text labels and announced using text-to-speech.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:
   ```
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:
   ```
   git commit -m "Add your commit message here"
   ```

4. Push your changes to your fork:
   ```
   git push origin feature/your-feature-name
   ```

5. Open a pull request on the original repository.



## Contact

For questions or inquiries, please contact [vallalarishwanth@gmail.com].


