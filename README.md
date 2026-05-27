# EXPERIMENT--01-ALP-FOR-8086
# Name : JAYASREE R
# Roll no : 212223230087
# Date of experiment :

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

<img width="630" height="459" alt="image" src="https://github.com/user-attachments/assets/108ab1e9-6fb4-45a2-b960-49255bbc77ad" />

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h
MOV AL,0BH
MOV BL,05H
ADD AL,BL
hlt
```


## Output  

 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/47ae00ee-eb6b-45ef-b57f-3372503bbd68" />


## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
MOV AL,0BH
MOV BL,05H
SUB AL,BL 
hlt
```
## Output  
<img width="630" height="459" alt="image" src="https://github.com/user-attachments/assets/812de304-c540-41a9-abff-4da26d2dc280" />

## Multiplication alp 
```
org 100h
MOV AL, 0BH
MOV BL, 05H
MUL BL
hlt
```
 ## Output  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a30854dc-ce64-4e16-a35f-9857af988282" />

## Division alp 
```
org 100h
MOV AL, 0BH
MOV BL, 05H
DIV BL
hlt
```
## Output  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ea80adca-610c-40c0-834f-af5596264181" />

## AND operation of 8 bit numbers ALP
```
mov AX,12H
mov BX,34H
and AX,BX
HLT
```
## Output
<img width="1590" height="799" alt="image" src="https://github.com/user-attachments/assets/dabd15a2-640a-4a44-a75c-a629b0cd8886" />

## OR of 16 bit numbers ALP
```
MOV AX,6745H
MOV BX,234FH
OR AX,BX
HLT
```
## Output
<img width="1605" height="838" alt="image" src="https://github.com/user-attachments/assets/ba7547e3-3927-4472-b9af-4aac1b87a956" />

## NOT of 16 bit numbers ALP
```
MOV AX,276DH
NOT AX
HLT
```
## Output
<img width="1642" height="884" alt="image" src="https://github.com/user-attachments/assets/1b4a37f2-9f38-42a2-ac39-ee1660dcb88d" />

## XOR of 16 bit numbers ALP
```
MOV AX,7722H
MOV BX,9754H
XOR AX,BX
HLT
```
## Output
<img width="1642" height="884" alt="image" src="https://github.com/user-attachments/assets/862b9b47-f926-434e-83d2-6bd514372830" />


## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








