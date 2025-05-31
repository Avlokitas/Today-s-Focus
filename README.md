# Today-s-Focus

### Problem Statement
Develop an algorithm for efficient task scheduling that addresses the needs of both individuals and organizations. The system should optimize for:
Task assignment
Maximizing profit
First-Come-First-Serve scheduling
Round-based task allocation
Maximum job scheduling within deadlines

### Features
- Job Scheduling
- Task Division
- Task Search Operation
- Real-Time Scheduling Simulation
- Dual Modes: Individual and Company

### Algorithms Used
###### 1. Greedy Algorithm (Job Scheduling)
Used to Maximize profit from task scheduling. Prioritize high-importance jobs. Maximize the total number of jobs within deadlines. This algorithm selects the locally optimal choice at each step to find the global optimum.

##### 2. Greedy Bin Packing Algorithm (Task Division)
Used in company mode to distribute tasks among workers in a way that minimizes idle time and optimizes task coverage.

##### 3. Round Robin Algorithm (Task Allocation)
A fair and cyclic approach to distributing tasks among multiple workers, ensuring balanced workload distribution.

##### 4. String Pattern Matching Algorithm (Task Search)
Efficiently searches for tasks by name or keyword using string matching algorithms such as:
Knuth-Morris-Pratt (KMP)
Boyer-Moore
Rabin-Karp
These algorithms help users find tasks in large datasets with minimal time complexity.

### Functionalities
- Input task data including ID, name, priority, duration, and profit
- Choose between scheduling algorithms:
  - Max Profit
  - Max Number of Jobs
  - Priority-Based
  - FCFS (First Come First Serve)
Round Robin
- Simulate allocation to single or multiple workers
- Search tasks by keyword or name
- View scheduled tasks and their allocation details

