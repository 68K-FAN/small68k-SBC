This is a small 68k SBC based on the EC68000 (QFP).  I am not able to solder such a fine
pitch chip (0.8mm), but my friend, who can, provided the chip soldered on an adapter board
that is mounted on the main board via four 16x2 headers.  It has 2 MB of SRAM, and 128k
of EEPROM, and uses a PLCC version of the 68C681 DUART for two serial ports that run at
34.4k baud.  The compact flash interface is based on an 82C55 PPI.  My version of the SBC
is currently running at 28 MHz.  The on-board 74LS can be replaced with 74HC to gain a few
extra MHz.  It uses an adaptation of the Antonakos monitor, and runs CP/M68k with sixteen
8MB "disks" on the compact flash.  Images of the EEPROMs coming soon.
