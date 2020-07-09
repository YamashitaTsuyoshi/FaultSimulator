# simulator_template
This repository is a template for creating a fault simulator.

# Usage
1. Join GitHub organization (@ehimetakahashilab)
2. Create a repository for implementing your own fault simulator. At this time, select this repository (ehimetakahashilab/simulator_template) as the repository template.

Then feel free to develop!  
For example, you could split the C code, add a Makefile, or implement it in C++ or Rust.

# File & Dir Structure
```bash
$ tree simulator_template
simulator_template/
├── README.md
├── iscas85
│   ├── Faultset
│   ├── Logic
│   ├── Pattern
│   ├── Table
│   └── Testcase
├── iscas89_cs
│   ├── Faultset
│   ├── Logic
│   ├── Pattern
│   ├── Table
│   └── Testcase
├── main.c
├── simulation_result.pdf
└── time.csv
```

## File
- main.c  
template C code
- simulation_result.pdf  
Verification data for fault simulator implementation
- time.csv  
Execution time of the implemented fault simulator

## Benchmark files
- iscas85, iscas89_cs
    - Faultset  
    Fault information
    - Logic  
    Logic simulator results
    - Pattern  
    Pattern to be executed by simulator
    - Table  
    Circuit information
    - Testcase  
    Test case for fault simulator
