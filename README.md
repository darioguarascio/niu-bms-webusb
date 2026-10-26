# NIU BMS over WebUSB

Read a NIU battery BMS (N1S protocol, RS485 9600 8E1) from Chrome on Android with a
CP2102 USB-RS485 dongle and a USB OTG adapter. No app to install.

**Open:** https://darioguarascio.github.io/niu-bms-webusb/

- Live pack voltage, current, SOC, temperatures, cycles and all 17 cell voltages
- Cell balance rating (Δ < 50 mV good, 50–100 mV medium, > 100 mV bad)
- Voltage charts, kept per battery (by BMS serial) in the browser

Wiring: dongle A → battery A, B → battery B, GND → battery GND.
