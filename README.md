# pcileech-Intel-ISA-Bridge
pcileech emulating an old intel pci-isa bridge from 1997 as a pcie device


Datasheet shows that the BME in the command register should be hardwired to 1. 
Writemask is used to prevent the driver or any other software from writing to the BME.

This is for researching purposes only.
