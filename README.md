# Synchronous_FIFO
First In First Out (FIFO) is used for the purpose of synchronization when the incoming data experiences same/ different clock domains within a system.
Depth of FIFO: The number of slots or rows in FIFO is called the depth of the FIFO.
Width of FIFO: The number of bits that can be stored in each slot or row is called the width of the FIFO.

A synchronous FIFO (First-In, First-Out) in Verilog utilizes a single clock for both write and read operations. The core components include a memory array, write and read pointers, and logic to determine full and empty conditions.

