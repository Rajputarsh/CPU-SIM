# CPU-SIM
CSA-CPU-Sim-Lab# Computer System Architecture – CPU Sim Lab
Name:- ( Kumar Arsh )
Roll No:- ( 26570032 )
Course / Semester:- Bsc(hons)computer science,semester-1
College	Ramanujan College, University of Delhi
Paper	Computer System Architecture
Simulation of Mano's Basic Computer using CPU Sim 4.0.11 (Java 8 with JavaFX). Each practical has its own folder containing the program (where applicable) and the screenshots of its output.

# Repository structure
CSA-CPU-Sim-Lab/
├── README.md
├── Practical_01_Create_Machine/
│   ├── BasicComputer.cpu        <- the machine used by all other practicals
│   └── screenshots/
├── Practical_02_Fetch_Routine/
│   └── screenshots/
├── Practical_03_ADD/
│   ├── P03_ADD.a
│   └── screenshots/
│   ...
└── Practical_11_Sum_Until_Zero/
    ├── P11_SUM_UNTIL_ZERO.a
    └── screenshots/

  # How to run
      
1.Install Java 8 with JavaFX (for example Azul Zulu JDK FX 8) and download CPU Sim 4.0.11.
2.Start CPU Sim (Cpusim4.bat).
3.File → Open machine… and choose Practical_01_Create_Machine/BasicComputer.cpu.
4.File → Open text… and choose the .a program from the practical's folder.
5.Press Ctrl+2 (assemble and load), then:
6.Ctrl+R to run, or
7.Ctrl+D to enter debug mode and use Step by Instr / Step by Micro.
8.For programs that read input, type a number in the yellow console and press Enter.
9.Example (Practical 3): open Practical_03_ADD/P03_ADD.a, press Ctrl+2, then Ctrl+R, and enter 25 and 17. The console shows


# Notes

1.Practical 2 uses the same machine file as Practical 1; its screenshots show the fetch routine executed one microinstruction at a time .
2.Register values in the debug traces are shown in Unsigned Dec; the RAM pane is shown in Hex.
