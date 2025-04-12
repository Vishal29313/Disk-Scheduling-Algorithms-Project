# Disk Scheduling Algorithms Project

This project simulates three popular disk scheduling algorithms:

- **First-Come, First-Served (FCFS)**
- **Shortest Seek Time First (SSTF)**
- **SCAN (Elevator Algorithm)**

The program allows users to input a sequence of disk requests along with the initial head position, then computes and compares the order of service, total head movement, and average seek time based on the selected algorithm.

---

## 🔍 Algorithms Overview

### 1. First-Come, First-Served (FCFS)

- Services requests in the exact order of arrival.
- Simple but can result in high total head movement.

### 2. Shortest Seek Time First (SSTF)

- Selects the request closest to the current head position.
- Optimizes seek time but may cause starvation for distant requests.

### 3. SCAN (Elevator Algorithm)

- Moves the disk head in one direction (like an elevator), servicing all requests in its path until the end is reached.
- Then, the direction reverses and continues servicing.

---

## 📥 Input Format

The user needs to provide:

- A list of disk track requests (integers)
- The initial head position
- The choice of scheduling algorithm (FCFS, SSTF, SCAN)
- (For SCAN) The direction of head movement: `"left"` or `"right"`

---
