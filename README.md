# CPU Scheduling Simulator

This project is a **CPU Scheduling Simulator** that implements various scheduling algorithms to evaluate their performance based on given processes. The simulation includes statistical analysis of key performance metrics such as wait time and turnaround time.

## Features

The project simulates the following CPU scheduling algorithms:
1. **First Come First Serve (FCFS)**
2. **Shortest Job First (SJF)**
3. **Preemptive Shortest Job First (SRTF)**
4. **Round Robin (RR)**
5. **Priority Scheduling**

## How It Works

1. **Process Generation**:
   - A set number of processes are created with random burst times and arrival times.
   - 80% of the processes have randomly generated arrival times (exponential distribution).
   - 20% of the processes have an arrival time of 0.
   - Each process has a randomly assigned priority (importance).

2. **Scheduling**:
   - Processes are sorted by arrival time.
   - Each algorithm is applied sequentially, and the results (e.g., wait time, turnaround time) are displayed.

3. **Statistical Analysis**:
   - Key performance metrics such as maximum/minimum wait times and initial response times are computed and displayed for each scheduling algorithm.

### Prerequisites
- A C++ compiler (e.g., GCC, Clang, or MSVC)
- Standard C++ libraries (`<iostream>`, `<vector>`, `<algorithm>`, `<cmath>`, `<cstdlib>`, `<ctime>`)


