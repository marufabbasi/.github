# Maruf Abbasi

Most of my good code is owned by the companies I have worked in. But, when I have time I work on compilers, virtual machines and robotics/machine learning.

This github account is to share some of those. Please keepin mind that I do not have a lot of time to follow all the software engineering principles.

### groot

Repository: https://github.com/marufabbasi/groot
Compiler repo: https://github.com/marufabbasi/grootc

I  have built the groot language and interpreter for it in about 100 minutes during a live session on youtube. The audience of my seesion was mostly non-english speaking -but you should be able to  follow the code maybe. Here is the video:
 
https://www.youtube.com/watch?v=su8PBuGOXq4 

I am in the process of creating a just in time compiler (using LLVM) for the language.

The objectives of the compiler:

* Run applications fast (comparable to C++  and Rust)
* Automatic memory management with out a GC (like Rust)
* High level language formost tasks but can be used for systems programming as well (alternative to  C++)

Development plan:

* Use ANTLR4 to generate lexer/parser for the language
* Create an interpreter to demonstrate the language
* Generate executable machine code using LLVM as the backend
* We prefer not to work on optimization and machine code generation until absolutely necessary (use LLVM instead)  

### jvm

Repository: https://github.com/marufabbasi/jvm

This is java virtual machine I have created during my undergraduate program. It can run java applications and created from scratch using C++. 


I have created an article on code project explaing how it works: https://www.codeproject.com/Articles/24029/Home-Made-Java-Virtual-Machine 
