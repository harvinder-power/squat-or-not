# Squat or Not
Squat or Not uses transfer learning applied in realtime webcam input to determine whether a pose is a squat, or not.

# Methods
The model was trained using samples of a person standing with body in full view of the camera, on top of a MobileNet model. 

# Implementation
The model is implemented using Tensorflow.js, which enables local classification rather than sending data to a server.

Live demo: https://harvinder.me/squatornot

# Improvements
- Enable counter feature
- Improved UI
- Mobile functionality (appears to have issues with phones, but tablets work)
