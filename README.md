# Network Programming Lab

## About the Project
Network Programming Lab is an open source project for learning and practice. 
The project mainly uses C to implement different network applications and understand how computers communicate through networks.

The current project focuses on TCP client and server programming. 
It includes client and server programs to demonstrate how a TCP connection can be created and how messages can be transferred between two computers. 
When I learn and implement more network programming knowledge, this project will keep being updated.

## Features

- A TCP client written in C
- A TCP server written in C
- TCP connection between client and server
- Server listening and accepting client connections
- Multithreading for handling client connections
- Sending and receiving time information through the network

## Installation instructions

The project requires a C compiler such as GCC and a Unix-like environment that supports socket programming.

Clone the repository:
```bash
git clone https://github.com/NAU-OSS/Network-Programming-Lab.git
cd Network-Programming-Lab
```
Compile the client:
```bash
gcc client.c -o client
```
Compile the server:
```bash
gcc server.c -o server -pthread
```

## Usage examples

Start the server first:
```
./server 23657
```
Then run the client in another terminal:
```
./client
```
The client creates a network connection and receives information from the server.  
Time information format:
```
20xx-MM-DD xx:xx:xx UTC *
```
The current example is designed to demonstrate basic TCP communication and time information transfer.

## Project Status

This project is currently under development. The first version focuses on basic TCP client and server programming. 
It is mainly for practicing network programming concepts and sharing simple examples with other developers. 
It helps learners better understand network connections and transfers.

## Contributing

Contributions are welcome. Developers can report bugs, suggest new network programming examples, improve documentation, or contribute code.

Please read CONTRIBUTING.md for contribution instructions.

## License

This project uses the MIT License. See license.md for more information.

## Contact

Questions, bug reports, and feature suggestions can be submitted through GitHub Issues in this repository.

Project repository:  
https://github.com/NAU-OSS/Network-Programming-Lab
