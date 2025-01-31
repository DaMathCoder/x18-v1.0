# x18-v1.0

This CPU is an 8-bit processor designed for simplicity and efficiency in handling basic computational tasks. It operates with a set of 18 distinct instructions, each of which is used to manipulate data in various ways—whether it's loading values into registers, performing arithmetic operations, or handling input/output tasks. The CPU's assembly language, tailored specifically for this architecture, gives developers full control over the machine’s operations, ensuring that every instruction can be accessed and customized for specific use cases. This low-level language allows for a compact and streamlined approach to programming, ideal for applications where minimal resources and quick processing are necessary.

The heart of this CPU’s performance lies in its 4 8-bit registers—RegA, RegB, RegC, and RegD—each designed to store and process data as 8-bit values. These registers are used for various operations, such as mathematical calculations, input/output handling, and temporary storage during computation. RegA, typically the primary register for arithmetic tasks, can hold intermediate results from operations like addition, subtraction, multiplication, or division. RegB is mainly reserved for input/output data, while RegC and RegD provide additional temporary storage and flexibility in handling more complex operations. With this setup, the CPU can efficiently handle a range of tasks in its limited but effective environment.

In terms of memory, the CPU is equipped with a 45-byte RAM matrix, structured as a 5-by-40 grid. This compact memory setup is sufficient for the basic needs of the processor, providing enough space to store variables, results, and data needed for simple programs. The RAM is accessed using a specific set of instructions, such as RMLD (Write to RAM) and RMRD (Read from RAM), enabling seamless interaction with memory locations. Despite the small size, the combination of the 4 registers and the 45-byte RAM allows for effective execution of assembly programs, offering an ideal environment for small-scale embedded systems or educational purposes. With its minimalistic approach, this CPU is an excellent choice for learning about processor architecture and programming at the hardware level.
