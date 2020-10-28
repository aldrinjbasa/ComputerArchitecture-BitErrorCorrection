# ComputerArchitecture-BitErrorCorrection
Built on LogicWorks 5. The purpose of this project was to simulate bit-data transmission errors onto main memory and detecting them using parity bits.

Data Transmittor.clf - this file is the 13-bits that will be sent to the main memory. We use this
   to simulate the errors that occur during a real world transmission of data.

ECC Detector.clf - this file checks if there was an error that was transmitted from the 13-bit data
   transmittor. It will output various parts to give user feedback if an error had occurred during
   transmission.

ECC.clf - this file is the 8-bit generator that takes in a hexadecimal value to be checked. In addition,
   this circuit is built to generate the parity bits alongside the data bits that are to be used.
   
FullCircuitDiagram.cct - final diagram utilizing symbols of above circuits to simulate data transmission errors
