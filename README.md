# Info
This is an implementation of the OMRON FINS protocol.
-Labview 2019
-PLC OMRON CP1L
-PLC OMRON CX1 Programmer 9.7

# Examples
The example 1 (as seen in the image below) defines a means to:
1. Connect to a devices (TCP/IP)
2. Setup FINS communication (Handshake, exchange Nodes addresses)
3. Perform a FINS command (CMD) memory area read.

![alt text](https://github.com/jmor2000/LV-OMRON-FINS/blob/main/IMGs/Example%201.JPG?raw=true)

The device (e.g. PLC) will need to be be configure to accept FINS communition.
Please take note of the FINS node address (SD1)
In the example, the FINS header is automatically updated with client/server nodes.
This example can be modified to incorporate a wide range of other FINS commands, for reference please refere to "FINS Commands REFERENCE MANUAL" page 14 (2-1 Command List).

![alt text](https://github.com/jmor2000/LV-OMRON-FINS/blob/main/IMGs/PLC%20FINS%201.JPG?raw=true)

![alt text](https://github.com/jmor2000/LV-OMRON-FINS/blob/main/IMGs/PLC%20FINS%202.JPG?raw=true)

# Referencecs:
- Key to FINS communication, is identifying Destination Addresses (DA1) and Source Addresses (SA1)
"SYSMAC CS/CJ/CP Series Communications Commands REFERENCE MANUAL" page 36 (3-4-2 Addresses in FINS Commands)
"SYSMAC CS/CJ/CP Series Communications Commands REFERENCE MANUAL" page 7 (Host Link Communications Section 1-4)
- A full list of OMRON FINS Commands can be found in "FINS Commands REFERENCE MANUAL" page 14 (2-1 Command List).
