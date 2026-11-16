# AQUA-GUARDIAN
The floating robot is designed to be environmentally friendly, collecting waste water and monitoring water quality while cultivating plants that can be used for natural fish feed, thereby improving the cleanliness and sustainability of the aquatic environment.


## 🌟 Key Features

Smart Floating Waste Collection: Aqua Guardian will incorporate a floating robotic structure with a front-mounted servo-operated gate to collect light floating waste from the surface of the water and move it into a waste collection basket.

Monitoring of vital water parameters will be achieved by integrated pH, TDS and turbidity sensor and ADS1115 module that will give the user information about water quality.

Raspberry Pi Camera Module will be used to take the picture, and Python language and OpenCV will be used to analyze the image and assist in waste detection.

A built-in fish culture tray for plant cultivation will be provided to help the plants grow and eventually to provide alternative food for fish in order to ensure a sustainable aquatic ecosystem.

- Automated Fish Food Dispenser: A feeding mechanism will be used that is controlled by a servo system and will release a controlled amount of fish food into the water.

A 12V water pump will pump water to the plant growing tray, which will help the integrated plant growing system.

The camera, sensor, motor, servo mechanisms and pump are controlled by the raspberry pi 4 which will be used for intelligent control.

System flexibility and expandability will be taken into account, with multiple independent units for cleaning, monitoring, plant growth, and fish feeding that could be improved upon and expanded in the future.


## 🛠️ Assembly Instructions

Now that all these mechanical, electronic, sensor and software components are there, I will start working on Aqua Guardian – mechanical assembly, electronic and sensor systems, and software systems.

**1. Mechanical Assembly**

The whole robot body (2 pontoons attached, deck in the middle, waste collection basket at the front) is designed and 3D printed.
The two pontoons will be attached to the main platform to make a safe floating platform.
Then, I will put together the DC motor and propulsion at the end of the robot and choose an appropriate steering mechanism.
Front waste collection gate operation will be made possible with servo motors.
The upper part of the robot will be equipped with a fish-food dispenser and a plant growing tray.

**2. Electronics Integration**

The primary processor of Aqua Guardian will be Raspberry Pi 4.
A Raspberry Pi Camera Module will be attached to take the pictures and aid in the waste detection process.
Use of pH, TDS and turbidity sensors will be used to monitor various water quality parameters.
The integration of the analog sensor signals will be done with the help of analog sensor signals.
The L298N motor driver will be used to control the motors and the collection gates and fish food dispenser will be controlled by servo motors.
A pump will be used for the irrigation and water will be pumped to the tray in which this plant will be growing.
- Electronic components will be kept in an appropriate waterproof and cover location above the water level.

3. Wiring & Power Management

The power system will be designed to provide adequate power to Raspberry Pi, motors, servos, sensors and water pump.
A regulated power supply will supply the power to the Raspberry Pi, other components will be powered accordingly.
They will be integrated with the Raspberry Pi depending on what electrical requirements the motor driver, Relays module, ADS1115 and sensors have.
All Electrical Connections will be inspected for proper polarity, voltage and insulation.
Battery protection, proper fuse and master power switch will be integrated into the system.
Batteries and power wiring will be checked by an experienced electronics mentor prior to testing.

**4. Software and Programming**

Using Raspberry Pi Imager, Raspberry Pi 4 will be installed with Raspberry Pi OS.
The camera will be programmed via Picamera2/libcamera and image processing and waste detection will be done by OpenCV.
The reading of the pH, TDS and turbidity sensors will be read and analysed using python scripts.
Programs for motor or servo controls will be used to program the robot to move the robot and waste collection gates and fish-food dispenser.
A timed control system will be designed for the water pump to pump water to the plant tray.
A Monitoring Dashboard will be created for viewing sensor data and system information.

The final integration will include testing to verify the accuracy of the program.

First the electronic components, sensors, motors, servos and pumps will be individually tested.
Prior to electronics installation, the floating body will undergo a leak test, then a stability test.
- Reference solutions will be used to calibrate the water quality sensors.
The waste collection mechanism and fish-food dispenser will be separately tested.
Last but not least, all subsystems will be integrated and tested in a controlled environment to evaluate Aqua Guardian overall performance.

The ultimate goal is to develop a smart floating robotic system that will involve cleaning water surface, monitoring water quality, and natural fish feeding by the use of plants to achieve cleaner and healthier water bodies.

