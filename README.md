# BankerDetection

<ins>_**Experiment name:**_</ins> Implementation of the Bankers Algorithm (Detection)

<ins>_**Description:**_</ins>
The provided code implements a Deadlock Detection Algorithm for a system with multiple processes and resource types. It utilizes several matrices: arrmax for maximum resource demand, alloc for current resource allocation, need for remaining resource needs, and avail for available resources. The input() function gathers data from the user, including the number of processes, resource types, and the respective matrices. The show() function displays the current state of the system, presenting the allocation, maximum demand, and available resources for each process. The core logic resides in the cal() function, which first calculates the need matrix by subtracting the allocation from the maximum demand. It then uses a safety algorithm to check if the system is in a safe state by attempting to fulfill resource requests and complete processes. If all processes can finish, the system is deemed safe; otherwise, the function identifies and lists processes involved in deadlock. The main() function orchestrates the execution by calling the input(), show(), and cal() functions sequentially to ensure proper data flow and analysis, ultimately determining and displaying whether the system is safe or in deadlock.

<ins>_**Input**_</ins>
The input required for the provided  Bankers  Algorithm (Detection) code is as follows:
	Number of Processes (n): Total number of processes in the system.
	Number of Resource Types (r): Total number of different resource types.
	Maximum Demand Matrix (arrmax) :
	The maximum number of instances of each resource that each process may request.
	Allocation Matrix (alloc) :
	The number of instances of each resource currently allocated to each process.
	Available Resources (avail) :
	The number of instances of each resource currently available in the system.

<ins>_**Output**_</ins>
The output of the provided Bankers Algorithm (Detection) code and the final result:

![image](https://github.com/simoon06/BankerDetection/assets/139492391/f8f31aab-11c8-4ab7-b48d-f6b046b2e19a)

