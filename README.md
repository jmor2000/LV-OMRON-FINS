# INFO
This is an implementation of the OMRON FINS protocol using Labview.

# Examples
The example 1 (as seen in the image below). Defines a means to:
1. Connect to a devices (TCP/IP)
2. Setup FINS communication (Handshake, exchange Nodes addresses)
3. Perform a FINS command (CMD) memory area read.
![alt text](https://github.com/jmor2000/LV-OMRON-FINS/blob/main/IMGs/Example%201.JPG?raw=true)

# Referencecs:
- Key to FINS communication, is identifying Destination Addresses (DA1) and Source Addresses (SA1)
"SYSMAC CS/CJ/CP Series Communications Commands REFERENCE MANUAL" page 36 (3-4-2 Addresses in FINS Commands)
- A full list of OMRON FINS Commands can be found in "FINS Commands REFERENCE MANUAL" page 14 (2-1 Command List).
