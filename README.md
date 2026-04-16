# MUX-Firmware-Release-PIC

PIC firmware releases for TitanMUX subsea multiplexer.

## Firmware Modules

| File | Target | Description |
|------|--------|-------------|
| MotherboardPIC.hex | Power Motherboard | Main PMB PIC microcontroller |
| DCSwitchPIC.hex | DC Switch | DC switching module (I2C slave) |
| ACSwitchPIC.hex | AC Switch | AC switching module (I2C slave) |
| EarthLeakagePIC.hex | Earth Leakage | Ground fault detection module (I2C slave) |

## Release Naming

Releases are tagged as `PIC-vX.XX` (e.g. `PIC-v1.10`). All four hex files are included as assets under each release tag.
