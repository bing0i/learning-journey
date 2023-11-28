- [Internet](#internet)
  - [Terminologies](#terminologies)
  - [Basic concepts](#basic-concepts)
  - [Emerging Trends and Technologies](#emerging-trends-and-technologies)
- [Reference](#reference)

# Internet

## Terminologies

- Packet: A small unit of data that is transmitted over the internet.
- Router: A device that directs packets of data between different networks.
- IP Address: A unique identifier assigned to each device on a network, used to route data to the correct destination.
- Domain Name: A human-readable name that is used to identify a website, such as google.com.
- DNS: The Domain Name System is responsible for translating domain names into IP addresses.
- FTP: File Transfer Protocol
- SMTP:b Simple Mail Transfer Protocol
- HTTP: The Hypertext Transfer Protocol is used to transfer data between a client (such as a web browser) and a server (such as a website).
- HTTPS: An encrypted version of HTTP that is used to provide secure communication between a client and server.
- SSL/TLS: The Secure Sockets Layer and Transport Layer Security protocols are used to provide secure communication over the internet.
  - Certificates: SSL/TLS certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party (a Certificate Authority) to verify their authenticity.
  - Handshake: During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.
  - Encryption: Once the secure connection is established, data is encrypted using the agreed-upon algorithm and can be transmitted securely between the client and server.
- TCP/IP:
  - Ports: Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.
  - Sockets: A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
  - Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection.
  - Data transfer: Once a connection is established, data can be transferred between the applications running on each device. Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.

## Basic concepts

- The internet is a network of networks.
- The internet was developed in the late 1960s by the United States Department of Defense as a means of creating a decentralized communication network that could withstand a nuclear attack.
- The core of the internet is a global network of interconnected routers, which are responsible for directing traffic between different devices and systems. When you send data over the internet, it is broken up into small packets that are sent from your device to a router. The router examines the packet and forwards it to the next router in the path towards its destination. This process continues until the packet reaches its final destination.

## Emerging Trends and Technologies

- 5G: 5G is the latest generation of mobile network technology, offering faster speeds, lower latency, and greater capacity than previous generations. It is expected to enable new use cases and applications, such as autonomous vehicles and remote surgery.
- Internet of Things (IoT): IoT refers to the network of physical devices, vehicles, home appliances, and other objects that are connected to the internet and can exchange data. As IoT continues to grow, it is expected to revolutionize industries such as healthcare, transportation, and manufacturing.
- Artificial Intelligence (AI): AI technologies such as machine learning and natural language processing are already being used to power a wide range of applications and services, from voice assistants to fraud detection. As AI continues to advance, it is expected to enable new use cases and transform industries such as healthcare, finance, and education.
- Blockchain: Blockchain is a distributed ledger technology that enables secure, decentralized transactions. It is being used to power a wide range of applications, from cryptocurrency to supply chain management.
- Edge computing: Edge computing refers to the processing and storage of data at the edge of the network, rather than in centralized data centers. It is expected to enable new use cases and applications, such as real-time analytics and low-latency applications.

# Reference

- [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work)
