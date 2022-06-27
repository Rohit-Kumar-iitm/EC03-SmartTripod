# EC03-Smart Tripod - Mini Task 2                      
- ROHIT KUMAR, 21st June 2022

### **Project – 1:  Door Lock system with Arduino and RFID Module** 
![project-1](https://user-images.githubusercontent.com/107256063/175406667-39e1ac4f-3bd6-48ac-8c2f-39d248b0ae7a.gif)

• This project opens a door, using some compononents like
1. Arduino(nano version) – the heart of project 
2. RFID Module(RFID RC522) – to identify the unique tag 
3. Stepper motor – to rotate the door 
4. A stepper motor driver(ULN2003 Stepper Motor Driver Module) 
5. And ofcourse some extra add ONs 😊 like jumping wire, LEDs, OLED display, power supply, breadboard etc. like stuffs.

•	It is a smart project, in which a door is opened only if the correct (RFID)tag(and it’s UID is also stored in the arduino) is in the proximity to the RFID Reader/Antenna(An RFID module).


•	References used:
  1. https://www.hackster.io/bruno_opaiva/door-lock-system-with-arduino-and-rfid-module-25f092
  2. What is an RFID module: 
      - https://lastminuteengineers.com/how-rfid-works-rc522-arduino-tutorial/
      - https://www.youtube.com/watch?v=Ukfpq71BoMo

### **Project – 2:  Temperature and humidity measurement using Raspberry Pi and Bluetooth module:** 

![image](https://user-images.githubusercontent.com/107256063/175830496-3f94f82e-1621-4d99-b242-3cf8a1bb816c.png)

•	In this project, we analyze the room’s temperature and it’s humidity. 
Correspondingly we require the below items:
1.)	Raspberry Pi Pico – The heart of the project 😅
2.)	DHT11 Temperature and Humidity Sensor – the name suggests its use 😉  
3.)	Adafruit RGB Backlight LCD 16x2 – to showcase our results 😎
4.)	HC-05 Bluetooth Module – to trigger our system ⚡
5.)	And some add ONs like breadboard, power supply, jumping wires, and some bluetooth devise say your smartphone.

•	So, the thing is this system will display the temperature and humidity parameters on LCD.
First, we trigger the system via connecting the bluetooth module with our phone. And on phone we will use a bluetooth terminal, using that terminal we will send a request to the system to start doing it’s task.
And next, when the required parameters are measured we display it in the LCD. 

•	References used:
  1. [See project here](https://www.hackster.io/stefanalbertalexandru/temperature-and-humidity-measurement-a0e263)
  2. [Bluetooth module handling](https://www.youtube.com/watch?v=otIy2zwmdvw)


### **Project – 3:  Mecanum Wheels Robot using a Bat Hand controller(PcB): **

![project-2](https://user-images.githubusercontent.com/107256063/175830635-87b192ba-159d-4d89-b7f7-25d5521b0435.gif)

•	In this challenging project we, control a four-mecanum-wheeled robot with a physical hand controller(bat shaped) i.e., a PCB on which ESP32 can be mounted. Similarly, there’s a PCB sitting on the head of the car-type-robot on which also ESP-32 is sitting. 

•	There are many requirements for this project.
  1. Body of robot – 4 mecanum wheels (Mecanum wheels) we can make or purchase it.
  2. Designing the PCB of robot: 
     - Design a schematic in software’s like Eagle etc.
     - Generate gerber files and get the PCB from a well-professional sources like PCBWay etc. 
     - And then mounting the PCB and making our robot design. 
  3. Similarly, designing the PCB of hand controller.

![image](https://user-images.githubusercontent.com/107256063/175830915-f0b067ed-b861-4c61-af79-851b09625d63.png)

Improvements: 
Can use some app like dabble, to control it just to reduce the cost of using 2 ESP32s.

### **Project – 4: 3D scanning using Arduino and Laser sensor**

![image](https://user-images.githubusercontent.com/107256063/175830979-2145e860-199e-4194-a647-60fb663bc26d.png)

•	To build this project we will be using the below components:
1.	Arduino uno R3
2.	2 Stepper motors (one on the base, the other on the screw-type axis)
3.	LCD display, Hex keyboard (for manual control, to set the start position) 
4.	[Laser sensor](https://www.smartray.com/glossary/laser-sensor/#:~:text=The%20laser%20sensor%20works%20based,addition%20to%20the%20various%20resolutions.)
5.	Some mechanical modules, like platform with a shaft, few shafts, nuts, bolts etc.

•	The principle is: 
1.	 First, We use a stepper motor with a model platform mounted to it. The platform is used to place the physical models to be scanned. Both the motors are operated in coordination to achieve a 3D scan of the model.
2.	 Next, Arduino controller is used to control the movement of both motors along with the scanner sensor to achieve the scan. The scan data is saved to an SD card using an SD card module. The scan data can then be transferred to a PC. 

•	Reference: [See Project here](https://nevonprojects.com/3d-scanner-machine-using-arduino/)

•	Improvements: Can use better algorithms to fasten the process.

### **Project 5: **



