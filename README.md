# Component Library
Written in System Verilog

Read files for usage
1. [library.sv](./rtl/library.sv)
2. [SSegDisplayDriver.sv](./rtl/SSegDisplayDriver.sv):
   ```systemverilog
   // Module header for Boolean Board
     module SSegDisplayDriver (
        input  logic            clk,
        input  logic            reset,
        input  logic [6:0] HEX0,
        input  logic [6:0] HEX1,
        input  logic [6:0] HEX2,
        input  logic [6:0] HEX3,
        input  logic [6:0] HEX4,
        input  logic [6:0] HEX5,
        input  logic [6:0] HEX6,
        input  logic [6:0] HEX7,
        input  logic [7:0] dpoints,
        output logic [3:0] D1_AN,
        output logic [3:0] D2_AN,
        output logic [7:0] D1_SEG,
        output logic [7:0] D2_SEG
    );
   ```
