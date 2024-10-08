# Gossip_Project
Project: Gossip and Push-Sum Algorithm Simulation in Pony

Team Members

	•	Sankaramaddi Hemanth Reddy
	•	Anshita Rayalla

What is Working

This project implements both the Gossip and Push-Sum algorithms for group communication and sum computation using the asynchronous nature of Pony actors. The following features are fully functional:

	1.	Gossip Algorithm for information propagation.
	2.	Push-Sum Algorithm for distributed sum computation.
	3.	Multiple network topologies:
	•	Full Network
	•	3D Grid
	•	Line
	•	Imperfect 3D Grid
	4.	Ability to specify the number of nodes, topology, and algorithm type as command line arguments.
	5.	Measurement of convergence time for each topology and algorithm.

Largest Network Managed

Gossip Algorithm:

	•	Full Network: 2,000 nodes
	•	3D Grid: 5,000 nodes
	•	Line: 100 nodes
	•	Imperfect 3D Grid: 20,000 nodes

Push-Sum Algorithm:

	•	Full Network: 10,000 nodes
	•	3D Grid: 100,000 nodes
	•	Line: 100,000 nodes
	•	Imperfect 3D Grid: 100,000 nodes

How to Run

To run the project, use the following format in the command line:

project2 algorithm numNodes topology 

Where:
        •	algorithm: One of gossip or push-sum.
	•	numNodes: The number of actors involved.
	•	topology: One of full, 3D, line, or imp3D.
	
project2 gossip 1000 fullnetwork

