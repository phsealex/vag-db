# Disable afterwipe of windscreen wipers
### Byte 1
![Bit 3](/common/svg/bitSelectBit3.svg)

Unset **Bit 3** to disable afterwipe, set to re-enable.

# DRL Settings
### Byte 2
![Bit Reference](/common/svg/bitRef.svg)

**Bit 0**: *unused*<br>
**Bit 1**: Toggle DRL on front side markers<br>
**Bit 2**: Toggle DRL on high beams<br>
**Bit 3**: Toggle DRL on fogs<br>
**Bit 4**: Toggle DRL on LED lights<br>
**Bit 5**: *unused*<br>
**Bit 6**: Toggle DRL on side markers<br>
**Bit 7**: Toggle DRL on tail lights<br>

# Disable LED wink on turn signal
### Byte 3

![Bits 2 & 7](/common/svg/bitSelectBits27.svg)

**Bit 2**: Set to enable LED & Parking light full brightness
**Bit 7**: Set to disable LED strip DRL couple with indicators

# Independent High Beam Fog Control
### Byte 4

![Bits 1 & 2](/common/svg/bitSelectBits12.svg)

**Bit 1**: Set to disable front, unset to enable front<br>
**Bit 2**: Set to disable back, unset to enable back<br>

# Permanent Headlights
### Byte 4
![Bit 5](/common/svg/bitSelectBit5.svg)

Set **Bit 5** to enable, unset to disable.

# Disable "Lights On" warning chime
### Byte 5

![Bit 3](/common/svg/bitSelectBit3.svg)

Set **Bit 3** to enable the warning, unset to disable it.

# Disable Amber Corner Lights
> 🇺🇸 Only US cars, check if your A4 has been imported!!
### Byte 10
![Bit 3](/common/svg/bitSelectBit3.svg)

Set **Bit 3** to disable amber side markers. Unset to re-enable.