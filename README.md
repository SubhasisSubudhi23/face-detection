Face Recognition Attendance System 

Hey! This is a project I put together to handle attendance automatically using Python and OpenCV. I've been diving deep into AI and Machine Learning, and I wanted to build something that actually solves a real-world problem—like replacing those old-fashioned manual sign-in sheets.

Why I built this
I wanted a system that could "see" and identify faces in real-time and then log them into a file with a timestamp. It's a lot more efficient than calling out names, and it was a great way for me to practice implementing Haar Cascades for object detection.

How it works
Detection: The system uses a webcam feed to scan for facial features.

Recognition: It compares what it sees against the pre-trained Haar Cascade models.

Logging: Once it finds a match, it sticks the name and time into an attendance log automatically.

Tech Stack
Python: My go-to for the backend logic.

OpenCV: Used this for all the computer vision and image processing.

Haar Cascades: The specific classifier I used to make the face detection fast and reliable.

Getting Started
If you want to run this locally, you'll need Python and the OpenCV library.

Install OpenCV: 


pip install opencv-python
Make sure your webcam is connected.


Run the script:


python face_detection.py


What's Next?
I'm looking into making the detection even more accurate in different lighting conditions. I'm also thinking about building a web dashboard to display the logs, similar to the work I'm doing on CampusConnect.
Feel free to reach out if you have any ideas or want to collaborate!
