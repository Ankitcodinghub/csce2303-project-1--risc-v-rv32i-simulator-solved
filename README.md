# csce2303-project-1--risc-v-rv32i-simulator-solved
**TO GET THIS SOLUTION VISIT:** [CSCE2303 Project 1- RISC-V RV32I Simulator Solved](https://www.ankitcodinghub.com/product/csce2303-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118637&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCE2303 Project 1- RISC-V RV32I Simulator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Project Overview: The goal of this project is to implement a functional RISC-V simulator capable of tracing the execution of RV32I instructions. This document details the requirements of the simulator.

Implementation language: Any general-purpose programming language. The resulting application can either be a console application or a graphical user interface (GUI) application (desktop, web-based, or mobile app) as a bonus feature.

Team Size: 2 or 3 students

Instruction Set Architecture (ISA): The simulator must support the RV32I base integer instruction set according to the specifications found here: https://riscv.org/technical/specifications. All forty user-level instructions (listed in page 130 of the RISC-V Instruction Set Manual – Volume I: Unprivileged ISA and explained in Chapter2 of the same manual) must be implemented as described in the specifications except ECALL, EBREAK, and FENCE instructions. Instead, your implementation should interpret any of these 3 instructions as a halting instruction that ends the execution of any program (by preventing the program counter from being updated anymore).

Simulator inputs:

1. Assembly program: The user should be able to input a program to be simulated by specifying a text file that contains the instructions. All input programs should be terminated by one of the 3 instructions interpreted as a halting instruction. The user should also specify the program starting address (where the program’s first instruction should be loaded in the memory).

2. Program data: The user should also specify any data required by the program to be initially loaded in the memory. For each data item both its value and memory address should be specified. This information should also be provided through a text file.

Simulation and simulation outputs: The simulator should start by reading the inputs provided by the user and then it should simulate the input program’s execution by keeping track of the program counter value, the register file contents, and the memory contents. The program should repeatedly output all these values (after each instruction’s execution) until the program ends.

1. To keep track of program counter value, the register file contents, and the memory contents you need to initialize them. The program counter should be initialized to the program starting address as specified by the user. All registers should be initialized to zeros. The memory should also be assumed to be empty except for the locations containing the instructions (which can be ignored unless you intend to implement the assembling to machine code bonus described below) and the locations containing the data values provided by the user.

2. Given that the memory address space is large (4 GBs), you will not be able to keep track of the memory contents by creating an array that can hold 4GBs of data. Instead, you will need to use a data structure that allows to record the contents of relevant memory locations only (along with the addresses of these locations of course). Relevant memory locations include all memory locations initialized through the user’s input and all the memory locations modified by the program through store instructions.

3. Register 0 always contains the value 0. You will need to make sure that no instructions can modify it.

Bonus features:

1. Building the application as a GUI application (either desktop, web-based, mobile app).

2. Implementing and integrating an assembler that will convert the input program into machine code and use these values to properly initialize the corresponding memory locations (which will be displayed as part of the relevant memory locations output).

3. Outputting all values in decimal, binary, and hexadecimal (instead of just decimal which is assumed to be the default)

4. Add support for at least 5 pseudoinstructions (out of the many pseudoinstructions supported by RARS), and at least 3 directives (like .data, .word, and .text).

5. Add support for compressed instructions to effectively support the full RV32IC instruction set except for compressed instructions that do not map to supported instructions according to the requirements above. The compressed instructions are also described in the official specifications mentioned above.

6. Add support for integer multiplication and division to effectively support the full RV32IM instruction set. The integer multiplication and division specifications can also be found in the document above.

7. Including a larger set of test programs (at least 6 meaningful programs) and their equivalent C programs.

Project Report: In addition to your team member names and IDs, the report should include:

1. A brief description of your implementation including any bonus features included.

2. Any design decisions and/or assumptions you made.

3. Any known bugs or issues in your simulator.

4. A user guide showing how to compile and run your simulator including a full simulation example step-bystep with screenshots.

5. A list of programs (and associated data if any) you simulated. You should at least provide 3 programs. The programs must cover all instructions supported and one of them at least must have a loop.

6. Optionally, you can include a section about your experience working on this project. This section will NOT affect your grade in any way.

General Guidelines

• Only one member of each group should submit on Blackboard. The submission should consist of a single compressed folder (zip or rar) which must include the following:

o A journal folder that contains the journal file of each team member. o A source code folder that contains the code you wrote using your chosen programming language. o A test folder that contains all input files (assembly and data files) used for testing.

o A PDF report that contains the information described above.

&nbsp;
