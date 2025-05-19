# Travel-And-Tourism-Management-System-in-java-programming-langue

# Travel Management System

A Java Swing-based desktop application for managing travel and tourism operations. The system includes functionalities like personal details management, hotel and package booking, and integration with system utilities like Calculator and Notepad.

## 💻 Features

- Add, View, Update, Delete Personal Details
- Check, Book, and View Travel Packages
- View Hotels and Book Hotel Rooms
- View Booked Hotels
- Explore Destinations
- Payment System (UI)
- System Utilities:
  - Open Calculator
  - Open Notepad
- About Section

## 🛠️ Technologies Used

- Java
- Java Swing & AWT for GUI
- Event Handling

## 📂 Project Structure
travel.management.system/
├── Dashboard.java
├── AddCustomer.java
├── ViewCustomer.java
├── UpdateCustomer.java
├── DeleteDetails.java
├── CheckPackage.java
├── BookPackage.java
├── ViewPackage.java
├── CheckHotels.java
├── BookHotel.java
├── ViewBookedHotel.java
├── Destinations.java
├── Payment.java
├── About.java
└── icons/
├── dashboard.png
└── home.jpg

markdown
Copy
Edit

## 🖼️ Dashboard Overview

- Left Sidebar: Buttons for all features
- Top Panel: Application heading
- Main Panel: Background image with overlay title
- Scrollable Navigation Panel to handle many options

## 🧾 How to Run

1. Make sure you have **JDK 8 or later** installed.
2. Place all `.java` files in the same package (`travel.management.system`).
3. Ensure the `icons` folder contains:
   - `dashboard.png`
   - `home.jpg`
4. Compile and run the `Dashboard` class:

```bash
javac travel/management/system/Dashboard.java
java travel.management.system.Dashboard
ℹ️ Tip: Use an IDE like IntelliJ IDEA or Eclipse for easier GUI management and error handling.

⚠️ Note
This project uses Runtime.getRuntime().exec() to open Calculator and Notepad.

These work on Windows OS only. You may need to modify the commands for other operating systems.

👤 Author
Hasnain Haider
Haseeb Anwar
SAP ID: 56626
sAP ID : 56720
📜 License
This project is open-source and intended for educational purposes only.
