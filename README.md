# Traffic-Light-Controller-with-Real-Time-Wait-Timer-using-Verilog
### **GitHub Project Description: Traffic Light Controller with Real-Time Wait Timer using Verilog**  

#### **📌 Overview**  
This Verilog-based **Traffic Light Controller** simulates a **real-world intersection**, managing **North, East, South, and West traffic signals** using a **Finite State Machine (FSM)**. The system integrates a **real-time wait timer**, displayed on a **7-segment LED**, and operates with precise timing through an **FPGA clock divider**.

#### **🚦 Features**  
✅ **10-State FSM** controlling **4 traffic directions**, each following a **10s Green → 2s Yellow → Red cycle**  
✅ **Clock Divider** that **reduces 50 MHz FPGA clock to 1 Hz**, ensuring real-time transitions  
✅ **4-bit Wait Time Counter** tracking time spent in each state, displayed on a **7-segment display**  
✅ **Testbench (TB) Included**, validating state transitions in **ModelSim/Quartus**  
✅ **Modular Design** with separate modules for **FSM, Clock Divider, and Display Interface**  


#### **🛠 Tools & Technologies Used**  
- **Verilog** (FSM, Clock Divider, Traffic Controller)  
- **ModelSim/Quartus** (Simulation & FPGA Synthesis)  
- **7-Segment Display Integration**  
- **FPGA Board** (Tested on Xilinx/Intel FPGA)  

#### **📌 Future Improvements**  
🔹 Implement **traffic sensors** for dynamic light adjustments  
🔹 Add **pedestrian crossing signals** with push-button input  
🔹 Optimize FSM transitions for **adaptive wait times**  
