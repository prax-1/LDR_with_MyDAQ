# To Develop a VI in Lab view to detect the presence of light using a Light Dependent Resistor (LDR).

## Project Description

This project aims to demonstrate the detect the presence of light using NI-MyDAQ and an LDR (Light Dependent Resistor). The setup involves creating a voltage divider circuit using a breadboard, LDR, op-amp,
and resistors. The LDR's resistance varies with the intensity of light falling on it, which affects the voltage across it in the voltage divider circuit.

The voltage signal from the voltage divider circuit is fed into the NI-MyDAQ device, which interfaces with a computer. LabView software is utilized to process the signal received from the NI-MyDAQ and 
display the output on the computer screen. In this project, the output simulates the brightness of a light source, with the intensity increasing as the light falling on the LDR increases.

![My_DAQ](/images/mydaq.png)


## Project Components

- NI-MyDAQ: Data acquisition device used to interface between the physical setup and the computer.
- LDR (Light Dependent Resistor): Sensing element that varies resistance based on incident light intensity.
- Breadboard: Used for prototyping and creating the voltage divider circuit.
- Resistors: Used in the voltage divider circuit to create a reference voltage.
- LabView Software: Utilized for signal processing and displaying output on the computer screen.

## <u> Project Setup </u>

1. **Hardware Setup**
  - Connect the LDR and resistors on the breadboard to create a voltage divider circuit.
  - Connect the output of the voltage divider circuit to the input channels of the NI-MyDAQ device.
  - Ensure proper connections and secure wiring to prevent signal loss or interference.
2. **Software Setup**
  - Install LabView software on the computer connected to the NI-MyDAQ device.
  - Set up LabView to interface with the NI-MyDAQ and configure input channels.
  - Develop LabView code to process the signal from the NI-MyDAQ and simulate the brightness output based on the LDR readings.
3. **Testing and Calibration**
  - Test the setup with varying light intensities to calibrate the system.
  - Ensure that the simulated brightness output correlates accurately with the light intensity falling on the LDR.

## Repository Structure

- /LabView_Code : Contains LabView code files for signal processing and output simulation.
- /Documentation : Includes project documentation, circuit diagrams, and setup instructions.
- /Images : Contains images of the project setup, circuit diagrams, and screenshots of the LabView interface.
- /Datasheets : Provide datasheets for components used in the project for reference.

## Contributors

- [Prakhar Gupta](https://github.com/prax-1)
- [Shubham Mehra]()

## License
This project is licensed under the MIT License.

## Acknowledgements
We would like to express our gratitude to the faculty [Dr. Prashanth Vooka](https://iittp.ac.in/dr-prashanth-vooka) and the staff of IIT Tirupati for their guidance and support throughout the project. 
Special thanks to our course instructor for providing valuable insights and resources for the Principles of Measurements course.
