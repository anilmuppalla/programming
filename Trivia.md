#### What is swapping? 

Swapping is a simple memory/process management technique used by an 
operating system to increase processor utilization by moving some blocked process from the main memory to the secondary memory. The execution continues with the newly arrived process. After performing the swapping process, the operating system has two options in selecting a process for execution :
 * Operating System can admit newly created process
 * Operating system can activate suspended process from the swap memory.
 
 ![Process Execution](http://blog.sudobits.com/wp-content/uploads/2010/08/swapping.png)

#### Memory access and Storage

Computer Memory can be classified as :
 * Registers - Internal register in a CPU is used for holding variables and temporary results
 * Cache - Cache is used by the CPU for memory which is being accessed over and over again
    * L1 Cache - accessed without any delay
    * L2 Cache - takes more clock cycles than L1
    * L3 Cache - takes more clock cycles than L2
 * RAM - is a form of computer data storage which stores frequently used program instructions to increase the general speed of a system. A random-access memory device allows data items to be read or written in almost the same amount of time irrespective of the physical location of data inside the memory
 * Hard Disk - is a data storage device that uses magnetic storage to store and retrieve digital information using one or more rigid rapidly rotating disks (platters) coated with magnetic material. The platters are paired with magnetic heads, usually arranged on a moving actuator arm, which read and write data to the platter surfaces.

![Computer Memory Hierarchy](https://i2.wp.com/moreprocess.com/wp-content/images/devices/Computer%20memory%20hierarchy%20Internal%20register,%20cache,%20RAM,%20hard%20disk,%20magnetic%20tape.jpg?zoom=2&resize=444%2C418')