# Motion Detection using Client and Server Modules

This project demonstrates motion detection using Arduino Uno and different ESP NodeMCU modules. The system consists of two NodeMCU devices—one acting as the client and the other as the server. The client module is responsible for detecting motion using a sensor, while the server module receives the motion alerts wirelessly and triggers appropriate actions.

## Objective

The primary objective of this project is to implement a wireless motion detection system using Arduino Uno and NodeMCU modules. The system aims to achieve the following goals:

- Detect motion using a sensor connected to the client NodeMCU module.
- Establish wireless communication between the client and server NodeMCU modules.
- Transmit motion detection alerts from the client to the server module.
- Trigger appropriate actions on the server module upon receiving motion alerts.

## Components

To replicate or further explore the project, you will need the following components:

- Arduino Uno board
- ESP NodeMCU modules (2 units)
- Motion sensor (e.g., PIR sensor)
- Jumper wires
- Breadboard (optional, for prototyping)
- USB cables for power and programming

## Installation and Setup

Follow these steps to set up the motion detection system:

1. Connect the client NodeMCU module to the motion sensor and Arduino Uno using jumper wires, ensuring proper wiring and connection.

2. Connect the server NodeMCU module to the Arduino Uno using jumper wires.

3. Connect the Arduino Uno board to your computer using a USB cable.

4. Install the Arduino IDE on your computer if you haven't already.

5. Install the required libraries for ESP NodeMCU by going to **Sketch > Include Library > Manage Libraries** in the Arduino IDE. Search for and install the necessary libraries for NodeMCU and ESP8266.

6. Open the Arduino IDE and select the appropriate board and port settings for Arduino Uno and NodeMCU modules.

7. Open the **client_module.ino** file and upload the code to the client NodeMCU module.

8. Open the **server_module.ino** file and upload the code to the server NodeMCU module.

9. Disconnect the NodeMCU modules from the computer and power them using appropriate power sources.

## Usage

1. Place the client NodeMCU module in the desired location for motion detection, ensuring it has a clear view of the area to monitor.

2. Power on the client and server modules. The client module will start detecting motion using the connected sensor.

3. Whenever motion is detected, the client module will wirelessly transmit a motion alert to the server module.

4. The server module will receive the motion alert and trigger appropriate actions, such as activating an alarm, sending a notification, or controlling other connected devices.

## Customization

Feel free to customize and extend the functionality of the motion detection system. You can modify the code to incorporate additional sensors, implement different actions upon motion detection, or integrate with other IoT platforms for enhanced functionality.

## Contributing

Contributions to this project are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

- This project utilizes the Arduino Uno board and ESP NodeMCU modules for wireless communication and motion detection.
- We appreciate the contributions of the open-source community, whose resources and knowledge have been valuable throughout this project.

## Contact

If you have any questions or inquiries, please feel free to contact the project maintainer:

- Sarfraz Nawaz
- Email: informsarfu@gmail.com
- GitHub: https://github.com/informsarfu
