# EXPERIMENT--01-ALP-FOR-8086

Name : VISHWA V

Roll no : 212224110062

Date of experiment : 27-04-2026





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
MOV AL,74H
MOV BL,69H
ADD AL,BL
HLT
```


## Output  
 ![Screenshot 2025-02-28 083119](https://github.com/user-attachments/assets/3d4f0f07-fb87-4e32-bb8d-c3d5d2dbace3)
## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,74H
MOV BL,69H
SUB AL,BL
HLT
```
## Output  
![Screenshot 2025-02-28 083443](https://github.com/user-attachments/assets/59fb8c36-1920-4378-9611-083d2f1f4f08)
## Multiplication alp 
```
org 100h
MOV AL,75H
MOV BL,32H
MUL BL
HLT
ret
```
 ## Output  
![Screenshot 2025-02-28 084501](https://github.com/user-attachments/assets/47c0e819-6ca6-4ca0-96fa-a67fbc489dc0)

## Division alp 
```
org 100h
MOV AL,70H
MOV BL,10H
DIV BL
HLT
ret
```
## Output  
![Screenshot 2025-02-28 085310](https://github.com/user-attachments/assets/9d192f60-580f-4e2e-b364-a9a5ea16c975)

## AND GATE OF 8 BIT ALP:
```
org 100h
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
ret
```
## OUTPUT:
![Screenshot 2025-02-28 085449](https://github.com/user-attachments/assets/2102ce1d-68f8-4a62-bf5b-0d8854dc211a)


## OR GATE OF 8 BIT ALP:
```
org 100h
MOV AL,33H
MOV BL,44H
OR AL,BL
HLT
ret
```
## OUTPUT:
![Screenshot 2025-02-28 085953](https://github.com/user-attachments/assets/a83f45b0-01dc-4de5-b4d0-01f8b4b59371)


## NOT GATE OF 8 BIT ALP:
```
org 100h
MOV AL,65H
NOT AL
HLT
ret
```
## OUTPUT:
![Screenshot 2025-02-28 090356](https://github.com/user-attachments/assets/042fe44d-6ba6-4cd3-ad1b-fc038502d2ec)


## XOR GATE OF 8 BIT ALP:
```
org 100h
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
ret
```
## OUTPUT:
![Screenshot 2025-02-28 091023](https://github.com/user-attachments/assets/e4d10e74-fa8b-49bf-ae28-2a96952ce952)

## Result :
Thus the program has been executed successfully.






