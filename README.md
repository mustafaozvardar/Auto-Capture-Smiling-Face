# 😊 Auto-Selfie for Smiling Face 📸

This project is a simple Python application designed to automatically take a selfie when a smile is detected on your face. Using `OpenCV` and `Mediapipe`, it tracks facial landmarks and captures a selfie when a smile is detected.

## 🎯 About the Project

- **Face Tracking**: Facial landmarks are tracked using `Mediapipe`.
- **Smile Detection**: The distance between the corners of the mouth is calculated. If this distance exceeds a certain threshold, it is considered a smile.
- **Auto-Selfie**: When a smile is detected, the application captures a selfie and saves it as `selfie.png`.
- **Sound Feedback**: A sound effect (`success.wav`) is played when a smile is detected.

## 🚀 How It Works

**1. Clone the repository:**
   ```bash
   git clone https://github.com/username/auto-selfie.git
   cd auto-selfie
   ```
**2. Install the required dependencies:**
   ```bash
   pip install opencv-python
   pip install mediapipe
   pip install winsound
   ```
**3. Add the "success.wav" sound file to the project directory.**

**4. Run the application:**
   ```bash
  python auto_selfie.py
  ```

## 🛠 Requirements
- Python 3.x
- OpenCV
- Mediapipe
- Winsound
- Windows (as the winsound module is used)

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.
