# Wireless Notice Board Using GSM


This project implements a Wireless Notice Board system using GSM technology, which allows users to remotely send messages to an electronic display board using SMS. The system receives messages through a GSM module and displays them on a notice board without requiring any wired communication.

The primary goal of this project is to demonstrate how wireless communication can be integrated with embedded systems to create a remote information display system. It eliminates the need for manual updates on notice boards and allows instant message updates from any location using a mobile phone.

The system is built using a microcontroller that communicates with a GSM module through serial communication. When a user sends an SMS to the GSM module, the microcontroller reads the message, processes it, and displays the content on the connected display device.

Key Features

1. Wireless notice board message update using SM
2. GSM-based remote communication
3. Automatic message reception and display
4. Serial communication between microcontroller and GSM module
5. Real-time display of received messages
6. Reduced manual effort for updating notices

Technologies and Components Used

1. Microcontroller-based embedded system
2. GSM communication module
3. Serial communication (UART)
4. Embedded C programming
5. Display module (LCD or LED display)
6. Power supply and interfacing circuits

Working Principle

1. A user sends a message via SMS to the GSM module attached to the system.
2. The GSM module receives the SMS using the cellular network.
3. The microcontroller reads the message using serial communication.
4. The received message is processed and displayed on the notice board.

Applications

1. College and university notice boards
2. Railway stations and bus terminals
3. Corporate offices
4. Public information display systems
5. Event announcements
