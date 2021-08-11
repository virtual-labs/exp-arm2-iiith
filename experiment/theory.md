To implement procedure abstraction we need to address the following questions:  

- How to pass parameters?  
- How to return values?  
- How to call the procedure and return back to the calling procedure?  

We can use the registers to pass parameters and return values back and forth between the caller and callee procedures. ARM provides the Branch and Link (BL) Instruction to call procedures. Unlike x86 architecture the return address is not stored on the stack, it is stored in the link register, R14. Code examples are given as a part of the simulator itself.  