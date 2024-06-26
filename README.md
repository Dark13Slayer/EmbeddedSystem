DOOR ACCESSING USING RFID WITH SIMPLE AUTOMATION

The project aims to enhance home security and comfort by integrating various sensors and devices.
When a person approaches the door, 
the PIR motion sensor detects their presence and prompts them to scan an RFID tag on the LCD. 
If the correct RFID tag is scanned, the servo motor unlocks the door and displays "Access Granted" on the LCD. 
If an incorrect RFID tag is scanned, "Access Denied" is displayed. 
When there is no motion detected, the system displays "Door is Locked" on the LCD. 
Additionally, based on real-time temperature and humidity readings from the sensor,the system should intelligently control a fan, ensuring optimal environmental conditions (e.g., turning on the fan if the temperature is 33 degrees Celsius and humidity is 51.80%). 
Finally, an LED should indicate the system's operational status.

Components Used:

    DHT11 Sensor
    PIR Motion Sensor
    Voltage Regulator
    Axial Fan
    RFID Module
    Jumper Wires
    ESP32
    Arduino Nano
    Breadboard
    OLED 128x64 Display
    Electric Door Lock

Instructions:

Clone the repository to your local machine.
Upload the code to your Arduino or ESP32 board.
Connect the components as per the circuit diagram provided in the documentation.
Follow the setup instructions to configure the system for your specific requirements.
Refer to the documentation for detailed usage guidelines and troubleshooting tips.
