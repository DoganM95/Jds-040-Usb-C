# DS4-UsbC-Mod
Custom pcb to replace Dualshock 4's micro b port with usb c (PD compatible). It was made to replace the jds-040 model but might be a compatible replacement for other models.

<img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/2156dd19-5f74-4983-b0be-04cec12e4c07" height="400px">
<img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/dac39760-7246-4728-9780-7458eb919624" height="400px">


## Key features
- Usb C port (with D+ and D-)
- Compatible with power delivery (communicates to get 5V)
- Compatible with any 5V usb port
- Uses easily accessible components (Aliexpress)
- Dual RGB led's

## Parts
- PCB: Get the latest gerber zip in releases and order it from Jlcpcb
- FPC connector (pins:12, pitch:0.5mm. Salvage it from an existing board -> ) https://a.aliexpress.com/_EjykXX1
- Led's (RGB, side view) https://a.aliexpress.com/_EHr7vQn
- Resistors (size:0603, res:5.1kOhm) https://a.aliexpress.com/_EIPYwrH
- USB C (female, pins:16, padding-bottom:0.8mm) https://a.aliexpress.com/_EJhQRSJ

## Tools (recommended next to the obvious)
- Hot plate
- Flux
- Solder wick
- Hot air gun

# Procedure
- Get the salvageable micro b module from aliexpress ready
- Use a hot air gun to desolder the usb micro b port
- Fire up the hot plate & put the pcb on it
- Steal the fpc connector from it
- Get the blank usb c pcb ready
- Solder the fpc connector to it (sides first in good position)
- Solder the usb c port's 4 shell pads in good position
- Solder usb c pins
- Solder solder smd resistors
- Solder smd led's
  - Put solder on the pcb pads
  - Put solder on the led's pads
  - Solder the middle 2 pins first
  - Solder the sides
