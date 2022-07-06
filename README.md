# Security-cam-using-RPI4

Human face detection is a vital component of security and surveillance. This have multiple applications in our day- to-day life like face detection for passport verification, id proofs, find the suspect, etc. 
Here in this project, we detect the human faces from pictures taken per second using a pi camera module or a phone camera and a raspberry pi 4. The project is done with the use of Robotic Operating System Noetic Ninjemys version which is the latest version. Publisher and subscriber are used to state whether a human face is detected or not. The detected human faces are cropped and saved in one of the folders.

DESIGN
Hardware needed:
 - Raspberry Pi
 - Pi Camera Module/ Phone camera
 
Software information:
 - Ubuntu Mate 20.04 - OS
 - Noetic Ninjemys - ROS
Here, we only need an RPi4 And Pi camera module or a phone camera with OpenCV installed on your Raspberry Pi.
Step-1: Open the camera and capture images.
Step-2: Search for human faces and apply box over it if detected.
Step-3: Crop the image and save it in a folder.
Step-4: Print the right message in publisher as well as in subscriber.

