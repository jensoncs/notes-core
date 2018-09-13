# Operating System Concepts

## Process

program
  |
  |
Executing
  V
In main memory


A process is :

*. A program in execution
*. Instance of a running process
*. Entity, That can be assigned and execute on a processor

Computer program -->{Write in }--file -->Executing--->Process(program loaded in main memory). A process which perform all the tasks mentioned in the progarm


### Process will be divided into 4 section

1. Stack
2. Heap
3. Text
4. data

### Layout of process inside main memory


Stack - Contains the temporray data. such as fucntions, values, local variables

Heap - It is dynamically allocated memory to process during run time.

Data - Contains global variables and the static variables

Text - Program counter + It contains the conents of processor register 


### Process synchronization

Bases uponm the synchronization process is divided into 2 type

1. Independent - No dependency. Execution of one process does not affect other
2. Cooperative process - Execution of one process is affecting other process.


## Critical section problem

Code segment --> Shared variables.

Eg : critical section problem is like movie -> shared variable like theatre. If multiple teams want to see the movie from one theatre, the movie will be available for only 1 team and the remianing team will be waiting with some mutual understanding. is called critical section problem.

When ever the critical segment is executed the remaining will be in wait is called code segment.

If all the people are coming at the same time, there will be a probelm is called critical section probelm.


## Semaphore

It has two variables

wait(s) - wait semaphors - is an decrement operation 

signal(s) - increment operation

Its used to solve the critical section problem./

