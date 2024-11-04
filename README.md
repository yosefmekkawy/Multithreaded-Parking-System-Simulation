# Multithreaded-Parking-System-Simulation

<h1>Yousef Hossam: Parking Lot and Semaphore Management</h1>
Set up the Parking Lot: Implement the parking lot with a limit of 4 parking spots.
Semaphore Integration: Integrate semaphores to manage the availability of parking spots, ensuring cars can park only if a spot is free.
Parking Spot Release: Implement logic to release the parking spot once the car’s stay duration is over.
Synchronization: Ensure proper synchronization so no more than 4 cars are parked at once.


<h1>Mekkawy: Gate Simulation and Car Threads</h1>
Gate Simulation: Implement the three gates (Gate 1, Gate 2, Gate 3) using separate threads to simulate cars arriving at different times.
Car Thread Creation: Each car should be represented by a thread. These threads will attempt to park based on arrival time, stay for the specified duration, and leave after.
Car Scheduling: Use sleep() to simulate the arrival time and parking duration for each car as per the test case input.


<h1>Abdo: Input Parsing and Logging</h1>
Input Parsing: Implement functionality to read and parse car arrival data from the input .txt file in the specified format.
Data Processing: Extract relevant details (gate, car ID, arrival time, parking duration) and pass this data to the gate threads.
Logging: Log every action for each car, including arrival, parking, waiting (if parking is full), and departure.


<h1>Eslam: Status Reporting and Concurrency Management</h1>
Real-time Status Reporting: Track the number of cars currently parked and log this information after every parking and departure action.
Final Report Generation: After the simulation, print the total number of cars served, the number of cars each gate served, and the final count of cars in the parking lot.
Concurrency Testing: Ensure the system handles concurrent arrivals and departures without errors or race conditions
