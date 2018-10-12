# devops-networkprotocols
**Transmission Control Protocol/Internet Protocol(TCP/IP)** suite is designed to make a nework robust and the data integrity won't be compromised under malicious attackts. It allows to contruct big networks but requires little central management.  It has four layers - Application, Host to Host, Internet and Network Access.

**Open Systems Interconnection Basic Reference Model(OSI Model)** is an abstract  description for networking protocol design, it is develped as an effort to standerdize networking. It has seven layers- Application, Presentation, Session, Transport, Network, Datalink and Physical layer.

**TCP/IP(Application) or OSI(Application, Presentation, Session)**: This layer deals with representation, encoding and dialog control issues.

**TCP/IP(Host-to-Host) or OSI(Transport)**: This layer responsibilities include application data segmentation, transmission reliability, flow and error control.

**TCP/IP(Internet) or OSI(Network)**: It's purpose is to route packets to their destination independent of the path taken.

**TCP/IP(Network Access) or OSI(Data Link and Physical)**: It deals with all the physical issues concerning data termination on network media.


**Protocols:**

**TCP(Transmission Control Protocol)** is 'connection oriented' protocol.TCP tracks all data sent and also acknowledgement is required. TCP is considered  as reliable protocol because of acknowledgements. It ensures no data is lost and It can even manage transmissions to attempt to reduce congestion.

**UDP(User Datagram Protocol)** is 'connection-less' protocol. It does not use acknowledgements at all that's why it is not a reliable protocol. UDP is used where few lost datagrames do no matter.It is light weight protocol and it is used in routing protocol updates and server availability, one to many multicast applications and streaming applications.
