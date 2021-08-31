# NQSMHS

![finished board](https://github.com/g7ltt/NQSMHS/blob/main/NQSMHS-V2-built-small.png)

Home of the D-STAR™ compatible Mini-HotSpot & Not Quite So Mini-HotSpot

Similar to the NQSMHS V1.1x series, the V2 board shares all the same facilities. The only changes are mechanical/cosmetic and with a few circuit flaws repaired.

Features include
Digital COS
DUTCH*Star HSA firmware compatible
"Satoshi" firmware V4.xx and V5.xx compatible
TTL serial port (for slow speed data)
S:N/RSSI (when used with relevant firmware/software)
USB firmware boot loader (when used with relevant firmware)
PICKit2 ICSP header
The NQSMHS-V2 is available in kit format. Lead time is usually 1 week but may change due to parts availability.

Unlike the 1.1x series of boards firmware is now provided Your board comes supplied with the DUTCH*Star PICBoot bootloader pre-installed. This will enable you to install the DUTCH*Star HSA firmware available from http://www.dutch-star.eu when coupled with the supplied firmware licence key.

REV V2
Nothing to report. All works as planned (when did that ever happen?!)

Please refer to the DUTCH*Star documentation for instructions on installing the firmware and drivers.

DIP switch settings are as follows;
SW1 (power)          Left = USB powered     Right = external 12V powered
PROG            installed = force bootloader mode
SW3               installed = RSSI enabled
SW4                       Left = RSSI enabled       Right = RSSI disabled
 Board layout, schematic and parts list can be found here.

MODS
Some users report very low transmit data levels emitting from the board. A quick fix for this is to cut the right leg of the TX pot.

Some users have reported that the PTT remains keyed long after the data has gone. This appears to be RF feedback holding the PTT transitor open. Place a 100pF (101) cap between the base of Q2 ground.
