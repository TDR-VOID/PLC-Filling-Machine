# PLC-Filling-Machine


## General Information

### PLC Used: Fatek FBS Series PLC

This project used the Fatek FBS series PLC, a versatile and powerful programmable logic controller ideal for automation tasks. The Fatek FBS series offers a range of features that make it suitable for various industrial applications.

For more detailed information about the Fatek FBS series PLC, including specifications and usage instructions, please refer to the [FBs-PLC User's Manual](https://www.fatek.com/en/download.php?act=list&cid=58).

### Programming Software: WinProLadder

The programming for this PLC was done using the WinProLadder software, which is designed specifically for Fatek PLCs. WinProLadder provides a user-friendly interface for creating and managing PLC programs.

For more information about using WinProLadder, please refer to the [WinProLadder User Manual](https://www.fatek.com/en/download.php?act=list&cid=141).

### Setting Up WinProLadder

To begin programming the PLC, follow these steps to set up WinProLadder:

1. Open WinProLadder.
2. Navigate to File → New Project.
3. Under the Project Information section:
  - Project Name: Enter a name for your project.
  - Model Name: Edit the model name to FBS-24MA.
4. Click OK to create your new project.

### Simulating and Testing the Program

Before uploading the program to the PLC, you can simulate and test it to ensure everything is working as expected:

1. In the WinProLadder interface, navigate to the PLC menu.
2. Select Simulate.
3. Choose RUN PLC to start the simulation.
   
This will allow you to verify the program's behaviour before deployment.

### Installing the Program to the PLC

Once you have verified that the program works as expected, you can install it onto the PLC:

1. Connect the PLC: Ensure the PLC is connected to power and the data cable is connected to your USB port.
2. Install Drivers: Make sure the necessary drivers for the PLC are installed on your computer.
3. Navigate to the PLC menu.
4. Select Online → Autocheck and choose the appropriate COM port.
   
This will upload the program to the PLC, making it ready for operation.



## Project Information

### Overview

This project involves automating a painting filling machine with two different paint colors: Yellow and Blue. The system is controlled by a Fatek FBS series PLC and uses various sensors and valves to manage the paint filling process. The machine operates in three distinct modes, each defining a specific sequence of operations.

### Components and Sensors

- Paint Valves: Two valves control the flow of paint:
    - Valve_Yellow: Controls Yellow paint.
    - Valve_Blue: Controls Blue paint.
- Conveyor Sensors:
    - Job_In_Sensor: Detects when a job (paint bucket) enters the conveyor.
    - Job_Out_Sensor: Detects when a job exits the conveyor.
- Filling Sensors:
    - Yellow_Filling_Sensor: Ensures the paint bucket is correctly positioned under the Yellow         filling valve.
    - Blue_Filling_Sensor: Ensures the paint bucket is correctly positioned under the Blue              filling valve.
- Push Buttons:
    - Start_PB: Starts the filling process.
    - Stop_PB: Stops the process (emergency button).
- Mode Switch: A 3-position switch to select the operating mode.


