# J1939-22 (CAN-FD) API

This LabVIEW API implements the **J1939-22** CAN-FD Transport Protocol specification using NI XNET.  **J1939-22** was created as a successor to *J1939-21* to take advantage of the increased bandwidth provided by CAN-FD and to support Multi-PG (Protocol Groups) within a single frame.

NI XNET only provides a mechanism for a single PG per frame, but the **J1939-22** specification allows for multiple PGs (Multi-PG) per CAN frame.  This API was created to fill in the gaps left by NI XNET and to provide a complete **J1939-22** implementation ready for use.

This API was tested against the **J1939-17** specification which specifies the following settings.

* CAN-FD with BRS (Bit Rate Switch) enabled
* 500K Baud Arbitration Rate
* 2M Baud Data Rate
* Termination enabled (Rx & Tx)

# J1939-22 Database Editor

The **J1939-22** Database Editor allows the user to provide additional **J1939-22** specific configuration that is not included with the base NI-XNET Database Editor.  It uses the same ASAM FIBEX XML format to remain cross compatible with NI-XNET Database Editor.  It manages this by using the **MANUFACTURER-EXTENSION** tags within the FIBEX XML specification to extend the functionality while remaining backwards compatible.

**ASAM AE MCD-2 NET Field Bus Data Exchange Format 4.1.2**

# J1939-22 Example

TODO

How to run the provided example(s) 

Provide the loopback example in LabVIEW that was used to verify the software as an example that can be used to build from.

# Getting Started

## Minimum Software Versions

* NI LabVIEW 2021 SP1
* NI XNET 21.5

## Installation

TODO 

How to install and use J1939-22 Database Editor?

## Documentation

TODO

Where to find additional documentation?