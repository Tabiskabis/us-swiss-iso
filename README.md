# US keyboard layout with (swiss styled) ISO key
Combine the simplicity of the US keyboard with the usability of the ISO key as typed on the Swiss (and Belgian, Danish, Færoese, Greenlandic, Luxembourgish) layouts.

## Motivation
There is no shortage of very-clever made software out there that just assumes everyone uses the US layout and that's all there is and that's enough.  
Like many games do. Or even remote control software that definitely should know better (like ATEN Supermicro iKVM viewer).  
Using this layout in the latter enables it to correctly and fully use ISO key typed layouts on remote targets.

## Variants

### `kbisgusy.klc`
The ISO key (VK_OEM_102) produces `<` (unmodified), `>` (shift), and `\` (AltGr).

### `kbisgusz.klc`
The same, but with swapped `Z` and `Y` keys (QWERTZ instead of QWERTY).

## Installation
I will not release executable/binary files (and have to deal with code signing).  
Use [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) to build an installer from the .klc file.
