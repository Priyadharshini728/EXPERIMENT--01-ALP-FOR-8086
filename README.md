# EXPERIMENT--01-ALP-FOR-8086
# Name : PRIYADHARSHINI P
# Roll no : 212224040252
# Date of experiment : 25-04-2026





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations:
```
org 100h

MOV AX,1224H
MOV BX,1122H
ADD AX,BX 

MOV CX, 7456H
MOV DX, 5000H
SUB CX, DX

MOV AX, 0012H      
MOV BX, 000BH      
MUL BX    

MOV AX,00A2H
MOV CX,0014H
DIV CX
        

ret
```

## Addition  of 8 bit ALP Output :

<img width="1564" height="554" alt="image" src="https://github.com/user-attachments/assets/ad3b13fa-18d7-40ae-b933-6ca4f781cfe7" />

 
## Subtraction   of 8 bit numbers  ALP Output :
<img width="1564" height="564" alt="image" src="https://github.com/user-attachments/assets/1a8f9cdd-53e5-490e-985d-e10dc2966f1c" />

  
## Multiplication alp Output :
<img width="1563" height="562" alt="image" src="https://github.com/user-attachments/assets/3a6b7440-4992-4deb-94d4-1df0135d13bd" />



## Division alp Output :
<img width="1568" height="561" alt="image" src="https://github.com/user-attachments/assets/dce9c8a3-ac4b-4b3f-af5c-bb276ccc2783" />

## Programs for Logical operations:
```
org 100h

MOV AX,5678h
MOV BX,1234h
AND AX,BX

MOV CX,5525h
MOV DX,2252h
OR CX,DX

MOV AX,1122h
MOV BX,0F0Fh
XOR AX,BX

MOV DX,1357h
NOT DX

MOV AX,2468h
MOV BX,1357h
AND AX,BX
NOT AX

MOV CX,0F00h
MOV DX,00FFh
XOR CX,DX
NOT CX

ret
```
## Logical AND operation ALP Output:

<img width="1588" height="559" alt="image" src="https://github.com/user-attachments/assets/8387dcd1-44b8-4d57-b39f-5c2285ffc130" />

## Logical OR operation ALP Output:
<img width="1594" height="556" alt="image" src="https://github.com/user-attachments/assets/1c3874dd-2d69-4d63-a081-fee2a69e1e68" />

## Logical XNOR operation ALP Output:
<img width="1598" height="562" alt="image" src="https://github.com/user-attachments/assets/f37f9904-9d8d-42ab-9ce8-1fbe9ce4302b" />

## Logical NAND operation ALP Output:
<img width="1589" height="561" alt="image" src="https://github.com/user-attachments/assets/f392121c-1314-454b-9d6c-0d98f5a45a28" />


## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








