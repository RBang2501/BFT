# BFT
Fault-Tolerant Agreement Protocol Simulation
This project is a simulation of a fault-tolerant agreement protocol, written in Python. The goal of this project is to create a system where a set of autonomous machines move on the streets of a city and try to agree on the next action to take. The protocol is designed to be fault-tolerant, meaning that even if some of the machines are faulty, the remaining machines can still reach consensus.

Implementation
The protocol is implemented using object-oriented programming (OOP) principles and multithreading. The code is organized into classes, with the Game class handling the simulation of the phases, and the Machine class serving as the base class for all machines in the simulation. The use of OOP allows for a modular and extensible codebase, with each class and method having a clear responsibility and purpose.

The protocol is executed using a multi-round approach, with each machine sending messages to all other machines in each round, and using the majority vote to make decisions for the next round. Faulty machines are randomly tagged as faulty, and the remaining machines try to reach consensus despite the presence of faulty machines.

The use of multithreading allows for the simulation of a large number of machines in parallel, with each machine running in its own thread. The simulation is designed to be scalable, with the number of machines and faulty machines adjustable based on the input parameters.

Benefits
Overall, this project is an excellent example of how industry-level OOP and multithreading concepts can be used together to create a high-quality, modular, and scalable codebase. The use of OOP principles and multithreading allows for the creation of a flexible and extensible system that can be easily adapted to changing requirements, while the modular design and encapsulation make it easy to understand and modify the code.

The fault-tolerant aspect of the protocol is particularly impressive, as it ensures that the system can continue to function even in the presence of faulty machines. This is a critical feature in real-world distributed systems, where hardware failures and software bugs are a common occurrence.

Conclusion
This project is a testament to the power of modern software engineering techniques, and is an excellent example of how they can be applied to real-world problems. The ability to simulate and test complex distributed systems is becoming increasingly important, and this project is at the forefront of that trend.

