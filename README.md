# 8X32-Matrix-Build

// For use with Arduino Create Studio - https://create.arduino.cc/editor/

// HARDWARE_TYPE (FC16_HW) in the MD_MAX72xx library

// I have customized an example from the MD_Parola library to make this simple 8x32 LED Might Matrix scroll (L-R)  

// My LED Matrix: Cylewet MAX7219 Dot Matrix Module 4 in 1 Display for Arduino Microcontroller with 5Pin Line CYT1045 

// Used: Arduino Mega 2560, Cylewet MAX7219 Dot Matrix Module, Breadboard, Wires (M-M/F-F/M-F), Arduino Power/USB, Arduino IDE Software

// 3 different libraries used to make my LED Matrix work include <MD_Parola.h> // https://github.com/MajicDesigns/MD_Parola - Download here include <MD_MAX72xx.h> // https://github.com/MajicDesigns/MD_MAX72xx - Download here include <SPI.h> // https://github.com/PaulStoffregen/SPI - Download here

// The rest of the code is a basic setup with parameters - refer to the MD_Parola and MC_MAX72xx documentation for all paramters and switches

// The example I've created has a text block (with "Name, Company") that scrolles over 4 LED Matrixes (4x32) from right to left, marquee style.
