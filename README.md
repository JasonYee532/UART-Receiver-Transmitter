# UART-Receiver-Transmitter
# This project implements the UART protocol on a Basys 3 FPGA Board

# Receiver
# Sent data to FPGA Board to be read by Putty
# Displayed ASCII code for characters on Board LEDS
# Implemented a state machine to switch between states
# Synced sampling rate with baudrate for accurate sampling

# Transmitter
# Sent data to PC from FPGA Board
# Debounced button for clean signals
# Sent signals for start, data, stop, and idle states
