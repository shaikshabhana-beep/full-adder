# Full Adder using Verilog

## Project Description
A Full Adder is a combinational logic circuit that adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces two outputs:
- Sum
- Cout (Carry Output)

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Files

- full_adder.v
- full_adder_tb.v
- output.png

## Software Used

- ModelSim
- Xilinx Vivado
- Icarus Verilog
- GTKWave (optional)

## How to Run

Compile

```
iverilog -o fulladder full_adder.v full_adder_tb.v
```

Run

```
vvp fulladder
```

Generate waveform

```
gtkwave dump.vcd
```

## Author

Your Name