# OS
I have used xv6 operating system(RISC-V verion) for the labwork. xv6 is MIT's reimplementation of Unix v6.
Lab1:
Created system calls to retrieve system information and running processes. The sysinfo system call returned the number of active processes, the number of system call made and the number of free memory pages available. The procinfo system call returned the ppid, number of system calls made and the page usage of each active process.


Lab2:
Implemented the basic operations of the Lottery Scheduler and the Stride Schedule,i.e, no ticket transfers, no compensation tickets, etc. The default scheduler for xv6 is a simple round robin scheduler. The performance of all the three schedulers was compared.


Lab3:
Implemented a new system call to create a kernel-level thread called clone(). Uing clone(), built a simple user-level library consisting of thread_create(), lock_acquire() and lock_release(), used for thread management. thread_create() creates a new thread and lock_acquire() function is used to acquire the lock for system resources and lock_release() is responsible for giving up the system reources.
