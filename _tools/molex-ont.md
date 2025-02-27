---
title: Molex ONT
has_children: false
nav_order: 3
layout: default
---

In some sticks, such as those based on Lantiq chipsets, the serial is exposed in the upper pins of the ONT, in order to read them there are two possibilities:
- the use of an SFP molex ([farnell](https://it.farnell.com/en-IT/molex/74441-0001/connector-sfp-rcpt-20pos-smt/dp/2112385)) to which you solder four wires and remove the other pins, this makes the adapter compatible for a single serial combination
- the use of a board to which the SFP molex is soldered, exposing the main SFP pins

{% include image.html file="ma5671a-root-1.jpg"  alt="Example of how the sfp-ttl adapter" caption="Example of how the sfp-ttl adapter" %}

{% include image.html file="new-root-procedure\board-molex-arduino.jpg"  alt="Example of how the sfp-ttl adapter with a custom board" caption="Example of how the sfp-ttl adapter with a custom board" %}

if you want to make your own board, here are some ideas:


{% include image.html file="board-dupont\top.svg"  alt="Example of how the sfp-ttl custom board" caption="Example of how the sfp-ttl custom board" %}
{% include image.html file="board-dupont\bottom.svg"  alt="Example of how the sfp-ttl custom board" caption="Example of how the sfp-ttl custom board" %}

the components to be soldered are instead:
- 1x MOLEX SFP (like Molex-744410001 [lcsc](https://www.lcsc.com/product-detail/Card-Edge-Connectors_MOLEX-744410001_C277615.html), [farnell](https://it.farnell.com/en-IT/molex/74441-0001/connector-sfp-rcpt-20pos-smt/dp/2112385))
- 2x pinout 2x10 (like [MINTRON MTP125-1210S1](https://www.lcsc.com/product-detail/Pin-Header-Female-Header_MINTRON-MTP125-1210S1_C358699.html))