#Chat App (using Socket programming)

## Overview

The Java Chat App is a simple chat application that allows users to communicate over a local network using client-server architecture. It utilizes socket programming for network communication and Swing for the graphical user interface (GUI).

## Features

- *Server-side:* The server is responsible for managing client connections, routing messages, and maintaining the chat history.

- *Client-side:* The client provides a user-friendly interface for users to connect to the server, send and receive messages, and view the chat history.

- *Socket Programming:* The application uses Java sockets for real-time communication between the client and server.

- *GUI with Swing:* The graphical user interface is built using Java Swing, providing a user-friendly and interactive chat experience.

## Prerequisites

- Java Development Kit (JDK) 8 or later
- A Java Integrated Development Environment (IDE) such as Eclipse or IntelliJ IDEA (optional but recommended)

## Getting Started

1. Clone this repository to your local machine.
2. Open the project in your Java IDE.

3. Build the project to compile the Java classes.

4. Start the server:

- Run the `Server` class to start the server application.

5. Start the client:

- Run the `Client` class to start the client application.
- Enter a username and connect to the server using the provided IP address and port.

6. Start chatting!

## Usage

- Launch the client application and connect to the server.
- Send messages in the chat input field and press "Enter" to send.
- View incoming messages from other clients in the chat area.
- Disconnect from the server by closing the client application.

## Configuration

- You can configure the server's IP address and port in the `Server` class.
- Adjust the client's IP address and port in the `Client` class to match the server's settings.