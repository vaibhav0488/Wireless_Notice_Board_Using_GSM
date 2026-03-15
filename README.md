# Wireless Notice Board Using GSM


This project implements a Wireless Notice Board system using GSM technology, which allows users to remotely send messages to an electronic display board using SMS. The system receives messages through a GSM module and displays them on a notice board without requiring any wired communication.

The primary goal of this project is to demonstrate how wireless communication can be integrated with embedded systems to create a remote information display system. It eliminates the need for manual updates on notice boards and allows instant message updates from any location using a mobile phone.

The system is built using a microcontroller that communicates with a GSM module through serial communication. When a user sends an SMS to the GSM module, the microcontroller reads the message, processes it, and displays the content on the connected display device.

Key Features

Wireless notice board message update using SMS

GSM-based remote communication

Automatic message reception and display

Serial communication between microcontroller and GSM module

Real-time display of received messages

Reduced manual effort for updating notices

Technologies and Components Used

Microcontroller-based embedded system

GSM communication module

Serial communication (UART)

Embedded C programming

Display module (LCD or LED display)

Power supply and interfacing circuits

Working Principle

A user sends a message via SMS to the GSM module attached to the system.

The GSM module receives the SMS using the cellular network.

The microcontroller reads the message using serial communication.

The received message is processed and displayed on the notice board.

Applications

College and university notice boards

Railway stations and bus terminals

Corporate offices

Public information display systems

Event announcements
