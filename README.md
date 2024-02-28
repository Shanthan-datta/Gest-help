Hand Gesture Emergency Notification System
This project is a real-time hand gesture recognition system using MediaPipe and TensorFlow. It detects hand gestures from a webcam feed and triggers an emergency notification email when the gesture "help" is recognized.

Features
Detects hand gestures using the MediaPipe library.
Recognizes the "help" gesture to send an emergency email.
Uses a pre-trained deep learning model for gesture recognition.
Sends email notifications via Gmail's SMTP server.
Real-time visualization of hand gestures on the webcam feed.
Prerequisites
Python 3.11.3
OpenCV
NumPy
MediaPipe
TensorFlow
Gmail account for sending email notifications
Installation
Clone the repository:
git clone https://github.com/geethikaakkineni/hand-gesture-emergency-notification.git
Install the required packages:
pip install -r requirement.txt
Usage
Run the hand_gesture_detection.py file:
python hand_gesture_detection.py
Ensure your webcam is connected and functioning properly.

Show the "help" gesture to trigger the emergency notification.

Configuration
Modify the smtp_username and smtp_password variables in main.py with your Gmail credentials.
Update the sender_email and recipient_email variables with the sender and recipient email addresses, respectively.
Customization
You can customize the gestures by training your own gesture recognition model and updating the model variable in main.py with your model.
Adjust the confidence threshold for gesture detection by modifying the min_detection_confidence variable in main.py.
You can also customize the code to recognize a specific number of hands.
Issues and Contributions
If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

