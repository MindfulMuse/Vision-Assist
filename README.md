Vision Assist is an advanced assistive system designed to empower visually impaired individuals by enhancing their understanding of their surroundings. The system incorporates state-of-the-art technologies for object detection, distance measurement, and auditory feedback, offering a comprehensive and user-friendly solution.

*Features*

Object Detection: Identifies objects in real-time using a camera setup.

Distance and Direction Measurement: Estimates the distance and directional location of objects relative to the user.

Auditory Feedback: Provides real-time voice feedback to notify users about detected objects.

Face Recognition: Recognizes and identifies familiar faces, even in low-light conditions, using the ex-darkset.

Vertical Direction Detection (Future Upgrade): Additional servo motor to detect upward or downward object movements.

LiDAR Integration (Future Upgrade): Enhances distance estimation and increases the detection range.

Technologies Used

Hardware:

Raspberry Pi 3

Ultrasonic Sensor

Servo Motor

Pi Camera

Software:

Python

OpenCV for object detection

TensorFlow/Keras for face recognition

ex-darkset for low-light performance optimization

Audio feedback library for voice alerts

How It Works

Object Detection and Distance Measurement:

A camera captures real-time video, and an ultrasonic sensor measures the distance of objects.

A servo motor adjusts the sensor's orientation to determine the object's direction.

Face Recognition:

Pre-trained models are used to identify faces.

The system can differentiate between known and unknown individuals.

Auditory Feedback:

The user receives information like "Car detected at 20 cm to the left" through voice output.

Setup Instructions

Hardware Setup

Connect the Pi Camera to the Raspberry Pi.

Attach the ultrasonic sensor and servo motor to the Raspberry Pi GPIO pins.

Assemble the components securely for portability and ease of use.

Software Setup

Clone the repository:

git clone https://github.com/MindfulMuse/Vision-Assist.git
cd vision-assist
