# EXPERIMENT 01 ALP for fundamental arithmetic and logical operations in 8086
## Name : Akshaikhanna D
## Roll no : 212223040010
## Date of experiment :10-09-2025





## Aim: To Write and execute ALP for fundamental arithmetic and logical operations in 8086
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







## Programs for arithmetic  operations
```
org 100h
mov ax,5dC2h
mov bx,4adbh
add ax,bx
mov [1000h],ax
mov cx,5b3ch
mov bx,5adbh
sub ax,bx
mov [1002h],ax
mul bx
mov [1004h], ax
div cx
mov [1006h],ax
ret
```


## Output  
<img width="1883" height="740" alt="image" src="https://github.com/user-attachments/assets/73dcc373-4dd2-4104-9d8b-49e74ffdafef" />


## Programs for logical operations
```
org 100h
MOV AX,5000h;
AND BX,1221h;
MOV [1000H],AX;
MOV AX,0A36H;
MOV BX,0B41H;
OR AX,BX;
MOV [1002H],AX;
NOT AX;
MOV [1004H],AX;
XOR AX,BX;
MOV [1006H],AX;
RET
```
## Output
<img width="964" height="852" alt="image" src="https://github.com/user-attachments/assets/47bfd0be-a912-4db8-a6b7-8dcd70e4051e" />

## Result :
Thus, to write and execute ALP on fundamental arithmetic operations and Logical operations is successful.








