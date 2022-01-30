# HybridRadarAD9361
## Introduction
This project tracks the development of a hybrid beamformed linear phased-array radar. The base of the RF chain is the AD9361, which is digitally controlled by a Z7020 FPGA. The phase shifter is based on BGS14PN10 SP4T switched line type shifter.

## Components
* AD9361 2Tx+2Rx transciever, 56 MHz channel bandwidth
* Zynq 7020 FPGA
* BGS14PN10 SP4T based switched line phase shifter

## Specification
* 5.150 GHz - 5.250 GHz
* 2 channel TX/TX, channel bandwidth is 56 MHz max
* 8 element linear patch antenna phased array
* Partially connected hybrid beamforming
