This project contains the design of a solar power optimizer.

The project was designed in KiCad, and the files are provided and can be edited to the users demands.

The project has generic values for R1, R2, R3, and R4 because they are intended to be chosen by the user depending on the voltage of the system.

Standard divider sizes are shown below:
  48V OCV: R1 = 40kOhm, R2 = 7500Ohm, R3 = 1000Ohm, R4 = 2000Ohm
  R1 and R2 must be rated for at least 1/8 Watt.
  R3 and R4 must be rated for at least 1 Watt.

  24V OCV: R1 = 16kOhm, R2 = 2000Ohm, R3 = Short, R4 = Open
  R1 and R2 must be rated for at least 1/8 Watt

  20V OCV: R1 = 12500, R2 = 7500, R3 = Short, R4 = Open

  500V OCV: R1 = 430K, R2 = 8000, R4 = 2000
            There are 3 slots for R3 (labelled R3_P1, R3_P2, R3_P3) which are in parallel
            Two of these should be a 7W 50K resistor in parallel with a 5W 62K Resistor
            The third slot should be one 5W 62K resistor
            

Production files are aslo included, the zip file and BOM are formatted for JLCPCB manufacturing and assembly.

If another software is used, these may need to be altered.


ORDERING INSRUCTIONS:
  Navigate to SolarOptimizer Git Upload\production and download SolarOptimizer3.0.zip

  This file can be uploaded directly to a PCB manufacturer and ordered
