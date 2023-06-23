# jweb-hands-landmarker

A self contained example demonstrating how to use MediaPipe HandLandmarker with Max's `jweb` connected to either a live webcamera stream or using still images.

![Max example patcher](jweb-hands-landmarker.gif)

## Features

The hand landmark model bundle detects the keypoint localization of 21 hand-knuckle coordinates within the detected hand regions. The model was trained on approximately 30K real-world images, as well as several rendered synthetic hand models imposed over various backgrounds.

![Handlandmarks diagram](hand-landmarks.png)

## Resources

This example is inspired by [an example by Rob Ramirez](https://github.com/robtherich/jweb-mediapipe), which is in turn inspired by [MediaPipe in JavaScript](https://github.com/LintangWisesa/MediaPipe-in-JavaScript). 

