# ✌️ V-Shape Hand Gesture Image Capture (JavaScript + MediaPipe)

This JavaScript project captures an image using your webcam when a **V-shape (✌️) hand gesture** is detected. The detection is powered by [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html), running in real-time in the browser.

## 🚀 Features

- ✋ Detects hand landmarks in real-time using MediaPipe
- ✌️ Recognizes a V-sign gesture (index + middle finger up)
- 📸 Automatically captures and saves a frame when the gesture is detected, with a download button for the image.
- 💻 Runs directly in the browser (no backend required)

## 📊 Additional Features

- **Selfie Counter**: Displays the number of selfies taken.
- **Click Effect**: Visual effect when a selfie is captured.

## 🛠️ Technologies Used

- **MediaPipe Hands** – For real-time hand landmark detection
- **JavaScript** – Core logic for gesture detection
- **HTML/CSS** – For webcam UI and layout
- **Canvas API** – For drawing and capturing frames


## 🧠 How It Works

1. Loads the user's webcam
2. MediaPipe detects and tracks hand landmarks.
3. The script identifies the "V-shape" gesture by checking the angles or relative positions of fingers:
   - Index and middle fingers should be extended.
   - Ring, pinky, and thumb should be down or closer together.
4. When the gesture is confirmed:
   - A frame is drawn onto a `<canvas>` and a download button is shown.
   - The image is saved or downloaded as a `.png`.

## 📦 Setup & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anujkumar2001/hand-motion-image-capture.git
   cd hand-motion-image-capture
