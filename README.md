# EMG (EEG)
Repo for an EMG project that I did for the final project in the electronics course (PHYS-GA 1500, Electronics for Scientists).

## Introduction

There are so many resources available to make one's own EMG (Electromyography) or EEG (Electroencephalography). 

This is a record of an EMG (rather than EEG at this point, due to the sensitivity issue) based on the online references that I found in spring of 2020. The references are listed at the bottom of this page.

This is something I wanted to try and actually did for an electronics course final project. I will add/update the scripts and detailed design of the circuit later (TBA).

### Parts list/BoM
* Arduino
* Electrodes
* Electronics parts (resistor, capacitor, INA, etc.)

## Design/Software

The PCB board consists of the following parts:

1. Over-voltage protection
1. INA
1. Notch filter
1. high-pass filter and variable gain
1. low-pass filter
1. Right-leg drive
1. -5Vdc circuit
1. DC offset


![design](/images/design.png)

(**FYI**: This circuit is the initial design and not fully functional when tested. I will update the working model.)

## References

* B.Luan, M. Sun, and W. Jia, “[Portable amplifier design for a novel EEG monitor in point-of-care applications](https://ieeexplore.ieee.org/document/6207127),” in 2012 38th Annual Northeast Bioengineering Conference (NEBEC), Philadelphia, PA, USA, Mar. 2012, pp. 388–389, doi: [10.1109/NEBC.2012.6207127](https://doi.org/10.1109/NEBC.2012.6207127)
* cah 6, “DIY EEG (and ECG) Circuit,” on instructables. https://www.instructables.com/id/DIY-EEG-and-ECG-Circuit/ (accessed Apr. 03, 2020)
* “Welcome to the OpenEEG project.” http://openeeg.sourceforge.net/doc/index.html (accessed Apr. 03, 2020)
* B.Luan, “Single-Unit Leadless EEG Sensor,” Jan. 25, 2018. http://d-scholarship.pitt.edu/33387/ (accessed Apr. 05, 2020)
* J.C. Huhta and J. G. Webster, “60-Hz Interference in Electrocardiography,” IEEE Transactions on Biomedical Engineering, vol. BME-20, no. 2, pp. 91–101, Mar. 1973, doi: [10.1109/TBME.1973.324169](https://doi.org/10.1109/TBME.1973.324169)
* M.R. Neuman, “1 6 BIOPOTENTIAL AMPLIFIERS,” 2009
* B.B. Winter and J. G. Webster, “Driven-right-leg circuit design,” IEEE Transactions on Biomedical Engineering, vol. BME-30, no. 1, pp. 62–66, Jan. 1983, doi: [10.1109/TBME.1983.325168](https://doi.org/10.1109/TBME.1983.325168)

