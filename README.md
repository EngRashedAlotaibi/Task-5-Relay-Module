# Task-5-Relay-Module

This project illustrates the use of an ESP32 microcontroller to manage an LED via a relay module, The LED is programmed to activate when ambient light levels fall below a specific threshold and motion is detected.

# Equipment list and experiment set-up :
ESP32 

PIR

LDR

Relay Module

LED

Resistors

Breadboard

Wires





# Experiment Procedure:


Connect one terminal of the LDR to the 3.3V pin on the ESP32.

Connect the other terminal of the LDR to GPIO 14 on the ESP32.

Attach one end of a 10k-ohm resistor to the same terminal of the LDR that connects to GPIO 14.

Connect the other end of the 10k-ohm resistor to the ground (GND)

Connect the VCC pin of the PIR sensor to the 3.3V pin on the ESP32.

Connect the GND pin of the PIR sensor to the ground (GND) on the ESP32.

Connect the OUT pin of the PIR sensor to GPIO 25 on the ESP32.

Connect the VCC pin of the relay module to the 3.3V pin on the ESP32.

Connect the GND pin of the relay module to the ground (GND) on the ESP32.

Connect the IN pin of the relay module to GPIO 23 on the ESP32.

Connect the anode (longer leg) of the LED to the Normally Open (NO) terminal of the relay.

Connect the cathode (shorter leg) of the LED to one end of a 220-ohm resistor.

Connect the other end of the 220-ohm resistor to the ground (GND).



![image](https://github.com/user-attachments/assets/72f4ab25-0857-4b70-bef3-ebecaf2b6958)

