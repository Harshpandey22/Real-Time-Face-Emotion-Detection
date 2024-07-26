
# Face Emotion Detection




#### This project implements a Face Emotion Detection system that utilizes deep learning to identify emotions from facial expressions. The application uses a Convolutional Neural Network (CNN) model with Keras and TensorFlow to classify emotions in real-time through a webcam or from uploaded images. Built with Streamlit, OpenCV, and Streamlit WebRTC, the application offers a modern and interactive user interface.
## Features

 - Live Emotion Detection: Detect emotions from your webcam feed in real-time.
 - Image Emotion Detection: Upload and analyze emotions in static images.
 - Real-time Feedback: View detected emotions and emotion distribution instantly.
 - User-Friendly Interface: Modern UI with Lottie animations and clear instructions.

## Installation

To set up the project on your local machine:

### Clone the repository:
- git clone https://github.com/your-username/face-emotion-detection.git
- cd face-emotion-detection

### Set up a virtual environment:
- python -m venv venv
- source venv/bin/activate (On Windows use`venv\Scripts\activate)

### Install required dependencies:
Ensure you have a requirements.txt file in the repository with all necessary packages. If not, create one using:
- pip freeze > requirements.txt

### Then install dependencies:
- pip install -r requirements.txt

### Download the pre-trained model and weights:
Download model_78.h5 and model_weights_78.h5 from the project directory.

### Run the application:
- streamlit run main_app.py
## Deployement
The application is deployed on Streamlit Sharing. You can access the live version of the app via the following link:
- https://real-time-face-emotion-by-harsh.streamlit.app


