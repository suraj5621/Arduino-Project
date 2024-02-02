# Ultrasonic Distance Measurement with Arduino

This Arduino sketch measures the distance using an ultrasonic sensor and provides feedback using a buzzer and an LED when an object is too close.

## Components Required
- Arduino board (e.g., Arduino Uno)
- Ultrasonic sensor (HC-SR04)
- Buzzer
- LED
- Jumper wires

## Wiring Instructions
1. Connect the trigPin of the ultrasonic sensor to digital pin 9 on the Arduino.
2. Connect the echoPin of the ultrasonic sensor to digital pin 10 on the Arduino.
3. Connect the positive (anode) pin of the buzzer to digital pin 11 on the Arduino.
4. Connect the positive (anode) pin of the LED to digital pin 13 on the Arduino.
5. Connect the negative (cathode) pins of the buzzer and LED to the ground (GND) pin on the Arduino.
6. Make sure to connect the VCC and GND pins of the ultrasonic sensor to the appropriate power and ground pins on the Arduino.

## Running the Code
1. Install the Arduino IDE if you haven't already. You can download it from the [Arduino website](https://www.arduino.cc/en/software).
2. Open the Arduino IDE and create a new sketch.
3. Copy the provided code and paste it into the new sketch.
4. Connect your Arduino board to your computer using a USB cable.
5. Select the correct board and port from the **Tools** menu in the Arduino IDE.
6. Click the **Upload** button to compile and upload the code to your Arduino board.
7. Open the Serial Monitor from the **Tools** menu to view the measured distance in real-time.

## Troubleshooting
- Double-check your wiring connections to ensure they match the instructions provided.
- Make sure you've selected the correct board and port in the Arduino IDE.
- If you encounter any errors during compilation or upload, refer to the error messages for troubleshooting steps.
- Ensure that your ultrasonic sensor is properly powered and oriented for accurate distance measurements.

