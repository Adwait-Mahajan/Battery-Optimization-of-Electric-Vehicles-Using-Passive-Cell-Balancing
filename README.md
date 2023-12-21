# Battery-Optimization-of-Electric-Vehicles-Using-Passive-Cell-Balancing & Machine Learning Techniques.
<br>
<br>
INTRODUCTION
<br>
<br>
Giving it to their great performance, Li-ion batteries are the most often used battery in electric vehicles (EVs). Because of their high energy density and specific energy, Li-ion batteries are extremely brittle. As a result, complex electronics are required to ensure that no cell in the pack leaves its safe functioning area. The nominal voltage of a Li-ion cell is 3.7 volts, with a maximum voltage of 4.2 volts and a minimum value of 2.7 volts. If the battery's extreme limits are breached, for example, if any cell is charged higher than 4.2V or discharged lower than 2.7V, it can result in unstable cell states and potentially fire dangers.
<br>
The functions of a BMS are to keep all cells within their pre-set safe operational limits by measuring voltage, current, and temperature, and to communicate with the master controller if any cell is out of bounds so that necessary steps can be taken to bring the cell back to its SOA or to deploy contingencies to prevent fire hazards. A complete BMS will include controlled charging using Constant Current Constant Voltage to ensure that all cells are charged to their full State of Charge, cell balancing techniques to ensure that all cells are at the same voltage after charging, and necessary failsafe and protection circuits to ensure that the user or the vehicle are not harmed if the battery pack performs unexpectedly. The goal of this study is to design and create a passive balancing system that uses Constant Current Constant Voltage charging.
<br>
The Li-ion cell BMS guarantees that the cells in the battery stay within safe operating limits, and it intervenes when a cell exceeds those limits. If the voltage gets too low, a BMS will disconnect load, and if the voltage rises too high, it will separate charges. It will also ensure that each cell in the pack will have the same voltage and will lower the voltage of any cell that is higher than the others. If the lithium cell's voltage rises above 4.0V to 4.5V or falls below 3V, two things can happen: the cell can burst or its life will be reduced. A BMS also regulates and monitors the temperature.
<br>
Cell balancing can be done in two ways: active cell balancing and passive cell balancing. Making the state of charge of each cell equal without dissipating energy through a resistor is known as active cell balancing. Here, energy is passed from one cell to another, from one cell to another. Passive cell_balancing means making the state of charge of each cell equal by dissipating energy through a resistor.
<br>
<br>
METHODOLOGY
<br>
<br>
• Once the circuit is connected each cell has a different state of charge(SOC). On making the cell balancing constant 1, we run the simulation and the cell balancing process starts and once they reach the same level the constant is made 0 to stop this process.
<br>
• Now the source constant is made 1 and the battery pack starts charging. After some time the constant is made 0 to stop charging of the battery pack.
<br>
•After this the load constant is made 1 to start the discharging process. During this process the current in the pack decreases.
<br>
•All the output/graph are obtained from the above processes and are attached below.
<br>
<br>
CONCLUSION
<br>
<br>
In our project we presented the fundamentals and importance of battery management systems using a Li-ion battery pack. This was followed by battery modelling using equivalent circuit and the charge and discharge graph explained with the help of the equivalent circuit model. Then the cell balancing techniques are discussed with major specialise in passive balancing (switched resistor). The trade-offs of using active balancing are discussed so on provides a clear understanding of why passive balancing is chosen.
MATLAB/Simulink modelling of single cell and 3 cells with their charge and discharge graphs are simulated. Finally, the charging method for Li-ion battery packs is discussed and it's highlighted on why this method is that the required to charge Li-ion battery packs.
<br>
Machine learning was also used to enhance the usability of the BMS. The Machine learning model can be incorporated with the BMS which would enable the BMS to make predictions regarding the State Of Charges (SoC) values before the journey of the vehicles even begins. An Artificial Neural Network was used which could do the mentioned task. The mean squared error of the machine learning model turned out to be very less, 0.0115 to be precise. As a result, this machine learning model can be used in the real world scenarios to make predictions. 
