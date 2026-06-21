# RFID Based Anti-Theft Intelligent Shopping System

# Overview

The RFID Based Anti-Theft Intelligent Shopping Trolley System is an embedded system project developed using the LPC2129 ARM7 microcontroller and RFID technology. The system is designed to provide automatic billing and improve security in supermarkets. It reduces manual billing effort, minimizes waiting time, and prevents unauthorized exit of products by incorporating an anti-theft mechanism.

# Technologies Used

* Embedded C
* LPC2124 ARM7 Microcontroller
* RFID Technology
* UART Communication
* 16×2 LCD Interface
* Interrupt Handling

# Working

* Each product is attached with an RFID tag containing a unique identification number.
* The EM-18 RFID reader reads the tag and sends the tag ID to the LPC2124 microcontroller through UART communication.
* The user can add or remove products using switches, and the corresponding bill amount is updated automatically.
* The total bill amount can be viewed on the LCD display.
* After payment, a payment RFID tag is scanned to confirm the transaction.
* During exit, the system verifies the payment status.
* If the payment is completed, the customer is allowed to exit and the system resets for the next user.
* If the customer attempts to exit without payment, the system detects theft and activates the buzzer as an alert.


