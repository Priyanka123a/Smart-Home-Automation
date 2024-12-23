# Smart-Home-Automation
This Arduino Uno code integrates multiple functionalities including distance measurement, motion detection, and temperature monitoring using various sensors and actuators:

Ultrasonic Sensor (HC-SR04): Measures the distance of an object in front of it. If an object is detected within 40 cm, a servo motor rotates to 90°, and otherwise, it resets to 0°.

Servo Motor Control: The servo motor adjusts its position based on the proximity detected by the ultrasonic sensor.

PIR Motion Sensor with LED: Detects motion and controls an LED. When motion is detected, the LED turns on for 1 second.

Temperature Monitoring: Reads the temperature using an analog temperature sensor connected to pin A0. If the temperature exceeds 20°C, a fan (controlled by pin 12) turns on, and pin 13 remains off. Otherwise, both pins 12 and 13 remain off.

Serial Communication: Outputs temperature data to the Serial Monitor for debugging or logging purposes.

