# 🤖 Firebird V Programming Guide

## Overview
This guide provides comprehensive instructions for programming the Firebird V robot using Atmel Studio and flashing code onto the ATmega2560 microcontroller.

## 📋 Prerequisites
- Computer with Windows OS
- Atmel Studio 6
- Firebird V robot
- STK cable

## 🔧 Installation Steps

### 1. Install Atmel Studio 6
- Download from [Atmel Studio Resources](https://elsi.e-yantra.org/resources)
- **Important:** Select the "file include" checkbox during installation

### 2. Set Up Your Project in Atmel Studio

#### Create a New Project
1. Launch Atmel Studio
2. Click **New Project**
3. Choose **GCC C Executable Project**

#### Configure Microcontroller
1. In the project setup window, select **ATmega2560**
2. Click **OK**

### 3. Coding and Building

#### Write Your Code
- Use the code editor to develop your program

#### Build the Solution
1. Click **Build**
2. Select **Build Solution**
3. Verify successful build message

#### Locate Hex File
1. Right-click project name
2. Select **Open Contingency Folder**
3. Navigate to **debug** folder
4. Find your `.hex` file

### 4. Flashing Code to Firebird V

#### Prepare for Flashing
1. Open **AVRDUDE_ATMEGA2560** folder
2. Locate **stkrun.bat**

#### Flash the Code
1. Open Command Prompt in the AVRDUDE folder
2. Type `stkrun` 
3. Provide path to your `.hex` file
4. Connect Firebird V with STK cable
5. Press **Enter** to upload code

## ⚠️ Important Notes
- Install all necessary drivers before flashing
- Ensure Firebird V is powered on
- Verify proper cable connection

## 🚀 Troubleshooting
- Check cable connections
- Verify driver installations
- Confirm correct `.hex` file selection

## 📚 Resources
- [Atmel Studio Official Documentation](https://www.microchip.com/en-us/development-tools-tools-and-software/microchip-studio-for-avr-and-sam-devices)
- [Firebird V User Manual](link-to-manual)

## 🤝 Contributing
Found an issue? Please open a GitHub issue or submit a pull request.

**Happy Robotics Programming!** 🤖👩‍💻👨‍💻
