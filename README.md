# 💻 Computer-architecture
🎓 **Register Number:** 192424081  
🤗 **NAME:** THARANKESWARAN 
## 8085-microprocessor

### 1️⃣ ADDITION
![image](ADDITION.jpg)
```assembly
LDA 8050  
MOV B, A  
LDA 8051  
ADD B  
STA 8052  
HLT  
```
Input 

8050 `1`
      
8051 `2`

Output 

8053 `3`
### 2️⃣ SUBTRACTION
![image](SUBTRACTION.jpg)

```assembly
LDA 8000
MOV B, A
LDA 8001
SUB B
STA 8002
RST
```
Input 

8000 `4`

8001 `5`

Output 

8000 `1`

### 3️⃣ MULTIPLICATION
![image](MULTIPLICATION.jpg)

```assembly
LDA 2200
MOV E, A
MVI D,00
LDA 2201
MOV C, A
LXI H, 0000
BACK: DAD D
DCR C
JNZ BACK
SHLD 2202
HLT
```
Input 

2200 `4`

2201 `2`

Output 

2202 `8`


### 4️⃣ DIVISION
![image](DIVISION.jpg)
