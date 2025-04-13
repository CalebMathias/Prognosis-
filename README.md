# Prognosis

Prognosis is an advanced AI-powered vision system that integrates cutting-edge technologies for real-time object detection, tracking, and analysis. It incorporates a range of features inspired by fields such as hyperdimensional computing, evolutionary algorithms, and consciousness field theories to provide a robust, adaptive, and intelligent vision framework.

---

## Features

- **Object Detection:** Uses the YOLOv8x model for high-accuracy object detection.
- **Object Tracking:** Integrates DeepSort for real-time tracking of multiple objects.
- **Text-to-Speech (TTS):** Converts insights into audible messages using `pyttsx3` for interactive feedback.
- **Hyperdimensional Memory:** Incorporates holographic memory for storing and recalling object states for contextual awareness.
- **Evolutionary Adaptation:** Dynamically adjusts parameters using evolutionary algorithms to optimize performance in real-time.
- **Anomaly Detection:** Identifies unusual patterns in the scene using a hyperdimensional consciousness field.
- **Collision Prediction:** Predicts potential collisions between objects with quantum-inspired noise modeling.

---

## How Prognosis Works

Prognosis operates as a real-time vision system that processes video input from a webcam or other video sources. It combines object detection, tracking, and state management to generate insights about the environment. Here's a breakdown of its functionality:

1. **Initialization**:  
   - Loads the YOLOv8x model for object detection.
   - Initializes the DeepSort tracker for object tracking.
   - Sets up a text-to-speech engine for auditory feedback.

2. **Object Detection**:  
   - Captures frames from a live video feed.
   - Detects objects in each frame using YOLO and classifies them into predefined categories (e.g., person, car, bicycle).

3. **Object Tracking**:  
   - Tracks detected objects across frames using DeepSort.
   - Maintains a unique ID for each object and updates its state (position, velocity, etc.) over time.

4. **Hyperdimensional Memory**:  
   - Encodes object states into hyperdimensional vectors.
   - Stores these vectors in a holographic memory for contextual awareness.
   - Recalls past states based on similarity to the current scene.

5. **Evolutionary Adaptation**:  
   - Periodically evaluates the performance of the system.
   - Dynamically adjusts parameters (e.g., noise multiplier, decay rates) to optimize tracking and prediction accuracy.

6. **Consciousness Field**:  
   - Maintains a multidimensional consciousness field that tracks object interactions and anomalies.
   - Detects hotspots of activity and alerts the user to significant events.

7. **Real-Time Feedback**:  
   - Provides spoken updates on detected objects, movements, and potential collisions.
   - Highlights anomalies, scene changes, and emerging patterns in the environment.

---

## Example Outputs

Here are some examples of what Prognosis can do in action:

### 1. **Object Detection and Tracking**
- Output:
  ```
  ID: 1 - person (walking) S:0.75 C:0.65
  ID: 2 - car (parked) S:0.85 C:0.55
  ```
- Spoken Feedback:
  - "A person is walking on the center."
  - "A car is parked on the left."

### 2. **Collision Prediction**
- Output:
  ```
  Potential collision between person and car in 2.5 seconds.
  ```
- Spoken Feedback:
  - "Potential collision between person and car in 2.5 seconds."

### 3. **Anomaly Detection**
- Output:
  ```
  Anomaly detected at (150, 200).
  ```
- Spoken Feedback:
  - "Anomaly detected at (150, 200)."

### 4. **Scene Summary**
- Output:
  ```
  Scene summary: 2 persons, 1 car.
  ```
- Spoken Feedback:
  - "Scene summary: 2 persons, 1 car."

### 5. **Hotspot Detection**
- Output:
  ```
  Consciousness hotspot at (300, 400).
  ```
- Spoken Feedback:
  - "Consciousness hotspot at (300, 400)."

---

## How to Use Prognosis

### Prerequisites
1. Install Python 3.9 or higher.
2. Install the required dependencies:
   ```bash
   pip install opencv-python torch numpy pyttsx3 ultralytics deep_sort_realtime scipy
   ```

### Running Prognosis
1. Clone the repository:
   ```bash
   git clone https://github.com/CalebMathias/Prognosis-.git
   cd Prognosis-
   ```
2. Run the program:
   ```bash
   python Prognosis.py
   ```
3. The system will initialize and start processing video input from your webcam.

### Stopping Prognosis
- Press `q` on the keyboard to terminate the program.

---

## Configuration Options

You can customize Prognosis by modifying the following parameters in the `Prognosis` class:

- **YOLO Model**: Change the YOLO model file (e.g., `yolov8n.pt`, `yolov8s.pt`) for different accuracy and speed trade-offs.
- **Tracker Settings**: Adjust the `max_age` and other parameters for the DeepSort tracker.
- **Speech Rate**: Modify the text-to-speech rate via `self.tts.setProperty("rate", <value>)`.
- **Evolutionary Parameters**: Change the initial parameter set in `self.population` to experiment with different evolutionary strategies.

---

## Troubleshooting

- **Webcam Not Detected**:
  - Ensure the webcam is connected and accessible.
  - Modify the `cv2.VideoCapture(0)` line to use a different video source if necessary.
- **Missing Dependencies**:
  - Verify that all required Python packages are installed.
- **Low FPS**:
  - Reduce the YOLO model size (e.g., use `yolov8n.pt` instead of `yolov8x.pt`).

---

Prognosis is an experimental AI framework that combines state-of-the-art vision technologies with innovative theories for advanced tracking, prediction, and anomaly detection. Try it out and explore the possibilities!
