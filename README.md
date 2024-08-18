# Face-recognition-cv2
Face Recognition with Python



This project demonstrates a real-time face recognition system using Python. The system captures video from a webcam, detects faces in the video feed, and matches them against a set of known faces using the face_recognition library. When a match is found, the system displays the name of the recognized face on the video feed.

Features
Real-Time Face Recognition: Detects and recognizes faces from the webcam feed in real-time.
Support for Multiple Known Faces: Can handle and recognize multiple faces based on images stored in a specified directory.
Video Display: Displays the video feed with bounding boxes and names of recognized faces.
Frame Processing Optimization: Processes every other frame to optimize performance and reduce processing load.
Requirements
Python 3.x
face_recognition library
opencv-python library
numpy library
Installation
To get started with this project, you need to install the required Python packages. You can do this using pip:

bash
Copy code






pip install face_recognition opencv-python numpy





Additionally, you must have CMake installed on your system to build some dependencies. You can download it from cmake.org.

Usage
Prepare Face Images:

Place the images of known faces in a directory named face_images. Each image should be in .jpg format.
Run the Script:

Execute the face_recognition.py script to start the face recognition system.
bash
Copy code
python face_recognition.py
Quit the Application:

Press q on the keyboard to exit the application and close the video feed.
How It Works
Loading Images: Loads sample face images from the face_images directory and learns how to recognize each face.
Video Capture: Captures video from the default webcam.
Face Detection: Detects faces in the video feed, resizes the frame for faster processing, and converts the image color format.
Face Recognition: Compares detected face encodings with known face encodings to identify recognized faces.
Display Results: Draws bounding boxes and labels around recognized faces in the video feed.
Contributing
Contributions to improve the project are welcome. Please fork the repository and submit a pull request with your changes.
