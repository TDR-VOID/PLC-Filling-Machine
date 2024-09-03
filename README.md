# PLC-Filling-Machine


## General Information

### PLC Used: Fatek FBS Series PLC

This project used the Fatek FBS series PLC, a versatile and powerful programmable logic controller ideal for automation tasks. The Fatek FBS series offers a range of features that make it suitable for various industrial applications.

For more detailed information about the Fatek FBS series PLC, including specifications and usage instructions, please refer to the [FBs-PLC User's Manual](https://www.fatek.com/en/download.php?act=list&cid=58).

### Programming Software: WinProLadder

The programming for this PLC was done using the WinProLadder software, which is designed specifically for Fatek PLCs. WinProLadder provides a user-friendly interface for creating and managing PLC programs.

For more information about using WinProLadder, please refer to the WinProLadder User Manual.

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
