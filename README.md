# 16-Bit-Active-Level-Shifting-Board

This repository contains a 16-bit active level shifting board designed to interface a 16-bit adiabatic MIPS with a Virtex-7 VC707 FPGA. Active level shifting was required to convert the FPGA's 0 to +1.8V logic to the microprocessor's -0.6 to +0.6V logic. Comparators and a direction control unit was chosen for this purpose.

# Details

Schematic File:
  - 1-bit level shifting design block replicated 16 times
  - Power design block for regulated +/-1.5V and +3V
  - Direction controlling design block
  
Board File:
  - 2 layer board
  - 2 columns of 8 level shifting design blocks
  - 24-pin Molex ribbon cable connectors for input/output
  
# Design

### 1-Bit Active Level Shifter
<p align="center">
  <img src="https://github.com/richardmcmanusjr/16-Bit-Active-Level-Shifting-Board/blob/main/1-Bit.png" width="800">
</p>

# Layout 

### mainboard-01-8x2+1c.brd
<p align="center">
  <img src="https://github.com/richardmcmanusjr/16-Bit-Active-Level-Shifting-Board/blob/main/LogicLevelShifter_V3_8x2_Inline/mainboard-01-8x2%2B1c_eagle.png" width="800">
</p>

### mainboard-01-8x2+1c OSHPARK
<p align="center">
  <img src="https://github.com/richardmcmanusjr/16-Bit-Active-Level-Shifting-Board/blob/main/LogicLevelShifter_V3_8x2_Inline/mainboard-01-8x2%2B1c_OSHPARK.png" width="800">
</p>
