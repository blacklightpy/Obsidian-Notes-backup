Devices are connected together using ports and connectors to transfer information. Information can generally be transmitted in parallel and serial formats, or even in a hybrid of both.

Parallel interfaces transfer data through multiple channels simultaneously to send all information at once. Serial interfaces transfer all information through a single channel to the receiver. Due to design fundamentals and scalability, serial interfaces are generally the faster of both choices nowadays.

> [!NOTE] Title
> I should make a distinction between terms here:
> - Port: Virtual Interfaces (Logical Layer)
> - Female Connector: Physical Port (Physical Layer)
> - Male Connector: Physical Connector (Physical Layer)
> - Electrical Interface: Voltage Levels (Physical Layer)

# Design Terminology
- Pitch - Center-to-center distance between two pins or terminals
# Parallel Ports
- PATA
- DB-25 (Legacy Printers) (D and B stand for size)
- VGA
# Serial Ports

- SATA
- DE-9 (Electrical Interface: RS-232) (D and E stand for size)
- RJ45 (Electrical Interface: RS-232) / Console Cable / Rollover Cable (Ethernet is not RS-232 at the electrical level)
	- It's a null-modem (not needing modem; i.e. used to connect two Data Terminal Equipments (DTEs) directly) cable used to connect a computer's terminal to another device's console port
	- Typically blue in colour
	- Usually RJ45 to DE-9, but adapters can be used to connect to other physical ports
	- It reverses pinouts from one end to another, and hence is called a rollover cable
	- Any two RS-232 devices can be connected using a rollover cable paired with connectors
		- Because we connect TX to RX on each DTE
		- RS-232 normally expects a DTE to be connected to a DCE (Data Circuit-Terminating Equipment), not two DTEs directly
- Universal Serial Bus
- MIPI CSI
- MIPI DSI

# Terminiology
## Physical
- Port
- Socket
- Connector
- Plug
- Jack
- Header (aka Pin Headers / DuPont Connectors / Berg Connectors)
## Logical
- Port
- Socket