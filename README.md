# Firebird V Mega 2560 Robot (stk500v2) Arduino Boards Package

**By: Aishwary Raj**

This package adds support for the **Firebird V Mega 2560 Robot (stk500v2)** board to the Arduino IDE via Boards Manager. It configures the board to upload using the STK500v2 protocol and the NEX-USB-ISP programmer used in the lab.

Included files:
- `hardware/firebird/avr/boards.txt`
- `hardware/firebird/avr/platform.txt`
- `hardware/firebird/avr/programmers.txt`
- `hardware/firebird/avr/README.md`

Local installation (quick test):
1. Unzip the package and copy `hardware/firebird/avr` to your Arduino sketchbook hardware folder:
   - Windows: `%USERPROFILE%\Documents\Arduino\hardware\firebird\avr\`
   - Linux: `~/Arduino/hardware/firebird/avr/`
   - macOS: `~/Documents/Arduino/hardware/firebird/avr/`
2. Restart Arduino IDE.
3. Select **Tools → Board → Firebird V Mega 2560 Robot (stk500v2)**.
4. Use **Sketch → Upload Using Programmer** (or Upload) to flash via NEX-USB-ISP.

Boards Manager installation (recommended):
1. Host `package_index.json` and the inner ZIP on GitHub Pages (see instructions).
2. In Arduino IDE: *File → Preferences → Additional Boards Manager URLs* add:
   `https://aishwary2316.github.io/firebird_V_atmega2560_stk500v2_robot/package_index.json`
3. Open Boards Manager, find *Firebird AVR* and Install.
