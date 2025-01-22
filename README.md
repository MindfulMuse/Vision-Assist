
---

# Vision Assist

Vision Assist is an assistive system designed to empower visually impaired individuals by providing auditory feedback about their surroundings. This system combines object detection, distance measurement, and face recognition, offering enhanced environmental awareness and safety.

## Features

- **Object Detection**: Identifies objects in the surroundings.
- **Distance and Direction Estimation**: Calculates the distance and direction of objects using an ultrasonic sensor and servo motor.
- **Face Recognition**: Recognizes known individuals, trained on the Ex-Darkset for better performance in low-light conditions.
- **Auditory Feedback**: Provides real-time audio notifications about detected objects and their locations.
- **Low-Light Optimization**: Performs effectively in low-light environments.

## Future Enhancements

- Add an additional servo motor for vertical direction detection (e.g., up/down) to identify falling objects.
- Integrate advanced equipment like LiDAR to improve distance estimation and detect objects at greater distances.

## Technologies Used

- **Programming Languages**: Python
- **Hardware**: Raspberry Pi 3, Ultrasonic Sensor, Servo Motor, Pi Camera
- **Libraries**:
  - OpenCV
  - TensorFlow/Keras (for object detection)
- **Datasets**:
  - Ex-Darkset (for face recognition)

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vision-assist.git
   cd vision-assist
   ```

2. Run the main script:
   ```bash
   python vision.py
   ```

## Usage

1. Power on the Raspberry Pi and ensure all components are connected properly.
2. Start the application to begin detecting objects and providing auditory feedback.
3. Place known individuals' face data in the `faces` folder for recognition.
4. Adjust the servo motor for directional scanning.






Feel free to modify the content to include any additional details specific to your project. Let me know if you'd like to adjust any sections or add more details!

