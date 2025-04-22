# EXPERIMENT 01 ALP FOR-8086
Name :MANOJ M
Roll no :212223230122
Date of experiment :11.3.25





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
```
MOV AX, 04ABAH  
mov BX, 04ABCH 
add AX,BX
mov CX,AX
ret
```


## Output  
![Screenshot 2025-03-11 050501](https://github.com/user-attachments/assets/b4c95197-671b-48eb-810a-3ab7dcd42271)
 
## Subtraction   of 8 bit numbers  ALP 
 ```
mov AX,[5000H]
mov BX,[5001H]          
sub AX,BX
mov [6010H],AX
ret
```
## Output 
![Screenshot 2025-03-11 050532](https://github.com/user-attachments/assets/7bb9d035-6b0c-48cb-a257-600ad3beca22)

## Multiplication alp 
```
mov BX,4444H
mov AX,BX
mov CX,3333H
mov DX,CX
mul DX
mov [6020H],AX
ret
```
 ## Output  
![Screenshot 2025-03-11 050551](https://github.com/user-attachments/assets/ac11e139-fb3a-4ae0-af7f-ad780384bf64)


## Division alp 
```
mov BX,5005H
mov AX,[BX]
mov CX,05H
div CX  
mov [6030],AX
ret
```
## Output  
![Screenshot 2025-03-11 050631](https://github.com/user-attachments/assets/44acf03d-6c84-4045-bf40-8ca0c5cd2bc5)

## Bitwise AND
```
MOV AL, 5AH  
MOV BL, 37H  
AND AL, BL
```
## output
![Screenshot 2025-03-11 052540](https://github.com/user-attachments/assets/8f7ad12f-ae90-4bc4-95de-cf8c79ca63f6)

## Bitwise OR
```
MOV AL, 5AH   
OR AL, BL
```
## output
![Screenshot 2025-03-11 052601](https://github.com/user-attachments/assets/5842480b-8f5e-4003-8a56-f30fa93a4996)

## Bitwise XOR
```
MOV AL, 5AH   
XOR AL, BL
```
##  output
![Screenshot 2025-03-11 052620](https://github.com/user-attachments/assets/9eedebac-39fe-4444-bc32-58aa55e0450f)

## Bitwise NOT
```
MOV AL, 5AH  
NOT AL
```
## output
![Screenshot 2025-03-11 052634](https://github.com/user-attachments/assets/156e01bf-d2a9-48d4-b42b-7ac4185732fd)

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed. 








