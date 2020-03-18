# Linux-Debugging
GDB Debugging
A debugger is a program that runs other programs, allowing the user to exercise control over these programs, and to examine variables when problems arise.

GNU Debugger, which is also called gdb, is the most popular debugger for UNIX systems to debug C and C++ programs.

GNU Debugger helps you in getting information about the following:

If a core dump happened, then what statement or expression did the program crash on?

If an error occurs while executing a function, what line of the program contains the call to that function, and what are the parameters?

What are the values of program variables at a particular point during execution of the program?

What is the result of a particular expression in a program?

How GDB Debugs?

GDB allows you to run the program up to a certain point, then stop and print out the values of certain variables at that point, or step through the program one line at a time and print out the values of each variable after executing each line.

GDB uses a simple command line interface.
