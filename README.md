Sleeping-Teaching-Assistant
OS Project: Sleeping Teaching Assistant using mutex locks and semaphores.

N threads for students. 1 thread for TA.

Semaphores used:

A semaphore to signal and wait TA's sleep.
An array of 3 semaphores to signal and wait chair to wait for the TA.
A semaphore to signal and wait for TA's next student.
Mutex Lock used:

To lock and unlock variable ChairsCount to increment and decrement its value.
