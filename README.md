# RFID-Smart-Cart-Billing-System

Overview

The RFID Smart Cart Billing System is an Embedded Systems and Embedded Linux based project designed to automate shopping and billing processes in supermarkets.

The system uses RFID technology to identify products and automatically update the shopping cart, reducing checkout time and improving customer experience.

Features

- RFID based product identification
- Automatic product addition/removal
- Cart management
- Real-time bill calculation
- Inventory management
- UART communication between ARM7 and Linux
- LCD display support
- Cash and Digital payment options
- Stock update after purchase


Hardware Used

- ARM7 LPC2129
- RFID Reader (MFRC522)
- RFID Tags
- LCD 16x2
- UART Interface
- Power Supply Circuit


Software Used

- Embedded C
- Embedded Linux
- GCC Compiler
- Ubuntu Linux
- Git & GitHub

System Architecture

ARM7 LPC2129
↓ UART
Embedded Linux Application
↓
Inventory Database (stock.csv)

Project Flow

1. RFID card scanned
2. Product details sent to Linux
3. Product added to cart
4. Bill updated
5. Payment selected
6. Inventory updated
7. Bill generated


Folder Structure

```text
ARM_Firmware/
Linux_Application/
Circuit_Diagram/
Screenshots/
Documents/
```

Future Enhancements

- QR Payment Integration
- Cloud Database
- Mobile Application
- IoT Monitoring

Author

Baji Baba Kusumanchi

Embedded Systems Engineer
