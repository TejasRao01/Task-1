**Project – 1**

Water Level Controller using 8051 Microcontroller https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/

Aim - This projects aims to create automate the proccess of controlling the level of water in a tank using a system controlled by a microcontroller.

Description – The system consists of a series of sensors that are used to measure the level of water in the tank. The sensors work on the priciplle of the conductivity of water. The system mentioned in the example consists of 4 wires running up to different levels in the tanks. The circuts will get completed based on the level of water inside the tank. Once the circuits get completed, they produce a signal at the inputs of the microcontroller, which is enabled by the help of transistors.

Based on these signals recieved by the microcontroller, the motors controlling the inlet of water get switched on or off. In addition to these, a 555-timer and a capacitor are connected so as to provide a clock signal to provide a timing signal. The motors get sufficient power to run by the means of a relay system.

Finally, there is an LED display screen connected to the microcontroller that displays the level of water in the tank.

Comments-

While the system is based on a 8051 microcontroller, it can easily be replicated by using an Arduino instead. The system can be improved by increasing the sensitivity by either using more wires or different types of sensors (maybe detecting the level of water by measuringing conductivity and feeding in analog input, instead) .


**Project-2**

Raspberry Pi Security Camera www.instructables.com/Raspberry-Pi-Security-Camera-1/

Aim – This project seeks to create a security system by using a Raspberry pi. Description – The project requries a Raspberry Pi, a Rasperry Pi compatible camera or Pi camera and motion detection sensor. The components can be directly connected to the Raspberry Pi. The most important task in this project is the creation of a Flask Web Server on the Pi that enables it to automatically take pictures and recordings. The first step of this project is to set up the pi and connect it to the internet. Next, the camera is set up and the Flask library is installed onto the Pi. Once this is done, a form class is created that enables to user to manually select the camera settings and manually record video and audio. Based on this form, a user interface is created using a Flask template. This is written using HTML and is basically used to improve presentation and enable the user to access the form. It is stored in a folder named templates. The template now has to be rendered. To do this a separate file, named appCam.py is created and stored outside the templates folder . To operate the camera, a file named camOperator.py is created, this file is used to ensure access to the built-in functions in the Pi camera. These functions change the record settings of the security camera using the specifications set by the user and also setting up default values in case the user has not set any specific settings. The methods defined in this class change the "record" settings on the security camera using the sensitivity and duration inputs that the user provides, while establishing default values for these variables if user input is not present. Finally a program called rec.py is written that gives instructions to the camera based on the user data. It does so by constantly reading the data from the Flask text file. All recordings are stored in a .h264 or .jpg file.

**Project - 3**

Gesture Controlled Robot https://www.hackster.io/357221/gesture-controlled-robot-74c5a5

Aim – The aim of this project is to create a robot that can be controlled using gestures.

Description – The project consists of an Arduino Uno, Arduino Nano, an Interial Measurment Unit (IMU) and a Reciever-Transmitter and some other components. There are basically two circuits, one for transmission and one for recieving the signal. The Motion Sensing is accomplished using the MPU6050 accelerometer sensor (IMU). The hand gestures sent are converted to signals that are processed by the Nano and send to the transmitter. The transmitted Signals are then recieved by the reciever on the robot and are decoded by the Uno. The processed signals are then used to control the Motors of the robot.

Once the circuits for the reciever and transmission parts are completed, the most important task is coding the control system. The IMU consists of an accelerometer and a gyroscope. The robot should accelerate when the absolute value of acceleration in any direction is between 20 and 80.


![Working of a hand gesture controlled robot (online-video-cutter com)](https://user-images.githubusercontent.com/85809459/122042442-c7f0df00-cdf7-11eb-9fdd-fa907b672572.gif)


**Project – 4**

Password Based Door Lock System using 8051 Microcontroller

https://www.electronicshub.org/password-based-door-lock-system-using-8051-microcontroller/

Aim - This project aims to create a door lock system that is password protected.

Description – The project consists of a microcontroller, a 4x4 matrix keypand, motors and an LCD screen. The passwords are entered into the keypad and the microcontroller, in this case a 8051, deteremines whether the password input into the keypad is correct or not. Based on this, it opens the door by actuating the motor or keeps it shut. The LCD display is used to determine whether the password is right or wrong.

The control system consists of the aforementioned parts as well as a 555 timer that provides the clock signal to the microcontroller. Once the components are connected according to the schematic diagrram, the microcontroller needs to be programmed. The program consists of the algorithm that is used to check whether the password entered is correct or not and take action based on that, as well as controlling the display system.

Comments – This is a rather simple system and the advantages of that are low power consumption and easy design. However, the system has the disadvantage that the door cannot be opened if the password isn’t known and that the range is limited. One possible solution is to make the system more robust by adding a wireless sensor and having a super-password that is only available to the administrator.

**Project – 5**

Electronic Eye Controlled Security System https://www.electronicshub.org/electronic-eye-controlled-security-system/

Aim – Create a simple Home Security application called Electronic Eye Controlled Security System using LDR.

Description – This project consists of an electronoic eye, a detection system which continously watches if someone is trying to enter the builing or not. The circuit of the system is based on the concept of a light activated stwitch which is built using an LDR or Light dependent Resistor. The basic property of an LDR is that its resistance increases rapidly with decrease in light intensity. The light activated switch is built using an LDR with a comparator in a configuration that supplies power in the presence of low light. The detection system uses this principle to detect objects or people as the amount of light intensity entering the sensor decreases. The decrease in resistance increases the output and a buzzer is triggered.

The system consists of two circuits, a power supply circuit and a logic circuit. The power supply circuit consists of battery, diode, regulator and capacitors. The purpose of the diode is to protect the circuit from reverse polarities. A regulator is also used to regulate the output voltage of the circuit.

The logic circuit consists primarily of some transistors and the LDR, and its primary functios is similar to that of the light activated switch.

Comments – This project is a simple implementation of a system that detects intruders. An advantage of this system is that it does not need a microcontroller and so is very inexpensive and has low power consumption. A disadvantage is that it will buzz everytime a person, whether that person is an intruder or a friend. Also, the system will not work in low light conditions. The system can be improved by maybe usig 2 LDRs that are separated by some distance.

![p5](https://user-images.githubusercontent.com/85809459/121961446-13b67080-cd85-11eb-8096-7bbf0f2eff5b.jpg)


**Project – 6**

Mobile Controlled Home Appliances without Microcontroller

https://www.electronicshub.org/mobile-controlled-home-appliances-without-microcontroller/

Aim – This project aims to create a circuit that can control home appliances using the mobile phone without using a microcontroller.

Description – The circuits are designed to remotely detect the dignals from the cell phones and turn on/off home appliances for specified time intervals. The basic principle for this project is DTMF or Dual-Tone Multi-Frequency. Every time a button is pressed, two audio-signals are sent by the phone indicating the row and column number of the button. Based on this the number representing the button can be determined. The main task is decoding these signals.

The components required for this project are prebuild DTMF decoders and relays and a reciever phone. The phone is connected to the decoder via an audio-jack, and once the phone is connected to the user’s phone ,it sends the signals from the mobile phone and the decoder converts it to a binary signal. This binary signal is sent to the relay and the desired task is performed.

Comments – This is a simple application of remotely controlling home appliances without using a microcontroller. A disadvange of this system is that it requires another cellphone to work, which will be expensive unless there is a spare, unused phone available. Another issue is that there is no security and a limited number of devices can be connected.
![mobile](https://user-images.githubusercontent.com/85809459/121998811-138c9400-cdca-11eb-8a48-915104c29b20.jpg)


**Project – 7**

Temperature Controlled Switch using LM35, LM358 https://www.electronicshub.org/temperature-controlled-switch/

Aim – To create an automatic Temperature Controlled Switch using LM35 Temperature Sensor that can be used to automatically turn ON a switch when a desired temperature is detected.

Description – The project is uses a temperature controlled switch which is a device that is activated based on temperature. The temperature controlled switch consists of three parts, the sensor , the control unit and the switch. The sensor detects the temperature and converts it into electrical signals that are processed by the control unit which decides the action that has to be taken. The switch is then turned on or off.

This project uses a LM35 as the temperature sensor, a LM358 OP-Amp as the controller, and a 5V relay module. The relay module is used to amplify the ‘ON’ signal sent out by the OP-Amp. The OP-Amp is used in the comparator configuration. The non-inverting terminal of the Op-Amp is connected to the output of the sensor and the inverting terminal is connected to a poteniometer. Initially, the inverting terminal has a higher voltage than the non-inverting terminal and the output is ‘OFF’. Later, as the temperature rises, the output of the sensor increases and after a certain critical temperautre, the voltage at the non-onverting terminal exceeeds the inverting terminal and the output changes to ‘ON’. Thus, it acts like a switch.

Comments – This is an example of a project that does not use a microcontroller to automatically turn on or off appliances at home. A limitation of this system is that it gives only one output for one temperature. If different outputs are needed for dfferent temperature ranges, then a microcontroller might be needed.

![temp](https://user-images.githubusercontent.com/85809459/121998814-15565780-cdca-11eb-86a2-c4ddd67e4a14.jpg)

**Project – 8**

Arduino Joystick Interface – Control Servo using Arduino and Joystick https://www.electronicshub.org/arduino-joystick-interface-control-servo/

Aim – The aim of this project is to control servo motors and an LED using an Arduino and a joystick.

Description – One of the major components required for this project is an analog joystick, which consists of a series of potentiometers (2 for each axis) which produce an input based on their relative position. There is also a push button which can activated if the knob is pressed.

Since the joystick is a system of potentiometers, the connections to the Arduino are similar to connecting to the potentiometer. Once the connections are made, the code is uploaded/written. Once that is done, the monitor will display the values from the potentiometers, that is constantly refreshed. The input from the potentiometer is analog and the output is digital.

The interface between the Arduino and hte joystick is achieved using the Joystick module. The data from the joystick is constantly collected and after processing, the required command is issued to the servo motor. A calibration is done to ensure desired sensitivity. Similar code is written for the LED.

Comments – This project is useful to control remotely controlled cars and LEDs.

![joy](https://user-images.githubusercontent.com/85809459/121998820-16878480-cdca-11eb-9a3b-f7fd4f71a445.jpg)



**Project – 9**

Car Parking Guard Circuit Using Infrared Sensor https://www.electronicshub.org/car-parking-guard-circuit-using-infrared-sensor/

Aim – To design and build a Car Parking guard sensor using infrared sensors that is used to assist in parking.

Description – The project aims to create a simple system that tells the driver if the car is about to collide or not. The project consists of an IR sensor that is used to measure the distance of the obstacle from the car, a tone detector which will be used to trigger the LM555 timer to generate a PWM for the buzzer.

The IR sensor first sends a signal that sets off the timer. This is done using the aid of the Photo-Darlington transistor. The timer, which operates in astable multivibrator mode, sends a PWM, or pulse width modulation signal to the the tone trigger. The tone trigger interprets the signal generated and gives the output based on that.

If there is an obstacle, the IR sensor recieves the rebound rays, and sends a signal to the tone detector, causing it to turn low and get disabled. The LED, thus will remain lighting and buzzer makes a continous sound.

Comments – The circuit for this system is rather complex, however it is not too difficult to repreoduce.

![jammer](https://user-images.githubusercontent.com/85809459/121998824-17b8b180-cdca-11eb-8a23-276b21808eb5.jpg)

**Project – 10** TV Remote Jammer Circuit https://www.electronicshub.org/tv-remote-jammer-circuit/

Aim – To create a jammer circuit for TV remote

Description – The TV remote operates on IR waves and thus the jamming circuit basically generates IR waves that disrupts the communication between the remote and the TV sensor. The jammer circuit basically creates a series of pulses that are sent to the reciever. When the signal from the remote is sent to the reciever, the net signal is that of the remote combined with that of the jammer. This combined signal is an invalid signal and will not result in any action by the TV.

Phillips TV remotes follow the RC5 protocol and each button transmits 14 bits. The protocol operates at a frequency of 36-37 kHz. Thus, the circuit is also designed to produce signals in this range. The major component is the 555 timer which is operated in the astable multivibrator mode. The pins of the timer are connected according to the schematic diagram and a potentiometer is used to control the frequency. The potentiometer is then adjusted to tune the circuit to 38 kHz.

Comments – A disadvantage of this circuit is that it difficult to tune the circuit to produce at exactly 38 kHz.

**Project – 11** Electronic Mosquito Repellent Circuit https://www.electronicshub.org/electronic-mosquito-repellent-circuit/

Aim – To design and built an electronic mosquito repellant circuit.

Description – The main principle behind this project is the fact that mosquitoes are repelled by ultrasonic sound. The circuit thus creates generates noise to repel the mosquitoes away. For this project, a 555 Timer which runs in astable multivibrational mode is used. The buzzer, which is the most important component for this project is driven by an oscillating circuit, which in this case is based using the 555 timer. The timer is used so as to generate the signal of pulses which drive the buzzer.

Once the circuit is assembled and the switch closed, the timer gets the activated. The voltage input the trigger and threshold pins are determined by the capacitance that they are connected to. Due to the charging and discharging of these capacitors, the output is an oscillating signal. The system is adjusted so that the output turns out to be 38 kHz.

Comments – The advantage of this circuit is that it repels mosquitoes without the need for chemical mosquito repellants. A disadvatnge is that the signals might bounce away if there are too many obstacles. Another disadvantage is that it is not effective for small populations of mosquitoes.

**Project – 12**

IoT Pet Feeder https://www.hackster.io/circuito-io-team/iot-pet-feeder-10a4f3

Aim – To design and build an automatic pet feeder.

Description – The project consists of an Arudino Uno, a P IR motion sensor, and a few other common electronic devices. In the specific set up mentioned in the site, the system detects the pet and actuates the motor controlling the food gate. The system also beeps periodically.

The implementation has a PIR sensor, Arduino uno (or other), servo, speaker, esp8266-01, and a power source. The esp8266-01 is a device that is used to ensure wifi connectivity. Once the components are connected and the code is written the system ready to be used.

Comments – The system can be expanded and made more sophisticated based on need by adding more sensors or by increasing the quality of the sensors.

![playdog_gif_YI8e1YcUYp](https://user-images.githubusercontent.com/85809459/122043085-92002a80-cdf8-11eb-90d5-9c1b0d695fee.gif)


**Project – 13**

Auto Night Lamp Circuits https://www.electronicshub.org/auto-night-lamp-using-high-power-led/

Aim – To make an automatic night lamp circuit.

Description – The project has to switch on the night lamp at night and automatically turn it off during the day time. The circuit consists of a series of high powered Leds and a photoresistor. One of the biggest challenges that have to be tackeled is the case when the light inenstiy reaches ambigous values. This cases flickering as the circuit gets switched on and off in quick intervals which may damage the components. A solution to this is to have two sensing devices which get switched on at different light intensities. The circuit is designed so that the light switches off when both sensors detect light and switches off when either one detects darkness.

The project consists of two different sensing devices, a U1 IC 741 and a U2 IC741. The project also has 555 timer in bistable mode that is used to provide the clock signals.

Comments – The project is a simple implementation of the making a automatic night lamp control system without using a microcontroller.

**Project – 14**

Police Siren Circuit using NE555 Timer

https://www.electronicshub.org/police-siren-circuit-using-ne555-timer/

Aim – To create a Police siren circuit using a NE555 Timer

Description – The main concept of the project is the multivibrator. A multivibrator is a device that oscillates between two distinct states and it categorised based on the nature of the states. Of both are quasi-stable, the configuration is astable. Similarly there are bistable and monostable configurations for the multivibrator. For this project, the multivibrator is kept in the astable configuration and is used to provide clock signals to the circuit. There are two NE555 timers which operate on different frequencies and the output of one of the timers is fed in as the input to the other timer, thereby modulating the signal of the latter with respect to the former. This signal is sent to the buzzer that generates the distinct sound of the police siren. The output frequency can be adjusted by changing the value of resistance that are connected to the two timers.

Comments – This audio can also be enhanced using an Op-amp to amplify the signal sent out to the buzzer. Another thing that can be done is to use a microcontroller to control the output of the buzzer.

**Project – 15**

Celsius Scale Thermometer using AT89C51 and LM35

https://www.electronicshub.org/celsius-scale-thermometer-using-at89c51-and-lm35/

Aim – To create a Celcius Scale Digital thermometer using a microcontroller.

Description – This project consists of a LM35 temperature sensing sensor that is integrated with a microcontroller. The LM35 sensor has the advantage of giving output in celsius without needing calibration. The project also consists of a 8 bit ADC that runs using the sucessive approximation method.

The main principle behind this project is analog to digital conversion. The input from the LM35 sensor is first converted to digital signals which are then sent to the microcontroller, which in turn, processes the signal and sends the required output to an Led display. A small amount of calculation also has to be done to convert the input from the sensor to Celsius.

Comments – While the microcontroller mentioned for this project is not an Arduino, it can very easily be implemented using an Arduino.

![Celsius Scale Thermometer (online-video-cutter com)](https://user-images.githubusercontent.com/85809459/122043786-5dd93980-cdf9-11eb-84cb-dca18cf661d2.gif)

