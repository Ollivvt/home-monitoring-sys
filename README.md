# Home Monitoring Systems
### Operation
#### Load Model for Object Detection

Import the pre-trained TensorFlow Lite object detection model and load the Interpreter for subsequent model scheduling and operations.

#### Specify Monitoring for Specific Objects

Monitor specific objects dynamically by specifying model labels, displaying various dynamic alert information on the screen.

#### Object Appears in No-Entry Zone

Define the no-entry zone by using position coordinate information, comparing the object's coordinates based on the relative screen display ratio.

#### Send Cloud Messages to Devices

Activate the IFTTT cloud service mechanism to send LINE message data when an alarm event occurs, based on the program conditions.
