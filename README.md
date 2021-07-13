# CrossbarSwitch_dim4

Arbitration algorithm - Round Robin (in scr also can be found Wrapped WaveFront Arbiter - WWFA)

Dimension 4×4 (4  Master Devises and 4 Slave Devices)

Target Device - Arty A7 (xc7a35ticsg324-1L)

Contains **two test modules** - non-Synthesizable (test for Crossbar) file and Synthesizable (stimulus for Crossbar). The last of them is the top-module.

Contains **two constraints files**. File *crossbar_constraints_max_freq.xdc* restricts frequency for the Crossbar itself (the design of crossbar requires little space of FPGA, whats why the main delay goes to achieve the degign)
