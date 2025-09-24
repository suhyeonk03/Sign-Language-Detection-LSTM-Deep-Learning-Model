# Phase 1: Sign-Language-Detection-LSTM-Deep-Learning-Model

## Project Overview
An action recognition deep learning model built in Jupyter notebook using Python
<br>
**Detailed steps and code are in the Jupyter notebook named Sign_Lang_Recognition.ipynb**
<br>

## Used Python Libraries
- os
- time
- tensorflow
- keras
- opencv-python
- scikit-learn
- matplotlib
- mediapipe
- numpy
- cv2

# Phase 2: Sign Language Translator can be implemented in assistive robots

## Project Overview:

## Next steps
Combination of Action Recognition and Arduino:
- Translator robot
- Sign language to normal language (display on LCD), or vice versa
- Language (by input buttons, e.g., first button: thanks) to sign language (shown by image popup)
- Sign Language through a webcam to Language through an LCD 
- Very limited phrases, small number of push-buttons available-->less classes/train, can be improved by getting input by typing, more memory, webcam can be replaced with a camera on the robot, LCD to screen on the robot

## Key components: Arduino, LCD, Push-buttons 
Find a way to integrate a Python program with an Arduino
(run the model on Jupyter, then transfer the output to Arduino so that Arduino can perform hardware tasks)
(libraries: pySerial(allows python to communicate with the Arduino via USB serial port))

## Constraints
- Memory constraint: The Arduino board has very limited RAM and flash storage, which is not sufficient to handle TensorFlow, virtual environments, and similar tasks. Instead, a Jupyter Notebook performs these tasks, and the Arduino receives the prediction result to execute hardware operations

## Possible further improvements
