# CV-hand-gesture-detector

# Hand Gesture Recognition using Computer Vision

## Overview
This project implements a Hand Gesture Recognition system using Computer Vision techniques with MediaPipe and OpenCV. It detects hand landmarks and classifies gestures based on finger positions.

---

## Features
- Detects hand using MediaPipe
- Identifies finger positions
- Classifies gestures:
  - FIST 
  - ONE 
  - TWO 
  - THREE
  - OPEN HAND 
- Works on multiple images

---

## Technologies Used
- Python
- OpenCV
- MediaPipe
- Google Colab

---

## How It Works
1. Image is uploaded by the user
2. MediaPipe detects 21 hand landmarks
3. Finger tips are compared with lower joints
4. Based on positions, fingers are classified as open/closed
5. Gesture is displayed on the image

---

## How to Run
1. Open the Colab Notebook
2. Run the setup cell
3. Upload a hand image
4. View detected gesture

---

## Limitations
- Thumb detection is not included to avoid inaccuracies
- Works best with clear hand images and good lighting

---

## Future Improvements
- Real-time webcam support
- Thumb gesture detection
- Gesture-based controls (volume, brightness)
- Deep learning-based gesture classification
