# RGB LED Control using Arduino Uno R4 WiFi

## Introduction
This project is based on controlling an **RGB LED** using **Arduino Uno R4 WiFi**.
The main aim of this project is to understand how **digital output** and
**PWM (Pulse Width Modulation)** work in embedded systems.

Using this project, we can turn LEDs ON/OFF and also control their brightness.

---

## Objectives
- To understand RGB LED working
- To learn digital HIGH and LOW control
- To learn PWM based brightness control
- To practice Arduino programming
- To use Git and GitHub for project submission

---

## Components Required
- Arduino Uno R4 WiFi  
- RGB LED (Common Cathode)  
- 3 × 220Ω resistors  
- Breadboard  
- Jumper wires  
- USB cable  

---

## Software Used
- Arduino IDE / PlatformIO
- Git
- GitHub

---

## Pin Connections

| LED Color | Arduino Pin |
|---------|-------------|
| Red     | 9 |
| Green   | 10 |
| Blue    | 11 |
| Common  | GND |

Each LED pin is connected using a resistor to avoid damage.

---

## Working of the Project

### Digital Mode
- The LED is turned ON and OFF using `digitalWrite()`
- This helps in understanding basic GPIO control

### PWM Mode
- Brightness is controlled using `analogWrite()`
- Values range from **0 to 255**
- Different brightness values create different colors

---

## Program Explanation
- `setup()` function initializes serial communication
- RGB pins are set as OUTPUT
- `loop()` function controls LED behavior
- Delay is used so that changes are clearly visible

---

## Output
- Red LED blinks in digital mode
- RGB LED glows with different brightness levels
- Multiple colors are observed due to color mixing

---

## Learning Outcome
- Basic embedded system concepts
- Practical use of PWM
- Hands-on Arduino programming
- Version control using GitHub

---

## Author
**Yatendra Kumar Gupta**

## Date
**17 February 2025**

---

## Conclusion
This project helped me understand how RGB LEDs work using Arduino.
It is a beginner-friendly project and very useful for learning embedded systems.

---

## License
This project is created for **academic and learning purposes only**.
