# SMS-BASED-THRESHOLD-MONITORING-AND-THERMAL-MANAGEMENT
SMS based threshold monitoring lets the operators track remote equipment like generators by sending alerts if parameters exceed set limits.operators can adjust thresholds via SMS,ensuring safety and uptime even in areas without internet,but with mobile coverage.

PROJECT OVERVIEW

This project is a smart monitoring and control system designed to track temperature and other critical parameters in real-time. When the values exceed a defined threshold, it automatically sends SMS alerts and activates a thermal management response, such as turning on a fan or cooling system.

It’s especially useful for applications where overheating can damage equipment or cause safety hazards—like in server rooms, electrical panels, or industrial machinery.

REQUIREMENTS:
HARDWARE REQUIREMENTS:
➢ LPC 2148
➢ GSM MODULE (M660A)
➢ 16X2 LCD
➢ LM35
➢ BUZZER
➢ AT25LC512

SOFTWARE REQUIREMENTS:
➢ PROGRAMMING IN EMBEDDED C
➢ KEIL-C COMPILER
➢ FLASH MAGIC

🔄 HOW IT WORKS – Key Points

TEMPERATURE SENSOR READS ENVIRONMENT:
A sensor like LM35 or DHT11 continuosly measures the temperature.

MICROCONTROLLER MONITORS THE DATA:
A microcontroller checks the sensor readings at regular intervals.

THRESHOLD COMPARISON:
The system compares the current temperature with a predefined threshold value.

SENDS SMS IF LIMIT IS CROSSED:
If the temperature exceeds the threshold ,the GSM module sends an SMS alert to a saved mobile number.

WORKFLOW DIAGRAM:
🟢 System Starts
     │
🔧 Initialize Sensors & GSM Module
     │
🌡️ Read Temperature Data
     │
❓ Is Temperature > Threshold?
     │    
    Yes    /   No
    |          |
Send SMS    Keep Monitoring
Alert User 
     │
Loop Back to Sensor Reading

MODULES USED IN THE PROJECT.

    🟦 MICROCONTROLLER MODULE
        Example: Arduino Uno, Arduino Nano, PIC, or ATmega328.
        Purpose: Acts as the brain of the system. It reads sensor data and sends commands to the GSM module.
    🌡️ TEMPERATURE SENSOR
        Example: LM35, DHT11, or DS18B20
        Purpose: Continuously senses the temperature of the environment.
    📶 GSM MODULE
        Purpose: Sends SMS alerts to a registered mobile number when temperature crosses a certain threshold.
    🔋 POWER SUPPLY MODULE
        Example: 12V adapter, USB power bank, or regulated power supply
        Purpose: Supplies power to the microcontroller and GSM module.
    🧪 DISPLAY MODULE
        Example: 16x2 LCD or OLED Display (I2C).
        Purpose: Displays the current temperature and system status (optional for user visibility).
    🧰 JUMPERWIRES,BREADBOARD OR PCB
        Purpose: For circuit connections and mounting the components.

📦 HOW TO RUN

STEPS TO RUN THE PROJECT:

 1.connect all components as per circuit diagram.
 
 2.upload the code to Arduino via Arduino IDE.
 
 3.Insert a SIM card into the GSM module.
 
 4.Power the sytem(12v or regulated power).
 
 5.Monitor temperature-SMS will be sent if threshold is exceeded.
    


