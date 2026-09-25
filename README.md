*SPACE STATION AIR-SAFETY SIMULATOR*

*PROJECT TITLE*

Design and Implementation of a Space Station Air-Safety Simulator Using Arduino UNO

*AIM*  
To design and implement a miniature space station safety system using Arduino UNO that detects hazardous gases, identifies authorized astronauts, detects astronaut presence, and automatically controls an airlock using a servo motor.

*COMPONENTS REQUIRED*

  ➤ Arduino UNO   
  ➤ MQ-2 Gas Sensor   
  ➤ IR Sensor  
  ➤ RFID Card  
  ➤ Servo Motor  
  ➤ Buzzer   
  ➤ Jumper Wires   
  ➤ Breadboard   
  ➤ 5V Power Supply 

*WORKING PRINCIPLE*

The system continuously monitors the space-station environment and astronaut access. The RFID module identifies an authorized astronaut, while the keypad provides PIN-based authentication. The IR sensor detects astronaut presence near the airlock, and the MQ-2 sensor monitors for dangerous gases. The Arduino processes these inputs and controls the servo motor. When the required safety conditions are satisfied, the servo operates the airlock. If dangerous gas is detected, the buzzer provides an emergency warning and the airlock is kept in the safe state.

*BASIC WORKING FLOW*

RFID \+ Keypad  
↓  
Astronaut Authentication  
↓  
IR Sensor → Astronaut Detected?  
↓  
MQ-2 → Air Safe?  
↓  
Arduino  
↓  
Servo Motor → Airlock Control  
↓  
Buzzer → Emergency Warning

*PROCEDURE*

   ➤  Place the Arduino and sensors on the breadboard.  
   ➤  Connect the MQ-2 sensor to analog input A0.  
   ➤  Connect the IR sensor to digital pin D2.  
   ➤  Connect the servo signal to D5.  
   ➤  Connect the buzzer to D6.  
   ➤  Connect the RFID RC522 using the SPI pins.  
   ➤  Connect the keypad to the assigned Arduino pins.  
   ➤  Upload the Arduino program.  
   ➤  Scan the authorized RFID card and enter the correct PIN.  
   ➤  Test the airlock operation under safe and hazardous conditions.

*SCHEMATIC DIAGRAM*

*![schematicdiagram](SCHEMATICDIAGRAM)*

*BLOCK DIAGRAM*  
*![blockdiagram](BLOCKDIAGRAM)*

*RESULT*  
*![result](RESULT)*  

*CONCLUSION*

The project successfully demonstrates an automated space-station safety system. It combines authentication, gas monitoring, astronaut detection, and automatic airlock control to provide a safer environment for astronauts.

