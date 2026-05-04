# Task 04 — Hand Gesture Recognition (CNN)

## Objective
Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image data, enabling intuitive human-computer interaction and gesture-based control systems.

## Dataset
LeapGestRecog Dataset from Kaggle

## Libraries Used
- NumPy, OpenCV (cv2)
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn

## Model Results
| Epoch | Train Accuracy | Val Accuracy |
|-------|---------------|-------------|
| 1     | 84.87%        | 99.50%      |
| 2     | 97.81%        | 99.87%      |
| 3     | 98.59%        | 99.94%      |

## Preprocessing
- Image resizing to 64x64
- RGB color images (no grayscale)
- Pixel normalization (divided by 255)
- Label encoding + One-Hot encoding

## Features Used
- Raw RGB pixel values (64x64x3)
- 10 gesture classes: palm, l, fist, fist_moved, thumb, index, ok, palm_moved, c, down
- Max 200 images per class (20,000 total images)