# Cprograms  
  
## Assignment Details  
  
#### Assign 3

```
1.      Write a C program (not a C++ program) that allows some tasks to be preformed automatically from a menu-driven interface. Automate the following tasks:
•       [4] Rename a file
•       [4] Delete a file or a directory
•       [4] Output Process Information  
•       [6] Execute “mode 644 ls –l”

Menu:
1.      Rename a file
2.      Delete a file or a directory
3.      Output Process Information
4.      Execute “mode 644 ls –l”
5.      Exit

Rename a file
prompt for two arguments: existing file name & new file name.  

Delete a file or a directory
prompt for a file or a directory to be deleted.
 
Output Process Information
Will display the process ID of the running process and the Process ID of its parent.
Output example:
My process ID is: 1587
My parent’s process ID is: 1455

Execute “mode 644 ls –l”
Your program should use fork and execl system calls to execute the “mode 644 ls –l” command. Please note that mode is a shell script you created for your lab7
```
  
  
#### Assign 4

```
Write two programs that run in parallel and interact to play the “Paper, Scissors, Rock” game.
In this game, one player chooses paper, scissors, or rock. Then s/he reveals her/his choice (using a socket).
A referee receives the player choice, then gets the computer to generate a random choice, and decides who wins as follows:
Paper beats rock (by covering it).
Rock beats scissors (by blunting it).
Scissors beats paper (by cutting it).
Matching choices draw.
Your program should simulate such a game.

You should write two programs, which operate as follows:
a.      One program is the referee program, which is actually a server program. The program will set up a socket with a unique port number. The referee program can get message from and send message to a client program as shown above; also it should randomly generate a string: Paper, Scissors or Rock.

b.      One program is a player program, which is actually a client program. The program will connect to a socket. The player program can also get message from and send message to the referee through a socket.

Please note that the server (referee) program should be able to handle multiple clients (up to 5 clients) at a time.

```  
  
#### Lab 7  

```  
1.      Create a makefile by doing the following steps:
a.      Copy all the files in /tmp/CPSC1280/lab7Sample into a subdirectory in your home directory.
b.      Create a Makefile to compile all the files and create an executable called sampleProject.
c.      Test your Makefile by doing the following steps:
i.      Make the sampleProject by running the make command. Check if the sampleProject is created correctly.
ii.     Make sure your Makefile removes the executable and all the .o files when make clean command is executed.
iii.    Explain the make behavior after executing each of the following commands, one after the other:
         > make
         > make
         > touch bar1.c
         > make


```  

#### Lab 8  

```  
1.      Modify the application presented in /tmp/CPSC1280/lab8 directory to implement the following:
a.      The compute function should be in a separate file, compute.c, and its include statement in compute.h
b.      Modify the makefile in the /tmp/CPSC1280/lab8 directory accordingly.
c.      Add clean target to the makefile to remove the object files and the executable file.

```  
