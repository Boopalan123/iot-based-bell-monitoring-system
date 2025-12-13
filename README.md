# iot-based-bell-nonitoring-system
Manual and conventional electric bell systems used in colleges and institutions are inefficient, error-prone, and lack flexibility. They depend on human intervention or fixed electromechanical timers, making schedule modification difficult and unreliable. With increasing demand for automation, remote control, and real-time monitoring, a smarter bell system is required.

This project presents the design and implementation of an IoT-based Automatic Bell System using ESP32, integrating GPS, RTC, relay module, OLED display, and a web interface. The system automates bell ringing according to predefined schedules while allowing remote configuration and monitoring through a webpage.

The ESP32 acts as the central controller, offering built-in Wi-Fi for IoT connectivity. A GPS module provides accurate real-time location and time synchronization, eliminating dependency on manual time setting and ensuring uniform operation across multiple installations. An RTC module maintains time continuity during network or power interruptions. The relay module safely controls the high-voltage bell circuit, while the OLED display provides real-time system status, current time, and bell activity locally.

The bell schedules are managed through a web-based interface, enabling administrators to add, modify, or delete bell timings remotely from any device connected to the network. This approach improves reliability, scalability, and ease of maintenance compared to traditional bell systems.

The proposed system is suitable for educational institutions, offices, factories, and public facilities, where precise time management, centralized control, and automation are critical. By combining embedded systems with IoT technology, the system reduces manual effort, minimizes scheduling errors, and provides a flexible and future-ready bell management solution.
