# Cheryl Mainline Kernel v5.13

**Requirements for booting mainline**
* [x] Voltage Regulators - handles power to the different gpios
* [ ] CPU – number of cpus, clustering, cache;
* [ ] Memory – amount and location of available memory
* [ ] Reserved Memory – locations of memory that the kernel should stay out of
* [ ] Timer – provide a mechanism for kernel to wake itself up (via interrupt) after some time.
* [ ] Interrupt Controller – handle interrupts from peripherals (the timer in the simplest case).
* [x] Display Cont Splash - handles bootloader display

**WIP DTS Areas**
- Regulators
- Display Working
- Wifi
- BT 
- CPU
- Memory
