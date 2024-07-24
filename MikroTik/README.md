# MikroTik Templates for Zabbix

## MikroTik SFP/SFP+ by SNMP

### Features

- Monitors supply voltage, Rx/Tx power, Tx bias current and temperature.
- Includes triggers for modules temperature, Rx loss and Tx fault.
- Has module Vendor, Serial and Wavelength monitoring options available.
  - To activate, go to Item prototypes for "SFP/SFP+ interface discovery" and enable the options you woud like.

### To-Do

- Make descriptions of the Item Prototypes more useful. Currently just quick descriptions and the MIB info.

- Add filtering to not process interfaces that don't report any statistics.

### Versions

- 0.1a - Initial hacked together version. Heavily inspired by the "MikroTik by SNMP" template.

- 0.2a - Renamed variables from initial coding to be more inline with oter stock templates.

- 0.3a: Initial committed version.
  - Cleaned up description and some variable names.

- 0.4a: Added missing scope tags to trigger prototypes.

- 0.5a: Fixed severity level for RX Loss trigger prototype.

### Templates were tested on the following hardware (RouterOS: 7.x)

- [RB5009UG+S+](https://mikrotik.com/product/rb5009ug_s_in)
- [CRS305-1G-4S+](https://mikrotik.com/product/crs305_1g_4s_in)
- [CRS310-8G+2S+](https://mikrotik.com/product/crs310_8g_2s_in)
- [CSS610-8P-2S+](https://mikrotik.com/product/css610_8p_2s_in)
- [CRS112-8P-4S](https://mikrotik.com/product/crs112_8p_4s_in)
- [cAPGi-5HaxD2HaxD](https://mikrotik.com/product/cap_ax)
- [RB960PGS](https://mikrotik.com/product/RB960PGS)