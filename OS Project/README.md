CPU Scheduling Simulator
Overview
  The CPU Scheduling Simulator is an interactive web-based tool designed to help users understand and analyze different CPU scheduling 
  algorithms used in operating systems. This simulator allows users to input process details such as arrival time, burst time, and 
  priority and visualize the execution order using Gantt charts.

The tool calculates key performance metrics, including:
 Turnaround Time – Total time taken for a process to complete.
 Waiting Time – Time a process spends in the ready queue before execution.

By simulating different scheduling techniques, users can compare how each algorithm impacts process execution efficiency. This is especially useful for students, developers, and computer science enthusiasts who want to grasp the fundamentals of CPU scheduling in a practical and visual manner.

Scheduling Algorithms
 First Come First Serve (FCFS) – Non-preemptive, executes processes in the order they arrive.
 Shortest Job First (SJF) – Non-preemptive, prioritizes shorter burst time processes.
 Round Robin (RR) – Preemptive, allocates a fixed time quantum for each process.
 Shortest Remaining Time First (SRTF) – Preemptive version of SJF, prioritizes the process with the shortest remaining time.
 Priority Scheduling – Can be preemptive or non-preemptive, executes processes based on priority levels.

Features
 Interactive user input for process details
 Real-time visualization using Gantt charts
 Computes Turnaround Time & Waiting Time
 Supports both preemptive and non-preemptive algorithms
 Simple and user-friendly UI for better understanding

Technologies Used
 HTML, CSS, JavaScript (Frontend)
 Bootstrap (for styling)
 Chart.js (for Gantt chart visualization)



