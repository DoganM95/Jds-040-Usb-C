# DS4-UsbC-Mod

Custom pcb to replace Dualshock 4's micro b port with usb c (PD compatible). It was made to replace the jds-040 model but might be a compatible replacement for other models.

<table>
  <tr>
    <td><img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/ba1c8847-5bf2-4835-9569-e061a3e7da26" alt="USB-C PCB Bottom View" style="width:100%; width: 500px;" /></td>
    <td><img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/dc7a516c-05b3-4503-b699-14db82dd3720" alt="USB-C PCB Top View" style="width:100%; width: 500px;" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/2156dd19-5f74-4983-b0be-04cec12e4c07" alt="USB-C PCB Top View" style="width:100%; width: 500px;" /></td>
    <td><img src="https://github.com/DoganM95/DS4-UsbC-Mod/assets/38842553/dac39760-7246-4728-9780-7458eb919624" alt="USB-C PCB Bottom View" style="width:100%; width: 500px;" /></td>
  </tr>
</table>

## FPC pinout

Starting with the pin that is closest to the charge port and ending with the pin that is closest to the led's:

1. GND
2. GND
3. D +
4. D -
5. GND
6. GND
7. Green LED (3V3_G)
8. Red LED VCC (2V2_G)
9. Blue LED VCC (3V_G)
10. LED VCC
11. USB 5V
12. USB 5V

## Key features
- Usb C port (with D+ and D-)
- Compatible with power delivery (communicates to get 5V)
- Compatible with any 5V usb port
- Uses easily accessible components (Aliexpress)
- Dual RGB led's

## Parts
- PCB: Get the latest gerber zip in releases and order it from Jlcpcb, with 1mm PCB thickness
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
