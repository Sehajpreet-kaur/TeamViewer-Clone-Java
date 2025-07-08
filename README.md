# TeamViewer-Clone-Java

A Java-based remote desktop application that mimics core features of TeamViewer. It enables users to securely connect to, view, and control other systems via an intuitive graphical interface—ideal for remote support, system control, and file access.

---

## Features

- Secure user registration and login with OTP-based email verification
- Remote screen sharing and viewing via IP address
- System-level control: Shutdown, Restart, Sleep
- Real-time messaging between connected systems
- Remote file access and downloading from drives
- View detailed system configuration of remote machine

---

## Application Flow

### Step 1: Server Control
- Start/Stop the server
- Launch the TeamViewer interface

### Step 2: User Authentication
- Sign Up: Enter name, email, password, phone number
- OTP Verification: Submit received OTP for confirmation
- Login: Use credentials to log in after registration

### Step 3: Dashboard
- Choose between:
  - **Share Screen** – View your local IP for others to connect
  - **Get Screen** – Input a remote IP to connect to another system

### Step 4: Remote Connection
- When sharing, your IP is shown to others
- When getting, input the IP of the device to control

### Step 5: Remote Control Panel
Once connected, you can:
- Shutdown, Restart, or Sleep the remote system
- Send text messages to the connected user
- View system configuration of the remote device
- Browse remote drives and download files as needed

---

## GUI Walkthrough

- Server Panel: Controls to Start, Stop, and Launch Viewer
- Sign-Up/Login Screens: User-friendly forms for registration and login
- OTP Verification: Input screen to validate email identity
- Dashboard: Choose to share or get screen access
- Screen Connection Panels:
  - Show IP to share
  - Enter IP to connect
- Remote Control Interface:
  - Buttons: Shutdown, Restart, Sleep, Send Message, View Config, View Drives
- File Manager:
  - Browse connected system drives
  - Select and download files

---

## Dependencies & Requirements

To run this project, ensure the following dependencies and tools are available:

### Software Requirements
- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)
- Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans)

### Libraries/Frameworks Used
- **Swing/AWT** (for GUI interface) – comes with JDK
- **Java Socket Programming** – built into Java SE for network communication

---

## Summary

This project offers a functional prototype of a remote desktop application using Java. With a focus on simplicity and essential features—such as screen sharing, user authentication, and system control—it is a compact alternative for remote collaboration and support needs.

