# Real-Time Chat Application

## Overview
The Real-Time Chat Application is a Spring Boot-based, WebSocket-powered chat system that allows users to send and receive messages in real-time. The front-end uses HTML, Bootstrap, and JavaScript to create an intuitive and responsive chat interface, while the back-end leverages Spring Boot to handle WebSocket connections, message routing, and broadcasting.

## Technologies Used:
- **Spring Boot**: Backend framework to set up REST APIs and WebSocket messaging.
- **Spring WebSocket**: Handles WebSocket connections and message brokering.
- **SockJS**: WebSocket fallback used for client compatibility.
- **STOMP**: Protocol used for message communication over WebSocket.
- **Bootstrap**: CSS framework for styling and responsive layout.
- **HTML5**: Front-end structure and design.
- **JavaScript**: For handling real-time message sending and receiving.
- **Lombok**: Used to reduce boilerplate code and simplify Java classes.

## Features:
- **Real-Time Messaging**: Messages are instantly broadcasted to all connected clients.
- **Chat Bubble Styling**: Messages appear as styled chat bubbles with sender's name in gray.
- **Responsive UI**: Fully responsive design that adapts to different screen sizes.
- **Auto-scroll**: Chat area automatically scrolls to the latest message.
- **Enter Key to Send**: Users can press `Enter` to send messages without clicking the Send button.
- **Bootstrap Integration**: Built with Bootstrap 5 for a modern and clean look.

##

## Directory Structure:

- **`src/main/java/com/chat/app/`**:
  - **`AppApplication.java`**: Main entry point of the Spring Boot application.
  - **`config/`**: 
    - **`WebSocketConfig.java`**: Configuration class for WebSocket setup.
  - **`controller/`**: 
    - **`ChatController.java`**: Handles WebSocket message routing.
  - **`model/`**: 
    - **`ChatMessage.java`**: Represents a chat message.

- **`src/main/resources/`**:
  - **`application.properties`**: Configuration file with server settings.
  - **`templates/`**:
    - **`chat.html`**: HTML template for the chat user interface.

## Explanation of Folder Contents:

- **`com.chat.app`**: 
  - **`controller`**: Handles incoming WebSocket messages and routing.
  - **`model`**: Contains the `ChatMessage` class to represent chat messages.
  - **`config`**: Contains configurations for WebSocket endpoints.

- **`src/main/resources/`**:
  - **`application.properties`**: Application-wide configurations.
  - **`templates/`**: Stores the HTML template for the chat UI.



## Getting Started

### Prerequisites
- **Java Development Kit (JDK)** 11 or higher.
- **IDE**: IntelliJ IDEA, Eclipse, or any other preferred Java IDE.
- **Build Tool**: Maven or Gradle.
- **Web Browser**: Any modern web browser (Google Chrome, Firefox, Edge).

### Demo Video 


https://github.com/user-attachments/assets/1f918f79-c699-46ed-ba5c-877fea87de6d



### Clone the Repository


   ```bash
   git clone https://github.com/chinmoypaul8897/Real-Time-Chat-Application.git
   cd Real-Time-Chat-Application


