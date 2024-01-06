# JiffyDOS-Color-Patch
Patch for JiffyDOS 6.01 to change default colors

## Description

This is a binary patch that will modify the JiffyDOS 6.01 ROM for the C64 to be more friendly on the eyes (and our aging CRTs), by changing the border and background colors to black and the text to white. Also modified the start screen to be a little more colorful (see screenshot below), with a nod to the original screen colors and the Commodore logo. Other than those minor changes, this is still 100% the stock JiffyDOS 6.01 ROM, no other modifications or "enhancements" were made.

## Installation

You must already own the JiffyDOS (https://www.c64-wiki.com/wiki/JiffyDOS) 6.01 ROM to use this patch. You can find more information on purchasing JiffyDOS from an authorized Sales channel here: 

https://www.go4retro.com/products/jiffydos/

To apply the patch, use the xdelta tool. This is available in most Linux distributions natively, simply install using your distro's package manager (e.g. dnf install xdelta). For Windows you can download xdelta here:

https://github.com/jmacd/xdelta-gpl/releases

Use the following command to generate the patched version:
```
xdelta -d -s </path/to/original/JiffyDOS_C64.bin> JiffyDOS_C64-color.patch JiffyDOS_C64-color.bin
```
You can then use the patched ROM file with the emulator of your choice (e.g. VICE). Or on real hardware, using one of the many cartridges that allow you to change ROMs, or even burn it to an EPROM and swap the Kernal ROM chip.
## Screenshots
<table>
  <tr>
    <td align=center width=50%>
      <img src="https://github.com/skielek/JiffyDOS-Color-Patch/blob/main/JiffyDOS-Color-Patch-Monitor.png?raw=true" width=50% height=50% />
    </td>
    <td align=center width=50%>
      <img src="https://github.com/skielek/JiffyDOS-Color-Patch/blob/main/JiffyDOS-Color-Patch.png?raw=true" width=50% height=50% />
    </td>
  </tr>
</table>
