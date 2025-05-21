# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

output of nclaunch -new:
![Screenshot 2025-05-21 161007](https://github.com/user-attachments/assets/d5f88a3e-62d0-4c56-8dbd-cddca5aa38db)


Synthesis RTL Schematic :
![Screenshot 2025-05-21 162412](https://github.com/user-attachments/assets/fd10acfe-e9c9-4b8c-87f0-78bae5fcf894)

Area report:
![Screenshot 2025-05-21 163418](https://github.com/user-attachments/assets/4d443e36-c104-471e-b09d-58a45a2d3f0d)

Timing report :
![Screenshot 2025-05-21 163356](https://github.com/user-attachments/assets/4b85c9aa-6f76-4e7f-9ad6-dc5742ddfdb4)

Power Report:
![Screenshot 2025-05-21 163400](https://github.com/user-attachments/assets/aaccef5c-e668-4ec2-9adb-ae27cca5615d)
Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
