# Raspberry Pi Security Camera www.instructables.com/Raspberry-Pi-Security-Camera-1/


Project Statement – The project aims to create a security camera system using a Raspberry Pi. The user should be able to manually change the camera settings and take photos and videos manually. 


Ideation and Planning: 

   • First stage is identifying the components that are needed for the project. Thehe  components thar are required are the Raspberry Pi, the  PIR sensor, the camera, and the interface.
   • Part of the pipeline to break:


|Part of the Pipeline | Feasibility | Advantages | Disadvantages |
| --- | --- | --- | --- |
| Raspberry Pi | Very Difficult, unless experienced programmer.|It is a computer, and so is versatile. |It is very expensive and cannot be mass produced cheaply.|
| PIR Sensor | It is built by the manufacturer, so it can’t be modified.|It detects motion. It is very convenient to be a ready-made sensor. They are also small inexpensive and low power.| It does not tell the distance or count many peaple or objects there are.|
Camera 
Difficult to improve.
It can capture images and videos.
The quality of video can vary and it is subject to lighting conditions. 
Software interface
It is rather difficult to improve the software interface, but new libraries can be found that improve the performance.
There are a large number of pre-built python libriaries that can be used.
There might be security issues.



  • Choosing the pipeline -
	From the above table it seems that the major areas of improvement can be done 	
  software interface and in changing the motion sensor. The motion sensor that is 	
  used for this project is the PIR sensor. The PIR sensor uses IR waves to detect 
	objects. One of the disadvatanges of this type of sensor is that it cannot gauge 	
	distance or count how many people are there. However, this sensor is in
	inexpensive and has low power consumption. In case that cost is less important 
	than additional functionality, other types of sensors such as RADAR based 	sensors can be used.
	The software interface is the major area where improvements can be made. The      
	project uses the built-in libraries to record the video and adjust the camera    
	settings. However, the biggest issue is that of security, anyone can quite easily       
	access the camera recordings. To ensure that the system is secure, several 
  security protocols can be implemented. In addition to this, the system can also 	
  be upgraded to use deep-learning and computer vision algorithms to 	
  differentiate between people and objects and notify incase someone enters the room. 
	Finally, the exact list of parts is made and the prototype is built. 




Prototyping Phase:- 
	

This is the phase to build the Bot, Test and Debugit. 
Some earlier backgroundassumptions we have might fall apart here. 
This canalso be fixed by goingback to the ideation phase and working it 
out in arecursive fashion
 	























 # Gesture Controlled Robot https://www.hackster.io/357221/gesture-controlled-robot-74c5a5


Project Statement – The project aims to create a gesture controlled robot. The robots motion should be wirerlessly controlled by the motion of a handled motion remote. The robot should have complete freedom to move in any direction. 

Ideation and Planning: 

    • The components that are needed for this project are an IMU , two microcontrollers, Rf reciever and transmitter, robot chassis, two servo motors, wheels for the robot, batteries, breadboards and a few other electronic components such as wires.
    • Part of the pipeline to break:


Part of the Pipeline 
Feasibility
Advantages
Disadvantages
Microcontroller (Arduino) 
Very Difficult, unless experienced programmer.
It is easily programmable and is versatile with several builtin libraries.
Limited executions.Hard for beginners.
IMU
It is built by the manufacturer, so it can’t be modified.
It senses changes in orientation and can be used for detecting hand gestures. They are 
It has to be held in the hand and is cumbersome to carry around.
Rf transmitter and reciever.
Very difficult to modify unless you are a skilled professional
Enables wireless communication and is Arduino compatible. They are inexpensive and a lot of options are available.
There is only one frequency at which it can be operated. Also it has limited bandwidth.
L298 Motor Drivers and motor casing.


Can be easily controlled and customisd. 
They enable communication with the motors, are inexpensive and there are lot of options
H-bridge ICs come indifferent datasheets,making it a littledifficult task



    • Choosing the pipeline -
	From the above table it seems that the major areas of improvement can be done  in IMU and motor drivers. The IMU that they use (Gy-521 MPU-6050 MPU6050 Module 3) is moderately expensive. However, the major issue is that it can often be inconvenient to have an extra remote. Therefore, the task of motion sensing can be done using smart phones instead. A special app can be created for the smart phones, which can then make use of the accelerometers and gyroscopic sensors of the phone to communicate with the microcontrollers. The only issue with this is the feasibility of making an android app. 
 
The motor drivers recieve signals from the Arduinos and translate those signals to run the motors. The issues that may arise would be that operational voltages of the Arduino and the driver might be different which can be sorted by using a resistor or potentiometer system or scaling the output using software. 

Finally, the exact list of parts is made and the prototype is built. 


Prototyping Phase -

This is the phase to build the Bot, Test and Debugit. Some earlier backgroundassumptions we have might fall apart here. This canalso be fixed by goingback to the ideation phase and working it out in arecursive fashion

