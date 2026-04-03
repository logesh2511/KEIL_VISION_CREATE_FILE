STEP BY STEP FOR NEW USER HOW TO CREATE A NEW PROJECT IN KEIL AND HOW TO DO DEBUG IN KEIL VISION

Keil µVision Project Setup Guide

Overview

This document provides a step-by-step guide to creating and running a new project in Keil µVision for ARM Cortex-M7 processors. It is useful for beginners working with embedded systems and assembly programming.


Requirements
- Keil µVision IDE installed
- ARM Cortex-M7 support (CMSIS)
- Basic knowledge of Embedded Systems / Assembly Language

  
Steps to Create a New Project


Create New Project:
Go to Project → New Project, choose folder and give project name.


Select Target Device:
Search for ARM Cortex-M7, select ARMCM7, click OK.


Configure Project:
If not using startup file → Click OK.
Else select CMSIS → CORE and Device → STARTUP.


Add Source File:
Right-click Source Group → Add New Item → Select ASM File (.s) → Name and Add.


Write Code:
Open .s file and write assembly code.


Build Project:
Click Build and fix errors if any.


Debug Configuration:
Go to Options for Target → Debug → Enable Use Simulator.


Run & Debug:
Start Debug Session. Use Run, Step, and Reset options.


Monitor Outputs:
Check Registers tab and Memory tab.
