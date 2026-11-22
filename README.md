#1 Renault-Visteon-Radio
## This repo is dedicated to the reverse engineering and mapping of the OEM Renault Visteon radio found in the Renault Twingo mk2, Clio 3, Scénic 3, among other models. This to make modifications, low-level repairs, or for general curiosity.

The specimen used is from a 2011 Renault Twingo II Phase 1.(Pre-facelift)

These radio's are commonly found in Renault group products from around the 2010's.
They are compact, low-ish powered radio's featuring a can-bus interface which usually goes paired with a display near the dashboard/instrument cluster. This version came with an LCD style display; there are also Visteon radios which drive a dot-matrix display. I haven't been able to find one to take apart yet.

## Disassembly 
 This process is easy and well-designed. 

#### 1 - Identify and remove 8 torx T9 screws. a T10 will fit but you need to push hard to prevent slippage.

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png

#### 2 - Tilt and pull back cover plate, then tilt and pull back mainboard.
The mainboard has a push-pull style connector to the front panel. This does NOT have any clips. Just pull away and it will come loose. This design is on purpose.
[logo]: 

#### 3 - Identify and remove 4 torx T9 screws

[logo]:

#### 4 - Pull the CD unit sideways, then up and out .

[logo]:

#### 5 - Identify 6 clips

[logo]:

#### 6 - Pull front panel straight off.


(Left to right: Ground, Left, Right)
The radio is powered by an NXP SoC, this one being a SAF7780HL in a LQFP-176 package roughly in the middle of the mainboard.
