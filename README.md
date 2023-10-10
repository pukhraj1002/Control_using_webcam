# Control_using_webcam
The project "Webcam-based Volume and Brightness Control System" utilizes Python programming to interact with a computer's webcam, enabling users to control the system's volume and brightness levels through hand gestures and facial expressions. The system employs computer vision techniques to analyze real-time video feed from the webcam, detecting and interpreting specific hand gestures and facial expressions. Based on the detected gestures and expressions, the system adjusts the volume and brightness accordingly to enhance user convenience and accessibility. The project integrates webcam interfacing, gesture recognition, and system control, providing an interactive and intuitive way to manage essential system settings.
Aim and objective of research work include- 
• For most laptops, touchpad is not the most comfortable and convenient tool. 
• Main objective of pre-processing is to represent the data in such a way that it can be easily interpreted and processed by the system. 
• Reduce cost of hardware .

Existing System 
A computer mouse is an input device that helps you point and interact with what you’re pointing at. There are many types of mouse in the current trend. There are mechanical mouse consisting of a single rubber ball that can rotate in any direction and the movement of the pointer is determined by the movement of the rubber ball.

Proposed System 
The proposed system can be used to fix real-world problems, such as situations where there is no space to use a physical mouse, and also for people who have hand problems and are unable to navigate physical mouse controls.

Methodology 
The proposed system is combination of three subsections which are clubbed together with GUI (graphical user interface). The three subsections are virtual mouse, volume controller and brightness controller. • GUI: Graphical user interface (GUI), a computer program that enables a person to communicate with a computer through the use of symbols, visual metaphors, and pointing devices [12]. A graphical user interface is an application with buttons, windows, and many other widgets that users can use to interact with your application. A good example is a web browser. It has buttons, tabs and a main window where all the content is loaded [13]. Many GUI libraries are available for Python. The most popular are: Tkinter, Kivy, PyQt, WxPython, Libavg, Pyforms, Wax Python GUI, etc. We used Tkinter in our system.


PROJECT PROTOTYPE
Volume controller 
Building a volume controller with OpenCV can be done in just 3 easy steps:
 • Step 1. Detect hand signals
 • Step 2. Calculate the distance between the tip of the thumb and the tip of the index finger. 
• Step 3. Map the distance between the tip of the thumb and the tip of the index finger with the volume range. In my case, the distance between the tip of the thumb and the tip of the index finger is from 15mm to 220mm and the volume range is -63.5dB to 0.0dB.

Brightness controller 
The method is almost the same as the volume control. First detect the landmarks of the hand and calculate the distance between the tip of the thumb and the tip of the index finger, then map the distance between the tip of the thumb and the tip of the index finger with the luminance range. In this case, the distance between the tip of the thumb and the tip of the index finger is 15mm to 220mm, and the minimum distance between the tip of the thumb and the tip of the index finger is 15mm and maximum distance is 220mm. 
