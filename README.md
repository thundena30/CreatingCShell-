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

FileZilla 2 (transfer files to ssh client); blazersh.c; myprog1.c; myprog2.c; Linux Terminal (UAB)

INSTRUCTIONS:

To compile : gcc -o blazersh blazersh.c; gcc -o myprog1 myprog1.c; gcc -o myprog2 myprog2.c;

RUNNING THE TESTS:

To print output:./blazersh; ./myprog1; ./myprog2;

Screenshots:
<img width="1280" alt="demo1" src="https://user-images.githubusercontent.com/46456051/53303206-17352f00-383e-11e9-9261-f973b18120c2.png">
<img width="1280" alt="demo2" src="https://user-images.githubusercontent.com/46456051/53303245-a7737400-383e-11e9-915e-631c590d0402.png">

CONTACT ME:

thundena@uab.edu

```
