# Smart_switch
# Smart Switch Project

## Overview
The Smart Switch project is an IoT-based home automation system that allows users to control electrical appliances remotely using an ESP32 microcontroller. It supports both web-based control and manual operation through a physical switch.

## Features
- Remote control of lights or appliances via a web interface
- Manual operation using a physical switch
- ESP32-based IoT integration
- Two-channel relay for controlling multiple devices
- Real-time status updates

## Components Used
- **ESP32** – Microcontroller for IoT functionality
- **2-Channel Relay Module** – To control AC appliances
- **Bulb** – For demonstration purposes
- **Switch** – For manual control
- **Power Supply** – 5V or 3.3V for ESP32

## Software & Tools
- **Arduino IDE** – For programming the ESP32
- **Wi-Fi Network** – For remote control functionality
- **Web Server (ESP32)** – Handles communication with the web interface
- **HTML, CSS, JavaScript** – For designing the web UI

## Installation & Setup
1. **ESP32 Setup:**
   - Install the ESP32 board package in Arduino IDE
   - Connect the ESP32 to your system via USB
   - Install necessary libraries (`WiFi`, `ESPAsyncWebServer`, etc.)
   
2. **Wiring:**
   - Connect the relay module to the ESP32
   - Connect the switch in parallel with the relay module
   - Ensure proper connections for AC devices

3. **Code Upload:**
   - Modify Wi-Fi credentials in the Arduino sketch
   - Upload the code to ESP32 using Arduino IDE

4. **Web Interface:**
   - ESP32 hosts a local web server
   - Users can access it via the assigned IP address

## Usage
- Open the web interface using a browser
- Toggle the switch to turn appliances ON/OFF
- Use the physical switch for manual control
- Monitor real-time status from the web interface

## Future Enhancements
- Integration with voice assistants (Google Assistant, Alexa)
- Mobile app control using Flutter
- Power consumption monitoring
- Multi-device support

## License
This project is open-source and available for modification and improvement. Feel free to contribute!



