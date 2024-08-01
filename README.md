### Setting Up a System on Chip (SoC) Project in Quartus

To set up a System on Chip (SoC) project in Quartus, follow these steps:

1. **Launch Quartus**: Open the Quartus software from your desktop or applications menu.

2. **License Quartus**: In a university lab, ensure Quartus is licensed. If needed, go to `Tools` > `License Setup` and enter the required license information.

3. **Start a New Project**: 
   - Use the `New Project Wizard` from `File` > `New Project Wizard`. Enter the project name, location, and top-level entity name. Add any existing Verilog files or skip this step if starting from scratch.
   - Select the appropriate FPGA device by choosing the correct family (e.g., Cyclone, Arria) and specific device.

4. **Add Verilog Code**: Create a new Verilog file by going to `File` > `New`, selecting `Verilog HDL File`, and writing or pasting your code. Save the file with a `.v` extension.

5. **Compile the Project**: Start the compilation process by selecting `Processing` > `Start Compilation`. Address any errors that appear.

6. **Assign Pins**: Use the Pin Planner from `Assignments` > `Pin Planner` to assign the correct FPGA pins based on your board's specifications. Save and re-compile the project to confirm correct pin assignments.

7. **SoC Configuration**: For SoC integration, configure additional IP cores and system settings using the Platform Designer (Qsys).

For effective project development, utilize simulation tools like ModelSim for code verification and the SignalTap Logic Analyzer for in-system debugging. Refer to the Quartus user manual and your FPGA board's documentation for detailed guidance and pin configuration. This process ensures a robust and efficient setup for your SoC project in Quartus.
