# Operating-ystems

Write a C program with the appropriate fork() commands to create a total (including
the main program P0) six processes, with the following kinship structure (tree):
  
       ![image](https://user-images.githubusercontent.com/100516014/200918783-e1c64fdc-9bd4-4804-823f-4233f26fa8ca.png)

As a main part of its work each Pi process simply prints a message on the screen that
indicating its name (Pi), its PID and its PPID. Your program should include
additionally include appropriate wait commands to satisfy the following constraints.
(a) (a) process P0 must wait for completion before it can perform the main part of its task
(b) the P2 process must wait for the completion of the P2 process before performing its main task; and (c) the P2 process must wait for the completion of its main task before performing its main task
the completion of at least two of its immediate children. Finally, P0 upon completion of its execution
be replaced by the ps instruction.
