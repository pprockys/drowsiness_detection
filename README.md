# drowsiness_detection
Applications

This can be used by riders who tend to drive for a longer period of time that may lead to accidents
Code Requirements

The example code is in Python (version 2.7 or higher will work).
Dependencies

    import cv2
    import immutils
    import dlib
    import scipy

Description

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.
Algorithm

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.


