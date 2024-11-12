# Cooperative Drone-Assisted Mobile Access Network for Disaster Emergency Communications

## Project Overview

This project is a simulation of a Cooperative Drone-Assisted Mobile Access Network. It uses drone-mounted base stations (DBSs) to restore communication links in disaster-affected areas. The project implements the COACH (COoperative DBS plAcement and CHannel allocation) algorithm to optimize DBS placement, channel allocation, and traffic offloading.

**Key Components:**
1. Drone-Mounted Base Stations (DBSs)
2. Macro Base Stations (MBSs)
3. Mobile Users (MUs)
4. COACH Algorithm for dynamic DBS deployment and channel allocation

## Table of Contents

- [Core Concept](#core-concept)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow](#workflow)
- [Output](#output)
- [Citations and References](#citations-and-references)

## Core Concept

The core idea is to create a resilient communication network that can be deployed swiftly in disaster zones. DBSs provide temporary communication infrastructure by linking mobile users (MUs) within affected areas to macro base stations (MBSs) outside these zones.

## Installation

### Prerequisites
- C Compiler (for `coach_algorithm.c`)
- MATLAB (for COACH algorithm simulation)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git

2.	Change to the project directory:

cd yourrepository


3.	Ensure you have a C compiler installed for compiling the code, and MATLAB for the simulation.

### Usage

Running the Code

1.	Compile the C Code:
Compile the C code for the COACH algorithm with:

gcc coach_algorithm.c -o coach_algorithm


2.	Run the Compiled Program:
Execute the compiled program:

./coach_algorithm


3.	Run MATLAB Simulation:
Open the COACH_algorithm.m MATLAB script in MATLAB and execute it to simulate the algorithm.

### Output

The output of the code includes:
	•	Access and backhaul rates for each DBS, indicating communication capacity and efficiency.
	•	Identification of bottlenecked DBSs and how D2D (drone-to-drone) traffic offloading helps balance the network load.
	•	Total network data throughput, showing the effectiveness of the COACH algorithm in handling data traffic during simulated disaster scenarios.

### Workflow

1.	DBS Deployment: DBSs are deployed either in Hovering Mode (stationary) or Ferry Mode (moving on a fixed path) to provide connectivity within the disaster zone.
2.	Channel Allocation and MU Association: COACH algorithm assigns channels and connects MUs to the closest DBS for optimized data transfer.
3.	Traffic Bottleneck Detection and Offloading: The COACH algorithm detects any bottlenecks at DBSs and initiates offloading through D2D communication to alleviate congestion.
4.	Real-Time Network Adaptation: The COACH algorithm dynamically adjusts channel allocation and DBS-MU associations to adapt to changing conditions in the disaster zone.

### Citations and References

This project references the following sources:
	•	Project report:
	Rohan 221CS146 and Aryan Yadav 221CS221, “A Cooperative Drone Assisted Mobile Access Network for Disaster Emergency Communications,” National Institute of Technology Karnataka, Department of Computer Science and Engineering.
	•	Additional references:
	•	Relevant publications on drone-assisted mobile access networks and emergency communications.
	•	MATLAB official documentation for the MATLAB simulation environment and scripting guidance.

Replace placeholders (e.g., `https://github.com/yourusername/yourrepository.git`) with actual information specific to your project. Let me know if you need further customization!
