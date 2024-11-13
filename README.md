# Single_Port_RAM_AB

Single_Port_RAM_AB is a synchronous single-port RAM (Random Access Memory) module designed for efficient data storage and retrieval in digital systems. This module allows for simultaneous read and write operations, controlled by specific input signals, making it suitable for various applications in FPGA and ASIC designs.

Key Features:
Single-Port Access: The RAM supports a single access port for both reading and writing, simplifying the design and control logic.

Synchronous Operation: All memory operations (read/write) are synchronized to a clock signal, ensuring consistent timing and predictable behavior.

Configurable Parameters:

Address Width: The number of bits used for addressing memory locations, allowing for a configurable depth of the RAM.
Data Width: The size of the data bus, enabling storage of data in varying bit widths.
Depth: The total number of memory locations available for storage, defined by the address width.
Control Signals:

Chip Select (CS): Activates the RAM module for read/write operations.
Write Enable (WE): Determines whether the operation is a write (when high) or a read (when low).
Output Enable (OE): Controls whether the data output is active, allowing for data to be read from the RAM.
High Impedance State: When not in use, the data output can be tri-stated (high impedance), preventing bus contention in multi-device systems.

Applications:
Data Buffers: Used in systems requiring temporary storage of data before processing.
Signal Processing: Suitable for applications in digital signal processing where quick access to stored data is essential.
Microcontroller Memory: Acts as a data storage solution in microcontrollers and embedded systems.
