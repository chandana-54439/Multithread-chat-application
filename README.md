Name:Chandana M S

Branch duration 4 weeks

Company name:CODTECH IT SOLUTIONS

Intern id:CT04DG799

Domain name:java

Mentor name:Neela santhosh kumar

Description:The Multithreaded Chat Application is a real-time messaging system developed using Java Sockets and Multithreading. This project simulates a client-server architecture where multiple users (clients) can join a shared chatroom, communicate with each other, and leave the chat — all through simple command-line terminals. The server listens for client requests and creates a new thread for every connected client, allowing many users to chat at the same time without interfering with each other. This asynchronous communication model demonstrates how scalable chat systems work behind the scenes.

In this system, the Server runs continuously, listening on a specified port for client connections. When a client connects, the server spawns a separate thread (using a ClientHandler) to manage communication with that user independently. This ensures that each client can send and receive messages in real time without waiting for others to finish. The server also broadcasts messages from one client to all others, enabling a true group chat experience.

The Client connects to the server using Java's Socket class, sends its name for identification, and can then send messages. Each message is read by the server and rebroadcast to all other clients. The client also uses a background thread to listen for incoming messages from the server, ensuring that user input and incoming messages are handled simultaneously. This shows how multithreading enables responsiveness in network-based applications.

The following tools and technologies were used for this project:

Programming Language: Java (JDK 17 or later) – for core logic and threading

IDE: Visual Studio Code – to write, compile, and run Java programs

Terminal/Command Prompt – to execute and test the chat application

Java Networking Library – for socket programming (Socket, ServerSocket)

Multithreading – using Java’s Thread class to handle multiple clients concurrently

Operating System: Windows – for development and execution

Compression Tool: Windows built-in zip or WinRAR – to bundle the project


This project is a foundational example of how network-based applications are built. It can be expanded to include GUI features using Java Swing or JavaFX, login systems, file sharing, or even database support for storing chat history. The design follows key computer science concepts like concurrency, inter-process communication, and event-driven programming.

Applications and Use Cases of this chat application include:

📚 Educational use: For learning how multithreading and socket programming work

🧪 Testing chat functionality before developing mobile or web-based chat apps

🧑‍💻 Local chat on LAN networks (like between classroom computers)

🧠 Foundation for building real-time communication tools (e.g., customer support systems, collaborative tools)

💬 Text-based chat for games or developer collaboration tools

OUTPUT
<img width="1819" height="185" alt="Image" src="https://github.com/user-attachments/assets/edfa0d0c-4e9f-4428-ac6b-4693e316c96b" />



