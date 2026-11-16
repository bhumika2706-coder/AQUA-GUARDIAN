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


## 🛒 BOM
| Store | SKU | Product | Quantity | Unit Price (INR) | Subtotal (INR) | Buy Link |
|---|---|---|---|---|---|---|
| Robu.in | 471149 | Raspberry Pi 4 Model B with 4GB RAM | 1 | 11519.0 | 11519.0 | [Link](https://robu.in/?s=471149&post_type=product) |
| Robu.in | 1441079 | Raspberry Pi Camera Module 3 | 1 | 3299.0 | 3299.0 | [Link](https://robu.in/?s=1441079&post_type=product) |
| Robu.in | R271421 | SanDisk Ultra GO 64GB Micro SD Card 140MB/s R, Class 10 Memory Card | 1 | 1899.0 | 1899.0 | [Link](https://robu.in/?s=R271421&post_type=product) |
| Robu.in | 328377 | Electrode Probe for Liquid pH Value Detection Sensor Module | 2 | 819.0 | 1638.0 | [Link](https://robu.in/?s=328377&post_type=product) |
| Robu.in | 1749015 | Official 27W USB-C PD Power Supply for Raspberry Pi 5 - White (Plug Type: IN) | 1 | 1345.0 | 1345.0 | [Link](https://robu.in/?s=1749015&post_type=product) |
| Robu.in | 618530 | TowerPro MG996R Digital High Torque Servo Motor (360° Rotation) | 5 | 359.0 | 1795.0 | [Link](https://robu.in/?s=618530&post_type=product) |
| Robu.in | 51971 | L298N Dual H Bridge DC/Stepper Motor Driver Controller Module | 1 | 199.0 | 199.0 | [Link](https://robu.in/?s=51971&post_type=product) |
| Robu.in | 1770442 | D Shaft 775 12V 12000 RPM/MIN High Speed High Torque DC Motor Dual Shaft | 1 | 439.0 | 439.0 | [Link](https://robu.in/?s=1770442&post_type=product) |
| Robu.in | 30219 | Pro-Range Propellers 1045 (10X4.5) ABS DJI Black 1CW + 1CCW - 1 pair | 1 | 105.0 | 105.0 | [Link](https://robu.in/?s=30219&post_type=product) |
| Robu.in | 815780 | 12V High Quality DC Mini Submersible Pump | 1 | 169.0 | 169.0 | [Link](https://robu.in/?s=815780&post_type=product) |
| Robu.in | 25289 | 1 channel 5V 10A Relay Control Board Module with Optocoupler | 1 | 74.0 | 74.0 | [Link](https://robu.in/?s=25289&post_type=product) |
| Robu.in | 946972 | Pro-Range 11.1V 3300mAh 25C 3S Lithium Polymer Battery Pack | 1 | 2739.0 | 2739.0 | [Link](https://robu.in/?s=946972&post_type=product) |
| Robu.in | 7364 | IMAX B3 AC Pro Compact Balance Charger for 2S-3S LiPo | 1 | 349.0 | 349.0 | [Link](https://robu.in/?s=7364&post_type=product) |
| Robu.in | 2753 | Lipo Voltage Checker 1S-8S with Buzzer Alarm | 1 | 210.0 | 210.0 | [Link](https://robu.in/?s=2753&post_type=product) |
| Robu.in | 975683 | 24V/12V to 5V 5A Power Module DC-DC XY-3606 Power Converter | 1 | 139.0 | 139.0 | [Link](https://robu.in/?s=975683&post_type=product) |
| Robu.in | 815884 | Universal Glue Gun SD-A601 20W with Switch | 1 | 499.0 | 499.0 | [Link](https://robu.in/?s=815884&post_type=product) |
| Robu.in | 6005 | All Purpose Hot Melt Glue Sticks for Glue Gun - 5pcs | 1 | 79.0 | 79.0 | [Link](https://robu.in/?s=6005&post_type=product) |
| Robu.in | 815847 | Male to Male Jumper Wires 40 Pin 40cm | 1 | 129.0 | 129.0 | [Link](https://robu.in/?s=815847&post_type=product) |
| Robu.in | 815846 | Male to Female Jumper Wires 40 Pin 40cm | 1 | 99.0 | 99.0 | [Link](https://robu.in/?s=815846&post_type=product) |
| Robu.in | R229090 | Pro-Range 28AWG Extra Soft Tinned Stranded Silicone Wire Kit - 5 Colors x 5m | 1 | 499.0 | 499.0 | [Link](https://robu.in/?s=R229090&post_type=product) |
| Robu.in | 1808824 | TAPARIA Screw Driver Set with Bulb - 840 | 1 | 339.0 | 339.0 | [Link](https://robu.in/?s=1808824&post_type=product) |
| Robu.in | 1081544 | Nylon Cable Zip Ties 100mm White (Pack of 100) | 1 | 30.0 | 30.0 | [Link](https://robu.in/?s=1081544&post_type=product) |
| Robu.in | 781955 | Soldron High Quality 35W/230V Soldering Iron | 1 | 589.0 | 589.0 | [Link](https://robu.in/?s=781955&post_type=product) |
| Robu.in | 762465 | Noel FLUX soldering paste-10g-1Pc | 1 | 21.0 | 21.0 | [Link](https://robu.in/?s=762465&post_type=product) |
| Robu.in | R232399 | Tin Wire Soldering Tube(US) 0.8mm 40/60 8gram | 1 | 58.0 | 58.0 | [Link](https://robu.in/?s=R232399&post_type=product) |
| Robu.in | R218803 | YIHUA T24 Silicone Mat 440*310*6mm±mm | 1 | 529.0 | 529.0 | [Link](https://robu.in/?s=R218803&post_type=product) |
| Robu.in | 5989 | Multitec 07 Heavy Duty Nipper Precision Electronics Wire Cutting Tool | 1 | 108.0 | 108.0 | [Link](https://robu.in/?s=5989&post_type=product) |
| Robu.in | 1608702 | Freemans FCPP06 Combination Plier Black Phosphate | 1 | 184.0 | 184.0 | [Link](https://robu.in/?s=1608702&post_type=product) |
| Robu.in | 5990 | Multitec 150B Wire Stripper and Cutter Durable Electronics Tool | 1 | 60.0 | 60.0 | [Link](https://robu.in/?s=5990&post_type=product) |
| Robu.in | R267300 | Red 32 in 1 Multi-Purpose Precision Screwdriver Kit (No.6011-A) | 1 | 239.0 | 239.0 | [Link](https://robu.in/?s=R267300&post_type=product) |
| Robu.in | 1031043 | Non-Contact Type Inductive AC / DC Continuity Voltage Tester | 1 | 290.0 | 290.0 | [Link](https://robu.in/?s=1031043&post_type=product) |
| Robu.in | R164021 | HTC DM-85T Digital Multimeter with Backlight | 1 | 1299.0 | 1299.0 | [Link](https://robu.in/?s=R164021&post_type=product) |
| Robu.in | 344270 | Soldering Wire 1.0mm 100g for PCB, Electronics, and DIY Projects | 1 | 339.0 | 339.0 | [Link](https://robu.in/?s=344270&post_type=product) |
| Robu.in | 18287 | Nylon Cable Zip Ties 200mm White (Pack of 100) | 1 | 72.0 | 72.0 | [Link](https://robu.in/?s=18287&post_type=product) |
| Rees52 | RS7238 | TE-801 Adjustable LED Magnifying Glass Helping Hands Repair Station for Electronics, Soldering & PCB Repair | 1 | 700.0 | 700.0 | [Link](https://rees52.com/products/te-801-adjustable-led-magnifying-glass-helping-hands-repair-station?variant=46443403313319) |
| Rees52 | RS9648 | M4, M5, M6 Sizes Fastener Kit Nuts, Bolts & Screws Assortment Kit | 1 | 299.0 | 299.0 | [Link](https://rees52.com/products/m4-m5-m6-sizes-fastener-kit-nuts-bolts-screws-assortment-kit-for-diy-industrial-use-rs9648?variant=47936473399463) |
| Rees52 | RS1644 | New 100-240 Volt AC Smart Charger for Two 18650 Lithium Ion Batteries (US Plug) | 1 | 350.0 | 350.0 | [Link](https://rees52.com/products/new-100-240-volt-ac-smart-charger-for-two-18650-lithium-ion-batteries-plug-u-s-rs1644?variant=43607420010663) |
| Rees52 | RS5464 | 4 x 18650 Battery Holder Storage Box Case Plastic Battery Cell Holder Without Cover | 1 | 33.0 | 33.0 | [Link](https://rees52.com/products/4-x-18650-battery-holder-storage-box-case-plastic-battery-cell-holder?variant=45681318133927) |
| Rees52 | RS7649 | 18650 Li-ion 3000mAh Rechargeable Battery (3.7V 11.1Wh) | 4 | 149.0 | 596.0 | [Link](https://rees52.com/products/18650-li-ion-3000mah-rechargeable-battery-3-7v-11-1wh-long-backup?variant=46886634193063) |
| Rees52 | RS4953 | Turbidity Sensor Module Water Quality Monitoring Sensor | 1 | 500.0 | 500.0 | [Link](https://rees52.com/products/turbidity-sensor-module-compatible-with-arduino-esp32-raspberry-pi?variant=46199552245927) |
| Rees52 | RS4951 | Analog TDS Sensor Module Water Conductivity Sensor | 1 | 399.0 | 399.0 | [Link](https://rees52.com/products/analog-tds-sensor-module-water-conductivity-sensor-module-compatible-with-arduino-for-water-quality-monitoring-rs4951?variant=44009222930599) |
