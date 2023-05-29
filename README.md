# Capstone-Design-Project-in-Power-Electronics
Portable USB Charger

  <p align="center">
    <img src="" width=80% height=80%>
  </p>
  <p align="center">
    Block Diagram
  </p>  
  
  
  ## Project Description
  Design and verify a bidirectional dc-dc converter and its controller, to interface a lithium-polymer battery to a USB device  
  - Supply 5 V at 2 A  
  - Supply 20 V at 3 A  
  - Charge battery at 60 W from 20 V USB source  
  
   [Project Description and Requirement]()  
   
  ___  

  **Milestone 1 Power Stage Design**  
  > Power Stage Design: converter selection, magnetics design, capacitor selection, semiconductor selection.  
  > Demonstrate steady state operation in LTspice.  
  > - Select dc-dc converter topology that is capable of interfacing the 9.6 V to 12.6V battery to the USB at 5 V, 12 V, or 20 V, with bidirectional power flow
  > - Design converter power stage
  > - Demonstrate operation via LTspice simulation
  > - Design inductor or inductors
  >   - Minimize inductor size
  >   - Use LTspicesaturating inductor model
  > - Design capacitors
  > - Select power stage transistors and diodes
  > - In simulation, demonstrate:
  >   - Operation at specified input/output voltages and currents
  >   - Inductor current ripple
  >   - Capacitor voltage ripple
  >   - Efficiency
  
  - [Milestone 1 Requirement](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone1.pdf)
  - [Milestone 1 Report](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/ECEA%205715%20Milestone%201%20-%20Kai%20Tam.pdf)  
  - [Magnetics Design  Tables]()  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/L1%20BodePlot%2064%20Turns%20470uH%20d.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Inductor Bode Plot
  </p>  
  
  ___
  
  **Milestone 2 Initial Controller Design**  
  > Averaged modeling and design of controller.  
  > Demonstrate closed-loop output impedance in LTspice.  
  > - Model converter power stage using averaged model
  > - Select control approach
  >   - Voltage mode
  >   - Peak current mode
  >   - Average current mode
  > - Design feedback loop(s)
  >   - Loop gain design, fc< fs/5
  >   - Compensator circuit design
  >   - Closed-loop output impedance < 0.5 Ω
  > - In simulations, demonstrate:
  >   - Operation at specified input/output voltages and currents (.transimulation)
  >   - Meets closed-loop output impedance requirement (.ac simulation)
    
  - [Milestone 2 Requirement](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone2.pdf)
  - [Milestone 2 Report](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/ECEA%205715%20Milestone%202%20-%20Kai%20Tam.pdf)  
  - [Milestone 2 LTSpice]()  
  
  ___
  
  **Project 3 Open-Loop DC-DC Converter (SEPIC)**  
  > Switching simulation demonstrates closed-loop transient response and regulation in Ltspice.  
  > - Model converter power stage using switching model with your control circuit implemented
  > - Verify that closed-loop system meets load current transient requirements
  > - Add current limiting
  > - Verify inductor size, capacitor size, and efficiency for final design
  > - In simulation, demonstrate:
  >   - Operation at specified input/output voltages and currents
  >   - Closed-loop response to step change in load current
  >   - Closed-loop response to step change in load current

 
  - [Milestone 3 Requirement](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone3.pdf)
  - [Milestonet 3 Report](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/ECEA%205715%20Milestone%203%20-%20Kai%20Tam.pdf)  
  - [Milestone 3 LTSpice]()  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Project%203%20LTSpice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    LTSpice .sch of Averaged SEPIC
  </p>  
  
  ___
  
  ## Pros
  Get the vertical design experience of Solar Power Converter.
  One of the greatest adventage of this lab is scalable, we can later using this as template to build a larger Solar Power Chargers.
  
  ## Cons
  Never got a chance to actually design the PCB based on what I have done on the prototype.
    
  ## Note to Future Development
  If I will do the PCB of this projects, some of the measurement would be better because it would be less ESR and ESL. Switching Noise will be less and efficiency would definitly gone up.
  It would be nice to sell it as a kit for future students.
  
  ## Simulation Program
  - LTSpice

  ## Schematc Capture Tool
  - Altium Designer

  ## PCB
    Reserved
