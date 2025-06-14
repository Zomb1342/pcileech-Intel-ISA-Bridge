# pcileech-Intel-ISA-Bridge
pcileech emulating an old intel pci-isa bridge from 1997 as a pcie device

Using Shadow Config + writemask + RW1C Mask for the full configuration because
the datasheet shows that the BME in the command register should be hardwired to 1 &
I do not know of any other way to prevent the driver/softare from flipping the bme register.

This firmware is for researching purposes only.

**Additional Info**

I have added PM & PCIE Caps to make this device compatible with modern systems and ensure proper linking.
