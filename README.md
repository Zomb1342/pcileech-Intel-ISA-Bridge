# pcileech-Intel-ISA-Bridge
pcileech emulating an old Intel pci-isa bridge from 1997 as a pcie device

Using Shadow Configuration, Writemask & RW1C Mask to emulate the intel bridge.

This firmware is for researching purposes only.

**Additional Info**

The Intel Bridge being emulated is not capable of generating interrupts & does not utilize any BAR space.

I have added PM & PCIE Caps to make this device compatible with modern systems and ensure proper linking.
