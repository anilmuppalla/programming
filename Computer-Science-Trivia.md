### What is swapping? 

Swapping is a simple memory/process management technique used by an 
operating system to increase processor utilization by moving some blocked process from the main 
memory to the secondary memory. The execution continues with the newly arrived process. 
After performing the swapping process, the operating system has two options in selecting a process for execution :
 * Operating System can admit newly created process
 * Operating system can activate suspended process from the swap memory.
 
 ![Process Execution](http://blog.sudobits.com/wp-content/uploads/2010/08/swapping.png)

### Memory access and Storage

Computer Memory can be classified as :
 * Registers - Internal register in a CPU is used for holding variables and temporary results
 * Cache - Cache is used by the CPU for memory which is being accessed over and over again
    * L1 Cache - accessed without any delay
    * L2 Cache - takes more clock cycles than L1
    * L3 Cache - takes more clock cycles than L2
 * RAM - is a form of computer data storage which stores frequently used program instructions to 
 increase the general speed of a system. A random-access memory device allows data items to be read 
 or written in almost the same amount of time irrespective of the physical location of data inside the memory
 * Hard Disk - is a data storage device that uses magnetic storage to store and retrieve digital 
 information using one or more rigid rapidly rotating disks (platters) coated with magnetic material. 
 The platters are paired with magnetic heads, usually arranged on a moving actuator arm, which read 
 and write data to the platter surfaces.

![Computer Memory Hierarchy](https://i2.wp.com/moreprocess.com/wp-content/images/devices/Computer%20memory%20hierarchy%20Internal%20register,%20cache,%20RAM,%20hard%20disk,%20magnetic%20tape.jpg?zoom=2&resize=444%2C418')

### Difference between CISC and RISC

RISC (Reduced Instruction Set Computing) and CISC (Complex Instruction Set Computing) are two 
computer architectures that are predominantly used nowadays. The main difference between RISC and 
CISC is in the number of computing cycles each of their instructions take. With CISC, each instruction 
may utilize a much greater number of cycles before completion than in RISC.

The reason behind the difference in number of cycles utilized is the complexity and goal of their 
instructions. In RISC, each instruction is only meant to achieve a very small task. So if you want 
a complex task done, then you need a lot of these instructions strung together. With CISC, each 
instruction is similar to a high level language code. You only need a few instructions to get what 
you want as each instruction does a lot.

[..more](http://www.differencebetween.net/technology/protocols-formats/difference-between-risc-and-cisc/)

### RAID

RAID is a data storage virtualization technology that combines multiple physical disk drive 
components into a single logical unit for the purposes of data redundancy, performance improvement, 
or both.

Data is distributed across the drives in one of several ways, referred to as RAID levels, depending 
on the required level of redundancy and performance. The different schemes, or data distribution 
layouts, are named by the word RAID followed by a number, for example RAID 0 or RAID 1. Each schema, 
or RAID level, provides a different balance among the key goals: reliability, availability, performance, and capacity.

### Difference between static and dynamic linking

Static Linking : 
* links all library modules into an executable. It is done by a linker in the 
compilation process. The linker combines library routines with the program code in order to resolve 
external references, and to generate an executable image suitable for loading into 
memory.
* Statically linked files are significantly larger in size because external programs
* if any of the external programs has changed then they have to be recompiled and re-linked
* Programs that use statically-linked libraries are usually faster
* Programs that use statically-linked libraries are usually faster

Dynamic Linking :
* The names of the external libraries (shared libraries) are placed in the final executable file 
while the actual linking takes place at run time when both executable file and libraries are placed 
in the memory
* In dynamic linking only one copy of shared library is kept in memory. 
This significantly reduces the size of executable programs
* In dynamic linking this is not the case and individual shared modules can be updated 
and recompiled.
* Dynamically linked programs are dependent on having a compatible library.