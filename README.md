Super Mario
===========
This project implements a simplified version of Super Mario in pure C without any additional graphics library.

For details of the implementation, please refer to my [blog](https://blog.yanchen.im/?p=131). There is also a Chinese but less detailed version [here](https://blog.yanchen.im/?p=161).

Turbo C, which is included in the project in folder TC, and DOSBox are needed to compile and run this program.

A very short video of the game is [here](https://www.youtube.com/watch?v=AubjK0NVTMI). 

To compile and run:

1. Download and install DOSBox
- Mount the root folder of this project as C: in DOSBox
   
   ```
   mount C: /path/to/project
   ```
- Change to drive C:
   
   ```
   C:
   ```
- Change directory to C:/GDC
   
   ```
   cd C:/GDC
   ```
- Compile
   
   ```
   compile.bat
   ```
- Run GDC.EXE
   
   ```
   GDC.EXE
   ```
- Use Ctrl+F12 and Ctrl+F11 to adjust CPU cycles to around 20000
- Wait for around half a minute to load the game
- Enjoy!

#### Developers
- Yan Chen
- Liang Guo
