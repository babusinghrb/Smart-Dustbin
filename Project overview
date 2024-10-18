# Smart Dustbin using IoT

## Methodology and Working

The **Smart Dustbin** is an IoT-based system designed to enhance waste management by detecting waste levels and notifying municipal authorities when the bin is full. The system incorporates sensors, microcontrollers, and cloud technology to automate and optimize the waste disposal process.

### 1. Block Diagram

The block diagram of the system demonstrates the interaction between the following components:

- **Ultrasonic Sensor (HC-SR04)**: Measures the fill level of the dustbin.
- **ESP32 Microcontroller**: Handles data processing and communication with the cloud.
- **Servo Motor**: Automatically opens and closes the lid of the dustbin.
- **Wi-Fi Module**: Connects the ESP32 to Firebase for real-time data monitoring.
- **LED Indicator**: Lights up when the dustbin is full.

### 2. Working Mechanism

1. **Fill Level Detection**: 
   - An **ultrasonic sensor** placed inside the dustbin measures the level of waste. The sensor works by emitting ultrasonic waves and calculating the time it takes for the waves to reflect back from the surface of the waste.
   - Another ultrasonic sensor is placed near the dustbin's lid to detect the presence of a user.
   
2. **Lid Control**:
   - When the sensor detects a user approaching, the **servo motor** rotates to open the lid. After waste is disposed of, the lid automatically closes.

3. **Real-Time Data Transmission**:
   - The data collected by the sensors is transmitted via the **ESP32 microcontroller** to **Google Firebase** using the **Wi-Fi module**. This allows for remote monitoring of the fill level of the dustbin.

4. **Alert Mechanism**:
   - When the dustbin reaches a certain fill level (e.g., 90% full), the system triggers an alert. This notification is sent to municipal authorities or waste management teams, ensuring timely collection.
   - Additionally, an **LED indicator** turns on when the dustbin is full.

5. **Cloud and Web Monitoring**:
   - The data from Firebase is visualized on a **webpage**, which can be accessed by anyone with the appropriate link. This page displays real-time information about the status of the dustbin.

### 3. Algorithm

The following is the simplified algorithm for the smart dustbin system:

1. Start
2. Measure the fill level of the dustbin using **Ultrasonic Sensor 1**.
3. If the fill level is within the threshold:
    - Turn on **Ultrasonic Sensor 2** to detect user presence.
4. If a user is detected:
    - Open the lid using the **servo motor**.
    - Wait for the user to dispose of the waste.
    - Close the lid after the waste is disposed.
5. If the fill level exceeds the maximum capacity:
    - Turn on the **LED indicator**.
    - Send a notification to the cloud (Firebase).
6. Repeat the process.

### 4. Flowchart

The flowchart below summarizes the working of the system:

1. Detect the waste level using the **ultrasonic sensor**.
2. If the waste level is within the threshold, detect the user's presence.
3. Open the lid using the **servo motor** when the user is detected.
4. Close the lid after the user disposes of the waste.
5. When the waste level reaches the maximum limit:
    - Notify the authorities via **Firebase**.
    - Turn on the **LED** to indicate that the bin is full.

### 5. Simulation Results

The system outputs data on:

- **Serial Monitor**: Displays real-time information about the waste level.
- **Firebase Cloud**: Stores and visualizes the data.
- **Webpage**: Shows the fill level of multiple dustbins in real-time.

### 6. Future Enhancements

- **Waste Segregation**: Implement AI-based waste sorting for more efficient waste management.
- **Solar Power**: Make the system energy-efficient by adding solar panels.
- **Mobile App Integration**: Provide notifications to users via mobile apps.

## Conclusion

This **Smart Dustbin** system provides an efficient and automated solution for waste management. It reduces the need for manual monitoring and ensures timely disposal, promoting a cleaner environment. The system is scalable and can be implemented in smart cities to optimize waste collection processes.
