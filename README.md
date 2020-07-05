# attack-lab
1. CMU CS-15213 lab on buffer overflow and ROP attacks.
1. Byte sequence of the attack string in  in exploit<n>.txt .
1. Actual string in exploit<n>.ans . Assembly code in .s file. Disassembled assembly code (to get the byte sequence in <exploit.d> file.
1. Use objdump -d to disassemble the code section.
# Level 1
Very easy. Ensure no null byte or 0x0A in the string. Address of touch1 in little endian format.

# Level 2
Conceptual mistake about stack pointer took a lot of time. GDB to the rescue. Interesting problem to ensure no null character in the attack string.


