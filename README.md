# Hand Gesture Recognition
For my hand gesture recognition project, I will use Python 3 for coding and integration. TensorFlow and Keras will train the recognition model, while OpenCV will capture and process hand gestrues. PySerial will connect Python to the Arduino Mega 2560, programmed in the Arduino IDE, to control hardware actions based on recognition results.

Project Steps:

Train the Facial Recognition Model

- Went to Teachable Machine at the following link: https://teachablemachine.withgoogle.com/train
- Created a model that differentiates between images containing a thumbs up and images with waving.
- Exported the completed model using the Keras format.

Upload the Arduino Code

-Launched the Arduino IDE and uploaded the provided code file.

-This code instructs the Arduino to turn the LED on whenever it receives input indicating that a hand gesture has been detected.

Configure the Python–Arduino Connection

-Opened Visual Studio Code and ran the included Python script.

-The Python script loads the Keras model and the labels, then sends the proper signal to the Arduino when the webcam identifies a hand gesture.

System Testing

-Closed the Arduino IDE to free the COM port.

-Started the Python script in Visual Studio Code.

-The setup is functioning properly if the camera detects waving and the LED switches on.

Tools and Components Used:

-Python 3

-TensorFlow

-Keras

-OpenCV

-PySerial

-Arduino IDE

-Arduino Mega 2560

Video Demonstration:
