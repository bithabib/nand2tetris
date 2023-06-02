# Build a Modern Computer from First Principles: From Nand to Tetris

The "From Nand to Tetris" project is a hands-on, educational endeavor that aims to teach computer science from the ground up, starting with basic logic gates and culminating in the creation of a fully functional modern computer system. The project follows a step-by-step approach, allowing participants to understand the inner workings of a computer by building each component themselves.

The project begins by introducing the concept of logic gates and how they can be combined to create more complex circuits. Participants then progress to designing and implementing elementary logic gates like the AND, OR, and NOT gates using a hardware description language (HDL).

Once the basic logic gates are built, the project moves on to constructing more advanced components such as adders, multiplexers, and memory units. Participants gradually build up their knowledge and skills, eventually creating an arithmetic logic unit (ALU), a central processing unit (CPU), and a memory system.

After constructing the computer's hardware, the project shifts its focus to software development. Participants develop a simple machine language and assembler to write programs that can be executed on their newly built computer. They then move on to designing an operating system, compilers, and higher-level programming languages.

The project concludes with the implementation of a Tetris game, showcasing the capabilities of the computer system participants have built from scratch. By going through this comprehensive process, participants gain a deep understanding of how computers work at both the hardware and software levels, providing them with a solid foundation in computer science.

## Setuping Environment
### 1. Install Java 
```
sudo apt install default-jre
sudo apt install default-jdk
java -version
```
### 2. Download the Nand2Tetris Software Suite https://www.nand2tetris.org/software then copy the zip file to Desktop and extract it. 
````
# open terminal 
cd Desktop/nand2tetris/tools/
# make the file executeable
chmod +x HardwareSimulator.sh
# Now run simulator
./HardwareSimulator.sh
````
### 3. Now you will see and interface where you can upload your hdl file and test file 
