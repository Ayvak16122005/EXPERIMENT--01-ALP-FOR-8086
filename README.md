
# EXPERIMENT--01-ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086

## Name :KAVYA T
## Roll no : 2305003004
## DEPARTMENT: B.TECH ARTIFICIAL INTELLEGENCE AND MACHINE LEARNING
## Date of experiment :  





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
```python
MOV AL,16H 
MOV BL,25H 
ADD AL,BL 
HLT
```
## Output :
![image](https://github.com/user-attachments/assets/9ac48d45-b84f-438d-9445-1aac4f8634d8)

 ## Subtraction   of 8 bit numbers  ALP 
 ```python
MOV AL,19H
MOV BL,26H
SUB AL,BL
HLT
```
## Output:
![image](https://github.com/user-attachments/assets/e26e9e2a-f895-480b-b1dd-782093198d20)

## Multiplication alp 
```python
MOV AL,20H
MOV BL,02H
MUL BL
HLT
```
 ## Output:
 ![image](https://github.com/user-attachments/assets/4f21d7a6-f164-41e8-ae1f-c24ad5b653c8)

 

## Division alp 
```python
MOV AL,02H
MOV BL,12H
DIV BL
HLT
```

## Output 
![image](https://github.com/user-attachments/assets/e99ac4cc-448e-4782-8add-51f4099cd256)


## AND of 8 bit ALP :
```python
MOV AL,22H
MOV BL,32H
AND AL,BL
HLT
```

## Output:
![image](https://github.com/user-attachments/assets/c56f4d18-2135-44c5-a999-c5335c046769)



## OR of 8 bit ALP :
```python
MOV AL,30H
MOV BL,62H
OR AL,BL
HLT
```

## Output :
![image](https://github.com/user-attachments/assets/fee8f9ce-bb1b-4736-962a-1fd45b81bbd4)


## NOT of 8 bit ALP :
```python
MOV AL,60H
NOT AL
HLT
```

## Output :
![image](https://github.com/user-attachments/assets/52141d72-4251-4bfa-a004-12985b39fb22)


## XOR of 8 bit ALP :
```python
MOV AL,14H
MOV BL,24H
XOR AL,BL
HLT
```

## Output :
![image](https://github.com/user-attachments/assets/0b173a1a-45c5-4f31-9b90-d6150721c9fa)

## Result :
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified successfully.
 








