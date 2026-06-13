# Emotion-Based Music Recommendation System
It is a machine learning project that detects a user's emotion in real time using a webcam and recommends songs based on the detected mood. The system further personalizes recommendations by allowing users to choose their preferred language and singer, creating a customized and engaging music experience.

## Project Description
It combines computer vision and machine learning to understand human emotions through facial expressions. Once the emotion is identified, the system interacts with the user to collect music preferences and then suggests suitable songs that match both the user's mood and choice.

## Objectives
- Detect user emotions using facial expressions
- Classify user expressions using a trained deep learning model
- Take user input for preferred language and singer
- Recommend songs based on emotional state
- Provide a personalized music recommendation experience

## Emotions Recognized
- Happy  
- Sad  
- Angry  
- Neutral  
- Surprise
- 

## Technologies Used
- **Programming Language:** Python  
- **Machine Learning:** Deep Learning (Dense Neural Network using Keras/TensorFlow)
- **Computer Vision:** OpenCV/ Mediapipe Holistic  
- **Libraries:** NumPy, TensorFlow, Keras
- **Hardware:** Webcam  

## Workflow
1. Webcam captures the user's facial expression  
2. Face detection and preprocessing are performed  
3. Emotion is classified using a trained ML model  
4. User selects preferred language and singer  
5. System recommends songs based on detected mood  
6. Results are displayed to the user  

## Dataset
- Custom dataset collected using a webcam and MediaPipe Holistic.
- Facial, hand and pose landmark coordinates were stored as NumPy files.
- Samples were labeled into six classes.
- Landmark coordinates were normalized relative to reference points before model training.

## Features
- Real-time emotion detection using webcam
- Personalized music recommendations
- Interactive user input
- Emotion-aware recommendation system
- Simple and user-friendly interface

## Future Scope
- Integration with music streaming platforms
- Mobile application development
- Improved emotion detection accuracy
- Voice-based emotion recognition
- Real-time playlist generation

## How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/PriyaChandra7/Emotion-Based-Music-Recommendation-System-.git
   cd Emotion-Based-Music-Recommendation-System-
2. Install required libraries
pip install -r requirements.txt
3. Run the project
python data_inference.py
4. Allow webcam access and follow on-screen instructions

Author
Priya Chandra
B.Tech CSE(AI & ML)

Acknowledgement
This project was developed for academic and learning purposes to explore emotion recognition and personalized music recommendation using machine learning.
