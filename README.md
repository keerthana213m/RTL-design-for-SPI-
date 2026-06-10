A Verilog HDL implementation of an SPI Master Controller featuring FSM-based control logic, serial data transmission, and functional verification through simulation.

File Description : 

1. About_SPI.pdf
Contains the theoretical background of the SPI (Serial Peripheral Interface) protocol.
Explains SPI architecture, communication process, timing diagrams, and signal descriptions.
Provides an understanding of how data is transferred between master and slave devices.

2. design_code_SPI.v
RTL implementation of the SPI Master Controller in Verilog HDL.
Generates SPI control signals such as:
SCLK (Serial Clock)
MOSI (Master Out Slave In)
SS (Slave Select)
Uses a Finite State Machine (FSM) to control data transmission.
Converts parallel input data into serial output data according to SPI protocol specifications.

3. Testbench_SPI.v
Verilog testbench developed for functional verification of the SPI Master.
Generates clock and reset signals.
Applies test vectors to validate SPI data transmission.
Monitors output signals and verifies correct operation of the design.
Supports waveform generation for debugging and analysis using GTKWave/ModelSim.
