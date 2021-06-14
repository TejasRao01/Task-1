
# Raspberry Pi Security Camera www.instructables.com/Raspberry-Pi-Security-Camera-1/


The Security camera has 3 major components, the Camera, the Raspberry Pi, and the Motion sensor. 

First the lights of all the comoponents are checked to if any of the components have stopped working or not.

If one of the components is not powering up, that means that the component is damaged and needs to be replaced.
 
If all the components are working, first check if all the connections are proper before debugging each of the components need to be individually. 

The first component that must checked is the Raspberry Pi. To check the raspberry pi, try connecting it to the power source and a monitor and see if you are able to log in. If the screen is blank/or you aren’t able to log in, then the issue might be that your SD card is either damaged or corrupted. If you are able to log in, check the output pins can be controlled by trying to light LEDs or executing commands in some test circuit.  If this does not work, that means some of the pins have been damaged and the Pi needs to be either repaired or replaced. 

If the raspberry pi is working fine, the Camera, Sensor and the software needs to be tested. Starting with the camera, if the camera is switching on, it needs to be tested to see whether it is relaying data or not. For this a sample code is run. If the camera now relays data, that means that there is an issue with the software that needs to be diagnosed, else there is an issue with the camera that needs to be further investigated. 

Similarly, for the motion sensor, the debugging code is run to see whether there is an issue with the sensor while relaying the data. If this is fine, then there is an error in the code which needs to be debugged. 

Finally, we have the Software. Issues with the software can only be diagnosed by running each task individually and working through the errors. 









 # Gesture Controlled Robot https://www.hackster.io/357221/gesture-controlled-robot-74c5a5


The Gesture Controlled Robot has the following sub-systems; the IMU, the microcontrollers, the motor drivers, the RF recievers. Before anything else, each of the sub-systems are checked if they are powering on. Incase this isnt the case, they need to be replaced. Next, all connections between the connects are checked and tighened.

If all components are powering on, they need to be individually tested to see if they are relaying data properly or not. For this project, the flow diagram is IMU -> microcontroller1 -> RF transmitter -> RF reciever -> Microcontroller2 ->  Motor Driver -> Motor. 

Before anythig else can be done, the Ardino is first debugged as that is the component through which the entire system has to be be checked. If the Arduino can be switched on and code can be uploaded, then proceed to check the pins of the Arduino. If not, it means that the Arduino is damaged. To check the pins, try lighting LEDs using the pins and try recieving some output, maybe using resistors and batteries. If there is any issue with the pins, then either use oher pins or use another Arduino.

If the Arduinos are working, then analyse each of the sub-systems according to the pipeline. First check the IMU sensor by running some testing code and printing the output as you change the orientation of the sensor. If there is no output, that means that there is some issue with the IMU sensor. If there is no issue then that means either there is a typo or logical error in the main code or the error is in some other sub-system.

Next, test the RF transmitter and Reciever by sending some test signals. If there is some error here, the challenge is to determine whether the error is in the transmitter or the reciever. One possible way is to use Transmitters and receivers that are known to work and testing both by using the ones that are known to work. 


Finally the Motor drivers and motors are tested indiviually. The motors maybe tested first so that the motor driver can be tested using the same motors. Just like the other sub-systems, the motor driver will be tested using some debugging code. 

If all these work fine, the batteries and wires are tested, and if even these turn out to be fine, the issue lies in the code for the whole system, which needs to be checked for errors.

