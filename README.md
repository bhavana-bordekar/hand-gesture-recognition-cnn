#  Hand Gesture Recognition — CNN

##  Overview
Deep learning project using Convolutional Neural
Networks (CNN) to recognise 10 different hand
gestures from images with high accuracy.

##  Results
- **Test Accuracy: XX%** ← put your score here!
- 20,000 images trained
- 10 gesture classes
- 10 training epochs

##  Gesture Classes
| Class | Gesture |
|-------|---------|
| 0 | Palm |
| 1 | L shape |
| 2 | Fist |
| 3 | Fist moved |
| 4 | Thumb up |
| 5 | Index finger |
| 6 | OK sign |
| 7 | Palm moved |
| 8 | C shape |
| 9 | Down |

##  CNN Architecture
nput (64x64 greyscale)
→ Conv2D(32) + MaxPooling
→ Conv2D(64) + MaxPooling
→ Conv2D(128) + MaxPooling
→ Flatten + Dropout(0.5)
→ Dense(128)
→ Output(10 classes)

##  Training Results
![Training Results](training_results.png)
![Sample Gestures](sample_gestures.png)

##  Tools Used
- Python 3.11
- TensorFlow 2.12
- Keras
- NumPy
- OpenCV
- Matplotlib
- Pillow

##  Dataset
- Source: LeapGestRecog (Kaggle)
- Images: 20,000
- Classes: 10
- Image size: 64x64 greyscale

##  How to Run
1. Clone this repository
2. Install requirements:
pip install tensorflow-macos numpy matplotlib
scikit-learn opencv-python Pillow
3. Download dataset from Kaggle:
kaggle.com/datasets/gti-upm/leapgestrecog
4. Run notebooks in order:
- check_setup.ipynb
- load_data.ipynb

##  About
Junior Data Analyst → AI Engineer
Python | SQL | TensorFlow | Tableau
Based in Braunschweig, Germany 
github.com/bhavana-bordekar
