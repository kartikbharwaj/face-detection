OpenCV Face Recognition
This OpenCV application enables real-time face detection and recognition using a webcam.

Prerequisites: Ensure you have the following dependencies installed:

Python
opencv-python
opencv-contrib-python
datetime
NumPy
Dataset Creation:

Open create_data.py.
Change the path of "haar_file" and "datasets" below to the location where these files are on your machine
Change the "name" variable to the name of the person whose face you want to store. Run create_data.py and follow on-screen instructions. Ensure good lighting and multiple face angles for better results. Face Recognition
Run face_detection.py. Look into the camera in the same position as during dataset creation. The application will detect and recognize your face in real-time.
Tips:

Create multiple sub-datasets with different lighting, angles, etc., to increase recognition accuracy.

Ensure your face recognition environment matches the conditions during dataset creation.

Adjust the number of pictures per name in create_data.py for better recognition.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Python
100.0%
Footer
©
