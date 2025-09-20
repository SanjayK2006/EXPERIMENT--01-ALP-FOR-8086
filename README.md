<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bbdda03e-73ef-4e36-8a0e-e3e4aafbc870" /><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/db7abdeb-e493-45ef-9c30-316ed362c033" /># EXPERIMENT--01-ALP-FOR-8086
## Name :SANJAY K
## Roll no : 212223220094





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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
### CODE
```
org 100h


MOV AX, 1234h   
MOV BX, 1111h   

ADD AX, BX 

ret

```



## Output  
<img width="1920" height="1080" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/f585e599-b9da-4982-988d-5f416ba4f357" />

 
## Subtraction   of 8 bit numbers  ALP
### CODE
```
org 100h


MOV AX, 1234h   
MOV BX, 1111h   

sub AX, BX 

ret
```
 
## Output  
<img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/e187cb01-4385-4257-aa2a-d9a711ad49a0" />

## Multiplication alp 
### CODE
```
org 100h


MOV AX, 0012h   
MOV BX, 0003h   

MUL BX   

ret
```
## Output  
<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/43788d4d-870a-43d9-b2cb-ffd6e24aab9e" />


## Division alp 
### CODE
```
org 100h


MOV AX, 1234h  
MOV BX, 0010h   
XOR DX, DX       

DIV BX        

ret
```
## Output  
<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/0f143a47-2725-429e-b6c8-1285b2b6d038" />

## AND
### CODE
```
org 100h

MOV AX, 1234h   
MOV BX, 00FFh   

AND AX, BX      

ret
```
## Output
<img width="1920" height="1080" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/cdf384e7-8512-45ee-8bc9-5de38570958f" />

## OR
### CODE
```
org 100h
MOV AX, 1234h   
MOV BX, 00FFh   

OR AX, BX          

ret
```
## Output
<img width="1920" height="1080" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/05ed9894-68d6-40cf-bd5f-76e28971ad73" />

## X-OR
### CODE
```
org 100h
MOV AX, 1234h   
MOV BX, 00FFh   

XOR AX, BX           

ret
```

## Output
<img width="1920" height="1080" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/721e72a7-013d-4b4d-90ec-d776b1a902f1" />

## NOT
### CODE
```
org 100h
MOV AX, 1234h   

NOT AX           

ret
```
## Output
<img width="1920" height="1080" alt="Screenshot (115)" src="https://github.com/user-attachments/assets/fbe4626a-f01c-422c-9441-33d1eb06dcb8" />






## Result :
Thus, to write and execute ALP on fundamental arithmetic and logical operations is successfully executed
 








