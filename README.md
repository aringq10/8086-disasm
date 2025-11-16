### A disassembler for 8086 .COM and .EXE files, fully written in 8086 assembly.
* To compile the disassembler, you must have **both** ```dis.asm``` and ```opcodes.inc``` in the same directory.<br>
* I used TASM and TLINK to do the compiling and linking, though I do not make any guarantees in regards to other assemblers.<br>
* To run TASM, TLINK and the compiled disassembler, I used [DOSBox](https://www.dosbox.com/download.php?main=1).<br>
```
Z:\>tasm.exe dis.asm

Z:\>tlink.exe dis.obj

Z:\>dis.exe yourfile.(exe/com) output.txt
```
