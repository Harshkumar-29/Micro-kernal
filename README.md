MiniWare OS is a simple Command-Line Based Operating System Simulation written in C language for B.Tech Operating System project. It demonstrates basic OS concepts such as Process Management, File System Handling, and Shell Command Execution in a beginner-friendly way.

Features

Boot Animation (OS startup simulation)

Background Processes Simulation (init, kworker, shell, networkd)

Process Viewer (ps command)

In-Memory File System

Create and Read Files

Date & Time Display

Colored Terminal Output

Interactive Shell Interface

Reboot and Shutdown Simulation

Technologies Used

C Programming Language

Standard Libraries (stdio.h, stdlib.h, string.h, time.h)

Windows API (windows.h)

Supported Commands
Command	Description
help	Show all available commands
clear	Clear the screen
ps	Display running processes
date	Show current date & time
createfile <name>	Create a new file
listfiles	List all files
cat <name>	Show file content
reboot	Restart MiniWare OS
exit	Shutdown the system
Project Structure

MiniWare OS uses:

Process Table → Stores running processes (PID, Name, Status)

In-Memory File System → Stores files in RAM (Filename + Content)

Command Interpreter (Shell) → Reads and executes user commands

Boot Loader Simulation → Displays startup animation

How to Run
Step 1: Compile
gcc miniware.c -o miniware

Step 2: Run
./miniware


Note: This project is designed for Windows because it uses windows.h.

Sample Output
MiniWare Operating System v1.0
Booting kernel...
Initializing memory... OK
Mounting filesystem... OK
Starting services... OK

root@MiniWare:~# help

Learning Outcomes

This project helps understand:

Basic Operating System Working

Process Management Concept

File System Simulation

Command Line Interface (CLI)

Memory-based Storage

Shell Command Parsing

Future Improvements

File Delete & Edit Feature

Process Kill Command

CPU Scheduling Simulation (FCFS / Round Robin)

Virtual Memory Simulation

User Login System

GUI Version (Optional)

Author

Harsh Kumar
B.Tech Computer Science Engineering
Operating System Project
