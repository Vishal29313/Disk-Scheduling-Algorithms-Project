# Disk-Scheduling-Algorithms-Project
# Disk Scheduling Project

This project implements two disk scheduling algorithms: First-Come, First-Served (FCFS) and Shortest Seek Time First (SSTF). The application takes user input for disk requests and processes them using the selected algorithm.

## Algorithms

### 1. First-Come, First-Served (FCFS)
The FCFS algorithm processes disk requests in the order they arrive. It is simple to implement but may not always provide the best performance in terms of seek time.

### 2. Shortest Seek Time First (SSTF)
The SSTF algorithm selects the disk request that is closest to the current head position, minimizing the seek time. This approach can lead to better performance compared to FCFS, especially in scenarios with varying request distances.
