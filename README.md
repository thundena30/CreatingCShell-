##README.md

IMPLEMENT A SHELL IN C
 ```
Project Objectives: When the shell is invoked by executing the executable blazersh, it should provide a prompt blazersh> 
and waits for any input from the keyboard. Any input entered will be interpreted as a program to be executed and the shell
should create a new process corresponding to the input entered using fork/exec. You can assume that the newline character
denotes the end of the input. If a newline character is entered without any other text or followed by white space, the shell
should just display the prompt on the next line. The new process created should be able to read keyboard input and display 
output to the terminal. You can assume that these programs are executed only in the foreground, i.e., the shell program will
wait for the child process to complete and when the child process completes successfully it will display the command prompt.
When the shell is invoked by executing the executable blazersh, it should provide a prompt blazersh> and waits for any input 
from the keyboard. Any input entered will be interpreted as a program to be executed and the shell should create a new process
corresponding to the input entered using fork/exec. You can assume that the newline character denotes the end of the input.
If a newline character is entered without any other text or followed by white space, the shell should just display the prompt
on the next line. The new process created should be able to read keyboard input and display output to the terminal. You can
assume that these programs are executed only in the foreground, i.e., the shell program will wait for the child process to 
complete and when the child process completes successfully it will display the command prompt.In addition to creating a 
new process corresponding to each command entered, the shell should also support the following internal commands: environ, set,
list, cd, help, and quit.
```
AUTHOR: PRATYUSHA THUNDENA

ACKNOWLEGMENT: https://www.geeksforgeeks.org/making-linux-shell-c/

PREREQUISITES:

FileZilla 2 (transfer files to ssh client); blazersh.c; myprog1.c; myprog2.c; myprogram.c;  Linux Terminal (UAB)

INSTRUCTIONS:

To compile : gcc -o blazersh blazersh.c; gcc -o myprog1 myprog1.c; gcc -o myprog2 myprog2.c; gcc -o myprogram myprogram.c 

RUNNING THE TESTS:

To print output:./blazersh; ./myprog1; ./myprog2; ./myprogram

Screenshots:

The first screenshot demonstrated the following commands: pwd, ls, cd, and the compilation of programs: myprog1.c, myprog2.c.,myprogram.c, and blazersh.c. The output for myprog1 was Hello World! The output for myprog2 was entering a number of elements in the keyboard.

<img width="1280" alt="demofinal1-myprog1 myprog2" src="https://user-images.githubusercontent.com/46456051/53352724-b66b2c80-38f9-11e9-8f8f-ff05f8c00c84.png">

The second screenshot specifically demonstrated the execution of myprogram, in which, one has input.txt and out.txt. The shell program strongly supported I/O redirection with command-line arguments : myprogram 1 2 < input.txt > out.txt. 

<img width="1280" alt="demofinal2-input output" src="https://user-images.githubusercontent.com/46456051/53352793-d7338200-38f9-11e9-96e8-61539682af32.png">

The third screenshot depicted the compilation and execution of blazersh.c. 

<img width="1280" alt="demofinal3-blazersh" src="https://user-images.githubusercontent.com/46456051/53354520-4c548680-38fd-11e9-8342-d7d5bfc22482.png">

CONTACT ME:

thundena@uab.edu

```
