# G

Minimal RPN stack-based language.  
Zero runtime, direct binary output.  
Memory-safe at compile-time.  
Three-letter uppercase tokens.  
Supports modular includes with `INC` (e.g. `MTH_SUM INC`).  
Targets x86, ARM, RISC-V.  

Example:  
3 4 ADD HLT  

Core tokens: ADD, SUB, MUL, DIV, DUP, POP, SWP, LOD, PUS, JMP, EQZ, HLT, INX, INC.  

Memory safety via OWN, BOR, CLN tokens.  

Versioning from G00 to G99.

Open source under MIT License.  
