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

    SENSOR DATA COLLECTION
    the temperature sensor continuously reads the temperature of the environment.

    Threshold Comparison
    The microcontroller checks whether the temperature is within the safe threshold range.

    SMS Alert via GSM Module

        If the temperature crosses the set limit, an SMS is sent to a predefined phone number.

        The message includes real-time temperature data and a warning message.

    Thermal Management Activation

        Simultaneously, a cooling system (like a fan) is turned on automatically using a relay.

        Once the temperature drops back to a normal range, the fan is turned off.
