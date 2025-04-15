🔍 AHB to APB Bridge Verification IP (VIP)
📘 Overview
This project showcases the functional verification of an AHB to APB Bridge using SystemVerilog and UVM (Universal Verification Methodology). The bridge acts as a protocol converter, handling transactions between the high-performance AHB bus and the lower-speed APB bus — both widely used in System-on-Chip (SoC) designs.

🚀 Key Features
🔁 Reusable & Scalable UVM Testbench
Designed a modular, reusable testbench architecture following UVM best practices, suitable for future expansion or reuse.

🎲 Constraint-Based Random Testing
Leveraged constrained-random stimulus generation to explore a wide range of functional scenarios and edge cases.

🛡️ SystemVerilog Assertions (SVA)
Implemented assertions to perform real-time protocol checking and detect violations during simulation.

📊 Functional Coverage
Built functional coverage models to track feature verification and ensure thorough test completeness.

🎯 Verification Objectives
✅ Verify Accurate Data & Control Signal Translation
Ensure correct mapping and transfer of AHB transactions to APB format.

✅ Protocol Compliance
Confirm adherence to AMBA protocol specifications for both AHB and APB.

✅ Edge Case Handling
Validate the design's robustness by testing uncommon and boundary conditions.

