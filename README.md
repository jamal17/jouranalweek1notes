# jouranalweek1notes


Today is wdensday 08/23/2017. A note for chapter 1

The most way to understand the OS work is the software developers use abstraction as tool when buliding an OS and applecation.
**level and layers**.

using abstraction to split computing system into componenet.

There are three main levels, each one have it is own componenets.

1. User processes(applecation)---->graphical user --->interface--->server--->shell.

2. Linux kernel(the hart of OS)---->system calls--->processes Management--->Memory Management---> device drivers.

3. The main and importment one(Hardware)--->processor(CPU)--->Main Memory(RAM)--->Disks--->network parts.


**The difference between the way that the kernel and user processer run**.


Kernel run in kernel mode.

User run in user mode.

Kernel has unrestricted access to processer and main memory this will make it very dengerous because it will allows a kernel access a kenel space.
Easily crash the entire system for a mistake. 
unlike the user mode is restricted access to subset of memory and safe CPU.
Hardware: has the most importent one is main memory.------>is a big storage for 0,1 they called a bit.

The kernel:
(1) processes for determining which processer allowed use CPU.
(2) Memory to keep and track the all memory.
(3) Device driveto operate the hardware.
(4) System calls and support its use to communicate with kernel.

Process Management it's send the information to the kernel and to the hardware and received the result to posted to user.


