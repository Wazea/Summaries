# OSI Model
- It stands for Open Systems Interconnection Model.
- It was published in 1984 by ISO.
- Conceptual framework that describes the functions of a networking system.
- The model has 7 different layers of abstraction.

# Physical Layer
- Concerned with electri-/optical transmiters.
- It can include information like voltage, pins, cabling and radio frequencies.
- Devices: Hubs, Switches, Routers, Cabling, etc.

# Data Link Layer
- Here is handled the node to node communication.
- The data is transmitted into frames.
- It can correct errors that occured at the physical layer.
- Encompasses two sub-layers:
  - Media Access Control (MAC): Flow control and multiplexing;
  - Logical Link Control (LLC): Flow and error control over the physical medium;

# Network Layer
- Receives frames and sends them to the intended destination.
- Identification is done by using logical addresses such as IP.
- Routers are doing the work here.

# Transport Layer
- Manages the delivery and error checking of data packets.
- It regulates the size, sequencing, and ultimately the transfer of data between systems and hosts.
 
# Session Layer
- Controls communication between multiple computers.
- Creates, manages and terminates connections between machines.

# Presentation Layer
- Formats or translates data for the application layer. 
- Handles the encryption and decryption required by the application layer.

# Application Layer
- Here is handled the interaction with the software application.
- The application layer identifies communication partners, resource availability, and synchronizes communication.