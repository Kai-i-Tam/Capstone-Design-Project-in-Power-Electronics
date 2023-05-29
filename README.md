# Capstone-Design-Project-in-Power-Electronics
Portable USB Charger

  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Block%20Diagram.JPG" width=50% height=50%>
  </p>
  <p align="center">
  Figure 1. Block Diagram
  </p>  
    
  ## Project Description
  Design and verify a bidirectional dc-dc converter and its controller, to interface a lithium-polymer battery to a USB device  
  - Supply 5 V at 2 A  
  - Supply 20 V at 3 A  
  - Charge battery at 60 W from 20 V USB source  
  
   [Project Description and Requirement](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Project%20Description%20and%20Requirement.pdf)  
   
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
  - [Milestone 2 LTSpice](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone1_Kai_Tam.zip) 
  - [Magnetics Design  Tables](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Magnetics%20Design%20%20Tables.pdf)  
  - [Datasheet - MOSFET Infineon BSC010N04LSI](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/67967a664b43d9702dd0d2dd48674d54cd54751c/Infineon-BSC010N04LSIATMA1-datasheet.pdf)  
  - [Datasheet - Current Sensor Maxim Integrated MAX4376TAUK+T](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/67967a664b43d9702dd0d2dd48674d54cd54751c/Maxim_Integrated-MAX4376TAUK%2BT-datasheet.pdf)  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone%201.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Figure 2. Power Stage
  </p>  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/516ab6e870aad4529bad6e42804565c08aec1efc/Milestone%201%20LT%20Spice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Figure 3. Open Loop Power stage LT Spice
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
  - [Milestone 2 LTSpice](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/milestone2spice-KaiTam.zip)  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone%202%20LT%20Spice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Figure 4. H-Bridge Synchronous Buck Boost Average Model
  </p>  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone%202%20LT%20Spice%20Inner%20Current%20Loop%20Gain.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Figure 5. Inner Current Loop Gain
  </p> 
  
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
  - [Milestone 3 Report](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/ECEA%205715%20Milestone%203%20-%20Kai%20Tam.pdf)  
  - [Milestone 3 LTSpice](https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/milestone3spice%20Kai%20Tam.zip)  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Capstone-Design-Project-in-Power-Electronics/blob/main/Milestone%203%20LT%20Spice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Figure 6. Final Schematic
  </p>  
  
  ___
  
  ## Pros
  This is a very good example template for fully vertical design of Power Electronic Circuit, work around given Specs and Restrictions.
  Designing Topology, Component Reseach, Magnetic Designs, Modeling and Simulation. 
  
  ## Cons
  Everything is theorectical, the result is heavily depended on how well the math model is.
    
  ## Note to Future Development
  It would be nice to design the PCBA one day and measure the real life performance and compare how close the simulation as.
    
  ## Simulation Program
  - LTSpice

  ## Schematc Capture Tool
  - Altium Designer

  ## PCB
    Reserved
