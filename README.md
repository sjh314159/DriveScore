# DriveScore
Application to explore self-organizing maps in the context of ranking manual Sphero driving

# Instructions

# Overview

Drive Score will rank your driving of a Sphero using machine learning applied to sensor values. Each time you record and drive the Sphero, the sensor values are scanned for features such as average speed or number of turns. The feature data is fed into a self-organizing map (SOM) type of neural network that will categorize your driving as beginner, intermediate, or expert.

# Permissions

This application requires permissions for location and file access. When you start recording, the sensor data is used to rank your driving and to update the learned weights. The number of recorded driving runs and the learned weights for the current shape are saved to a file.

# Sphero Connection

1. Wake up Sphero by tapping on it

2. Click the Connect slider at the top of the application window

3. Wait for the Sphero connection

4. Press Start Set Heading

5. Pull joystick to the edge

6. Align the blue tail light to your tablet

7. Press Stop Set Heading

# Note

If the tablet goes to sleep while the Sphero is connected, the Sphero may have difficulty resetting the Bluetooth connection. In this case reset the Sphero by returning it to the charging station and having it go to sleep. Wake up the Sphero and try the connection again.

# Recording, Ranking, and Learning

When you start recording, the sensor data will be recorded and then used for ranking your driving and for learning by using the calculated features to update the learned weights.

Start Recording will record sensor data

Stop Recording will stop recording, rank the driving, and  then update and save the learned weights

Start / Stop Auto Drive will start or stop automatic driving of the shape

Shape Selection radio buttons will switch to the shape and the learned weights for that shape

Speed Slider will adjust the maximum speed of the joystick

Flip Joystick will change the joystick from left-handed to right-handed

Clear Weights will reset the learned weights to default values and save them. Previous learned weights will be lost.

# File Saving

The weights are automatically saved after each recorded driving run. The weights are saved in the main file storage area and can be accessed by using the My Files application. The files are stored in a folder called Drive Score in files starting with DriveScoreWeights0.txt for the square to DriveScoreWeights3.txt for the figure eight.
