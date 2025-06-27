# Project-Code
🚦 Traffic Simulation System in Java
This project simulates a basic urban traffic system using Java, modeling how vehicles move through a network of roads and intersections with traffic lights. It helps analyze vehicle flow, waiting times, and signal behavior under dynamic traffic conditions.

🔍 Key Features
Simulates four intersections (A, B, C, D) connected by directional roads.

Vehicles are generated at regular intervals with random paths and types (normal or emergency).

Emergency vehicles are prioritized in queues to simulate real-world urgency.

Traffic lights switch between roads dynamically based on real-time queue lengths.

Priority queues are used to handle vehicle order efficiently at intersections.

Tracks and calculates each vehicle’s travel and waiting time.

⚙️ How It Works
The simulation runs for 1000 time steps. At each step:

New vehicles may be created with a random path.

Vehicles move along roads and queue at intersections when they reach the end of a road.

Traffic lights update their active green phase based on queue size, ensuring smarter signal timing.

Vehicles in the green-lit lane are processed and move to the next road or complete their journey.

At regular intervals, the system prints stats about queue lengths and vehicle status.

📊 Final Output
At the end of the simulation, the program prints:

Total number of vehicles created

Number of vehicles that completed their journey

Average travel time

Average waiting time

Number of vehicles still on the road

✅ Use Cases
This simulation is great for:

Learning how traffic systems can be modeled in code

Understanding priority queues and dynamic signal control

Experimenting with traffic flow optimization

Building more advanced traffic or smart city simulations
