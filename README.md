#### Project 2: Chord Protocol Implementation and Network Simulation

### Overview

Project 2 focuses on simulating a Chord peer-to-peer (P2P) network within the Akka.NET framework using F#. The simulation includes implementing a Chord network, node joining, stabilization, efficient routing, and calculating the average hops for message delivery.

### Key Features

- **Chord Ring Formation**: Arranges all nodes into a ring structure, updating whenever nodes join or leave the network.
- **Finger Table Management**: Implements finger tables for each node to optimize routing and lookup times.
- **Node Joining and Stabilization**: Supports node joining and implements stabilization to maintain ring integrity.
- **Efficient Routing**: Utilizes finger tables for efficient routing, significantly reducing the average hops required for message delivery.

### Running the Simulation

Refer to the project directory for instructions on compiling and running the Chord network simulation. Execute the provided commands to initiate the simulation with the desired parameters.

To run the Chord network simulation, execute the following command:

```
dotnet fsi final.fsx <no_of_Nodes> <no_of_Requests>
```
