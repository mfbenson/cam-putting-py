# Prototype for Webcam based putting simulation for GSPRO utilizing the R10 connect package:

Calculation includes BallSpeed in MPH and HLA of the putt. 

Setup:

- Position Webcam on the side an above the putting start area across from you (currently for a right handed player) - see video for example
- Position the Ball (yellow or white should work) on a dark green surface - In my test the area visible to the webcam was about 60 centimeters
- Once the Ball has a red circle around it is detected and you can start a putt
- The putt needs to cross in between the rectangle and needs to leave on the other side
- If a shot is detected it is send to http://localhost:8888/ where my extension of the garmin connect app (https://github.com/alleexx/gspro-garmin-connect-v2) is receiving the shot and passing it to GSPRO

You can install the necessary packages by running pip install with the requirements file - some mentioned packages might not be necessary to run it as I did not clean it up yet

"pip install -r requirements.txt"

Run "python ball_tracking.py" to run the app

This is early development so happy about feedback but do not base your SGT career on it

Here is a short video demonstration of the v0 1 prototype

https://youtu.be/ZgcH25WkCWQ