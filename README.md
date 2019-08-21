# QC3.0 to 3.6-20V DC adapter

This adapter controls USB QC3.0 adapters/batteries to generate DC output of 3.6-20V.
Actual output voltage range depends on capability of power source, and it seems most supports 3.6-12V range.

Unlike USB-PD, QC3.0 power source is quite easy to control.
All you need is to control USB D+/D- lines to appropriate level, and send a pulse to raise/lower the output voltage.

# Note on KiCad

Although KiCad v5 is out, this design uses KiCad v4.
KiCad v5 seems to have a library loading issue that stalls whenever I try to load parts model/footprint.
This is really a deal breaker.

# Note on JLCPCB

I'm using JLCPCB to manifacture the board.

To submit the order to [JLCPCB](https://jlcpcb.com/), follow the instruction in the page below:

> How to export Kicad PCB to gerber files
> - https://support.jlcpcb.com/article/44-how-to-export-kicad-pcb-to-gerber-files

> PCB Panelization
- https://support.jlcpcb.com/article/49-pcb-panelization

