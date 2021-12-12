
# OPERATING SYSTEM

# Table Of contents
| ID  | CHAPTER NO.                        |
| --- | ---------------------------------- |
| 1   | [INTRODUCTION](https://github.com/hacker-404-error/Operating_System#chapter-1-introduction)                       |
| 2   | PROCESS MANAGEMENT                 |
| 3   | CPU SCHEDULING                     |
| 4   | THREADS & MULTITHREADING           |
| 5   | PROCESS SYNCHRONISATION & DEADLOCK |
| 6   | MEMORY MANAGEMENT                  |
| 7   | VIRTUAL MEMORY                     |
| 8   | FILE SYSTEM                        |

# CHAPTER-1 INTRODUCTION
| Sno. | TOPICS                   |
| ---- | ------------------------ |
|0.    |[Introduction_Written_Notes](https://github.com/hacker-404-error/Operating_System/blob/main/Notes/1-INTRODUCTION.pdf)|
| 1.   | [What is Operating System ](https://github.com/hacker-404-error/Operating_System#what-is-operating-system)|
| 2.   | [Services Of OS           ](https://github.com/hacker-404-error/Operating_System#services-of-operating-system)|
| 3.   | [Goals Of OS              ](https://github.com/hacker-404-error/Operating_System#goals-of-operating-system)|
| 4.   | [Parts Of OS              ](https://github.com/hacker-404-error/Operating_System#parts-of-operating-system)|
| 5.   | [Protection In OS         ](https://github.com/hacker-404-error/Operating_System#protrction-in-os---dual-mode)|
| 6.   | [Types Of OS              ](https://github.com/hacker-404-error/Operating_System/blob/main/README.md#types-of-operating-system)|

### What is Operating System?
-----------------------------
```
1-Interface between user and hardware.
2-Set of utilities to simplify application development.
3-Control Program.
4-Acts like Govt.
```
<!-- ![os layout](https://github.com/hacker-404-error/Operating_System/blob/main/images/os%20layout.jpg) -->
<p align="center">
<img src="https://github.com/hacker-404-error/Operating_System/blob/main/images/os%20layout.jpg" alt="this is where operating system lies">
</p>

### Services Of Operating System
--------------------------------
<p align="center">
<img src="https://github.com/hacker-404-error/Operating_System/blob/main/images/Services-of-Operating-System.jpg" alt="this is where operating system lies">
</p>

### Goals Of Operating System
------------------
```
1-Memory Management
2-Processor Management 
3-Device Management 
4-File Management 
5-Security 
6-Job Accounting 
7-Control Over System Performance 
8-Interaction with the Operators 
9-1-Error-detecting Aids 
10-Coordination Between Other Software and Users 
```
### Parts Of Operating System
<p align="center">
<img align="center" src="https://github.com/hacker-404-error/Operating_System/blob/main/images/parts%20of%20os.jpg" alt="Parts Of OS">
</p>

### Protection In Operating System - DUAL MODE
```
Let: 
-user is writting something in MS Word (process is in user mode (mode bit=1)).
-If user want to save this file : 
-user and MS word do not have the authority to make changes in disk (saviing process).
-User calls (system call) to save this file.
-Operating system have all authorities to make changes in disk(saving file).
-Operating system change the mode bit to 1(kernel process (cannot accessible by users)and 
-execute system call (saving the file in the disk).
AND 
-Return to user process by changing mode bit to 1.

```
<p align="center">
<img align="center" src="https://github.com/hacker-404-error/Operating_System/blob/main/images/Protection%20_In_OS_DualMode.png" alt="Parts Of OS">
</p>

### Types Of Operating System
<p align="center">
<img align="center" src="https://github.com/hacker-404-error/Operating_System/blob/main/images/Types%20Of%20Operating%20System.png" alt="Parts Of OS">
</p>

