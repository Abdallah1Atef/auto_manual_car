# Automatic and Manual Obstacle-Avoiding Car

## Overview
Our project aims to develop an **automatic and manual car** that can avoid obstacles autonomously. The car can be controlled manually or set to automatic mode, where it uses sensors to detect and avoid obstacles in its path. This project integrates various IoT technologies, including **embedded systems**, **cloud computing**, and **mobile application development**, to create a functional and intelligent vehicle.

---

## Features
- **Automatic Obstacle Avoidance**: The car uses **IR sensors** to detect obstacles and automatically adjusts its path to avoid collisions.
- **Manual Control**: Users can manually control the car using a **mobile application**.
- **Real-time Data Monitoring**: The car sends real-time data to a **cloud platform** for monitoring and analysis.
- **Mobile Application**: A **Flutter-based mobile app** allows users to control the car manually, view sensor data, and switch between automatic and manual modes.
- **Cloud Integration**: The car integrates with **Firebase** and **HiveMQ** for real-time data storage and communication.
- **Hardware Assembly**: The car is built using **ESP32-based embedded systems**, sensors, and actuators.

---

## Requirements

### Hardware
- **ESP32 Development Board**: For controlling the car's movements and sensor data processing.
- **IR Sensors**: For detecting obstacles in the car's path.
- **Servo Motors**: For controlling the car's steering mechanism.
- **DC Motors**: For driving the car's wheels.
- **LEDs**: For visual indicators and notifications.
- **Breadboard and Wires**: For circuit connections.
- **Battery Pack**: To power the car.
- **Keypad**: For manual input and control.

### Software
- **Arduino IDE**: For programming the ESP32 microcontroller.
- **Flutter**: For developing the mobile application.
- **Firebase**: For real-time data storage and authentication.
- **HiveMQ**: For MQTT-based communication between the car and the mobile app.
- **Platform IO**: For embedded system development.

---

## Project Structure

### 1. **Hardware Assembly**
   - The car's hardware components, including the **ESP32**, **sensors**, **motors**, and **LEDs**, are assembled and connected.
   - The **IR sensors** are used to detect obstacles, and the **servo motors** control the car's steering.
   - The **DC motors** drive the car's wheels, and the **LEDs** provide visual feedback.

### 2. **ESP32 Programming**
   - The ESP32 is programmed using the **Arduino IDE** to handle sensor data, control the motors, and communicate with the cloud.
   - The car can switch between **automatic** and **manual modes** based on user input.

### 3. **Mobile Application**
   - A **Flutter-based mobile app** is developed to allow users to control the car manually, view sensor data, and switch between modes.
   - The app integrates with **Firebase** for user authentication and real-time data storage.

### 4. **Cloud Integration**
   - The car sends sensor data to **Firebase** and **HiveMQ** for real-time monitoring and analysis.
   - The mobile app retrieves data from the cloud to display real-time sensor readings and control the car.

### 5. **Testing and Debugging**
   - The car is tested in various environments to ensure it can detect and avoid obstacles effectively.
   - The mobile app is tested for usability and functionality, ensuring smooth communication with the car and cloud.

---

## Challenges Faced
1. **Power Supply Issues**: The car initially faced issues with insufficient current intensity, requiring multiple battery changes. The final solution involved using **three lithium-ion batteries**.
2. **Motor Gear Misalignment**: One of the motors had misaligned gears, which had to be fixed to ensure smooth operation.
3. **Code Optimization**: Ensuring the code was efficient and could handle real-time data processing and communication was a significant challenge.

---

## Real-life Applications
- **Robotics**: The obstacle avoidance system can be used in robots for navigation in dynamic environments.
- **Automotive**: The technology can be applied in **autonomous vehicles** for safer driving.
- **Toys**: The system can be used in children's toys to prevent collisions and enhance safety.

---

## Conclusion
This project provided a comprehensive understanding of **IoT technologies**, including embedded systems, cloud computing, and mobile application development. By integrating these technologies, we successfully developed an **automatic and manual car** capable of avoiding obstacles. The project highlighted the importance of **practical experience** and **teamwork** in solving real-world problems.

---

## Feedback
The training was an excellent opportunity to apply theoretical knowledge to practical projects. Working with hardware and embedded systems provided valuable insights into the challenges and solutions in IoT development.

---

## Recommendations for Future Cycles
- **Focus on Practical Implementation**: Allocate more time for hands-on practice to ensure a deeper understanding of the concepts.
- **Code Understanding**: Encourage students to fully understand the code they are working with, rather than just copying and pasting.

---

## Acknowledgment
We would like to thank all the trainers, especially **Eng. Mohamed Hatem**, for their guidance and support throughout the project. Their assistance was invaluable in overcoming the challenges we faced.

---

## Project Resources
-for testing vedio and presentation
-https://drive.google.com/drive/u/0/folders/1t-P63PjjkenXoegNHLQ2ODL_V9Et0ApU

---

**Note**: This project was developed as part of the **IoT Training Program** under the guidance of **Eng. Mohamed Hatem Abdulkader**.
