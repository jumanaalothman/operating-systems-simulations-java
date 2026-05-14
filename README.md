# Operating Systems Simulations in Java

## Overview

This repository contains Java implementations of operating systems concepts developed as part of an Operating Systems course. The project includes simulations for CPU scheduling and memory allocation strategies.

## Technologies Used

- Java
- Object-Oriented Programming
- Operating Systems Concepts

## Features

### 1. CPU Scheduling Simulation

The project implements the Shortest Remaining Time First (SRTF) scheduling algorithm.

The scheduler:

- Accepts process arrival time and burst time
- Selects the process with the shortest remaining time
- Handles process preemption
- Adds context switching time
- Generates a Gantt chart
- Calculates performance metrics

Performance metrics include:

- Average Turnaround Time
- Average Waiting Time
- CPU Utilization

### 2. Memory Allocation Simulation

The project also implements memory allocation strategies using fixed partitions.

Supported allocation strategies:

- First Fit
- Best Fit
- Worst Fit

The memory simulator allows users to:

- Create memory blocks
- Allocate processes to memory
- Deallocate processes
- Display memory status
- Show internal fragmentation

## Project Structure

```text
Assignment1/
├── Process.java
├── Scheduler.java
└── SchedulerMain.java

MemoryMain.java
Methods.java
Partition.java
