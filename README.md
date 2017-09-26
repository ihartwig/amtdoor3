AMT Door 3
==========

This repository houses hardware for the 3rd generation smart lock at Ace Monster Toys in Berkeley, CA. The hardware and software in this repo plus the PoEPi Hat make a single-cable solution for network connected locks.

<img width="500px" src="https://github.com/ihartwig/amtdoor3/raw/master/pcb/amtdoor3-3d-view.png" alt="AMT Door 3 Breakout 3D render"></img>

## Features

* Wide Operation Buck Boost and Automation pHat (WOBBApHAT)
  * RPi Zero-sized pHAT
  * bi-directional level shifting for RFID Reader I/O (UART), PWM, and switch inputs (GPIO)
  * 12-24V strike power from on-board boost or aux input
  * (optionally) 5V RPi power from 12-24V source
  * order at http://dirtypcbs.com/store/designer/details/9832/5763/wobbaphat-for-amtdoor3

## Development Structure

* **docs**: Documentation used in designs.
* **pcb**: WOBBApHAT board to connect RPi Zero with RFID Reader and door strike.
