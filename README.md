# Wristband_(Real_time_feedback)
 For a classroom it sents emergency if any students is emotionally unfit
 (wokwi simulator setup )
![WhatsApp Image 2024-09-02 at 22 40 12_624ffce7](https://github.com/user-attachments/assets/0c8ff85f-752c-4123-a1e4-7106cc283b4f)
(How to Use)
Set Up the Circuit: Follow the circuit setup instructions in the Wokwi simulator to connect the components.
Upload the Code: Copy the provided Arduino code into the Wokwi code editor and start the simulation.
Monitor Output: Open the Serial Monitor in Wokwi to view real-time data and alerts. Adjust the potentiometer to simulate heart rate changes and observe the buzzer activation.

(Circuit Setup)
Wokwi Simulator
Open Wokwi Simulator:

Go to Wokwi Arduino Simulator.
Add Components:

Arduino Uno
DS18B20 Temperature Sensor
Potentiometer
Buzzer
Breadboard
Component Connections:

DS18B20:
VCC to 5V on Arduino.
GND to GND on Arduino.
DATA to Digital Pin 2.
4.7k ohm resistor between VCC and DATA.
Potentiometer:
Middle pin to Analog Pin A0.
One side pin to 5V.
Other side pin to GND.
Buzzer:
Positive leg to Digital Pin 3.
Negative leg to GND.

