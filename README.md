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

🧠 HOW IT WORKS

🔄 How It Works – Key Points

    Temperature Sensor Reads Environment

        A sensor like LM35 or DHT11 continuously measures the temperature (and optionally humidity).

    Microcontroller Monitors the Data

        A microcontroller (e.g., Arduino) checks the sensor readings at regular intervals.

    Threshold Comparison

        The system compares the current temperature with a predefined threshold value (e.g., 40°C).

    Sends SMS if Limit is Crossed

        If the temperature exceeds the threshold, the GSM module sends an SMS alert to a saved mobile number.

    Activates Cooling System

        At the same time, a cooling fan or other thermal device is switched ON via a relay.

    System Keeps Monitoring

        The temperature keeps being monitored. If it falls back below the threshold, the fan is turned OFF automatically.

    Repeat Alerts as Needed

        The system can be set to send repeated alerts or update messages based on your setup.


