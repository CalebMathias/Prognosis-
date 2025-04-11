# Prognosis

Prognosis is an advanced AI-based vision system designed to perform real-time object detection, tracking, and contextual analysis. It combines cutting-edge technologies such as hyperdimensional computing, evolutionary algorithms, and emotional valence mapping to create a highly intelligent and adaptive system. Prognosis features a unique approach to perception and decision-making, inspired by theories of consciousness, neuroscience, and machine learning.

## How Prognosis Works

Prognosis integrates multiple AI components to create a sophisticated vision and decision-making system:

1. **Object Detection**:  
   Prognosis uses the YOLOv8x model for real-time object detection. It identifies various objects in the video stream, such as people, vehicles, and more, and assigns them meaningful labels.

2. **Object Tracking**:  
   The system leverages the DeepSort tracker to maintain consistent tracking of objects over time, even in a dynamic scene. It calculates the movement, speed, and direction of objects.

3. **Emotional Valence Mapping**:  
   Inspired by Damasio's emotional valence theory, Prognosis assigns emotional weights to objects based on proximity, movement, and speed. This allows it to prioritize objects that may require attention, such as fast-moving cars or nearby pedestrians.

4. **Hyperdimensional Computing**:  
   Prognosis encodes object states and tracks into high-dimensional vectors, simulating a holographic memory. These vectors enable the system to recall past states and detect patterns in complex contexts.

5. **Evolutionary Adaptation**:  
   Using Darwinian principles, Prognosis evaluates and evolves its internal parameters over time to improve its predictive capabilities. It continuously tests different configurations, retaining the most effective ones.

6. **Quantum Prediction**:  
   The system predicts future object states using probabilistic scenarios, enabling it to forecast potential collisions, overlaps, or significant events.

7. **Text-to-Speech (TTS)**:  
   Prognosis provides real-time audio feedback using a text-to-speech engine. It generates alerts and summaries of the scene, making it highly interactive and user-friendly.

8. **Hyperdimensional Consciousness Field**:  
   Prognosis simulates a "consciousness field" by maintaining a multi-dimensional grid of dynamic values. This field helps it identify hotspots of activity, convergence points, and emergent patterns in the environment.

## Example Outputs of Prognosis in Action

Here are some examples of what Prognosis might output during operation:

### Real-Time Alerts:
- **Scenario 1 (Fast Movement)**:  
   "Alert: Fast-moving car driving on the left."
- **Scenario 2 (Collision Prediction)**:  
   "Predicted convergence between a person and a bicycle with 85% probability in 1 second."
- **Scenario 3 (Consciousness Hotspot)**:  
   "Hyperdimensional consciousness hotspot detected at coordinates (120, 240)."

### Scene Summaries:
- After 150 frames, the system provides a summary of the scene:  
   "Scene summary: 3 people, 2 cars, 1 bicycle."

### Object Localization:
- "A person has appeared on the center. A car is parked on the right."

## How to Use Prognosis

### Requirements
To use Prognosis, ensure you have the following installed:
- Python 3.8 or higher
- Libraries: OpenCV, PyTorch, NumPy, SciPy, pyttsx3, and ultralytics (YOLO)
- A webcam or video input device

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/CalebMathias/Prognosis-.git
   cd Prognosis-
   ```

2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure that the YOLOv8x model (`yolov8x.pt`) is available in the working directory.

### Running Prognosis
1. Launch Prognosis:
   ```bash
   python Prognosis
   ```

2. The system will activate the webcam and start detecting and tracking objects in real time. A window will display the video feed with bounding boxes, labels, and actions.

3. Use the following key to control the system:
   - Press `q` to quit the application.

### Customization
- **Class Labels**:  
   Modify the `self.class_labels` dictionary in the `Prognosis` class to add or change object labels.
- **Action Mapping**:  
   Adjust the `self.action_map` dictionary to define new actions for detected objects.
- **Evolutionary Parameters**:  
   Change the `self.population` list to experiment with different noise multiplier values.

## Future Enhancements
Prognosis is designed to be extensible. Future updates may include:
- Integration with external APIs for advanced analytics
- Support for additional object detection models
- Enhanced visualization tools for the hyperdimensional consciousness field

---

Prognosis combines the latest advancements in AI, neuroscience, and robotics to create an intelligent system capable of understanding its environment in real time. Whether used for surveillance, autonomous systems, or educational purposes, Prognosis offers a glimpse into the future of machine intelligence.
