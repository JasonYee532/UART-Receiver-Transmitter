# UART-Receiver-Transmitter

This project implements the **UART protocol** on a **Basys 3 FPGA Board**. It allows the board to communicate with a PC using serial data through **PuTTY**.

---

## Receiver
- Receives data sent to the FPGA Board from a PC.
- Displays the **ASCII code** for received characters on the **board LEDs**.
- Implements a **state machine** to switch between **Idle, Start, Data, and Stop** states.
- Synchronizes the **sampling rate** with the baud rate for accurate bit detection.

---

## Transmitter
- Sends data from the FPGA Board to a PC.
- Uses a **debounced button** for clean signal input.
- Handles the **Start, Data, Stop, and Idle** states for proper UART transmission.

---
