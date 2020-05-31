# cv-lang 
CodeView programing language
Fast and elastic language inspired by C, C#, Java, Rust - design concept. 
Actual *Version 0.2*

# General language assumptions
* The code representation depends on the view.
* Object orintet language inspired by C#/Java
* Context
  * Hardware context - memory allocation strategy, checking memory limits - depends on actual hardwarecontext
  * Syntax depend on runtime context - a'la safe in C#
  * Execution context
* indirect compilation to C
* Serialization 
  * all typs can by serialized
  * method execution can by serialized by serialization state of virtual machine (stack and heap)
 * Heterogeneous computing -Should run on: microcontrollers, small processor, mobile, desktop and servers processor
* Logging - enable and disable in runtime
* Aspect programming - special block in function - before invoke method (for contract checking, logging), after invoke (for result contract chceking, logging)
 
 
# Modules
* Package manager 
* Serialization
* Virtual machine (CvLang.VirtualMachines)
 * DotNetVirtualMachine
 * CvlVirtualMachine
* Compiler
* IDE
* Database
