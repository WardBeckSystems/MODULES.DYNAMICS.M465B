# M465B Reverb Module · Dynamics

Ward-Beck Systems M465B, 1982|15. Wiki page: [M465B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M465B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 18 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 8 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 10 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 15 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1982 - M465B - p4.jpg](MANUALS/1982%20-%20M465B%20-%20p4.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 15 dB t 0.5 dB |
| **Frequency response** | 0.25 dB form 20 Hz to 20 kHz |
| **Noise** | 80 dB S/N, |
| **Harmonic distortion** | Less than 0.25 % THD from 20 Hz to 20 kHz a 724 dBm output or less. Less then 0.17 at kHz at +24 dBm output or less |
| **Source impedance** | 600 ohms or Tess, balanced |
| **Input impedance** | 600 ohms; balanced |
| **Input levels** | -10 cBm nominal, +30 dBm maximum. |
| **Output impedance** | Less {nan 200 ohms, balanced |
| **Load impedance** | 3,000 ohms minimum; each output, balanced. |
| **Output levels** | -10 dBm nominal, +28 dBm maximum |
| **Phasing** | Input and output terminals designated by numbers are in phase. |
| **Power requirements** | 25 volts dc 25 mA nominal, 50 mA maximum. +24 volts dc 50 mA |
| **Ambient temperature** | to 60 degrees C |
| **Dimensions** | 1.6&quot; wide X 7&quot; high X 6.5&quot; deep. (41mm X 178mm X 165mm) |

## Circuit description

From [1982 - M465B - p5.jpg](MANUALS/1982%20-%20M465B%20-%20p5.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M465B REVERB MODULE is designed to be used in conjunction with an external reverberation chamber and allows the Line level Reverb Return signal to be distributed throughout the mixing console system.

**INPUT AND FADER**

The input signal is applied to edge connector pins 16 IT and routed to the CH ON switch, SW15. This is also the pickup point for the PFL output. Following the CH ON switch, the signal goes to the 600 ohm balanced fader via pin 15 Is. This is also the pickup point for the prefade FB RS and PA outputs The fader output is returned to the module on pins 14 [R. 8-109 BOOSTER AMPLIFIER This amplifier operates with gain of 15 dB and recovers the nominal 15 dB &quot;in-hand&quot; loss incurred by the fader and develops sufficient additiona power 10 drive the PAN and output circuitry

**DIRECT OUTPUT**

The DIRECT output appears at pin 17 [u with of -10 dBm/600 ohms. nominal output level

**LEFT AND RIGHT OUTPUTS**

The output signa of the 8-109 amplifier is routed via PAN switch SW14, and PAN control R17 through R20, to the LEFT and RIGHT outputs at pins 13 IP and pins 12 IN respectively

**AUXILIARY OUTPUTS**

In addition SOLO output is available via SW12, to allow selective monitoring of the particular Reverb channel _ Other feeds originating from the 8-109 amplifier are supplied to the RS, FB and PA POSTFADE channels PRE/PosT SELECTOR SWITCHES AND LEVEL CONTROLS PRE/poST selection of the RS, FB and PA channels is facilitated by switches SW5, SwB/SW11 and SW2 respectively _ Each switch is followed by its associated level control The outputs of the level controls are fed to the summing outputs via individual assignment switches

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVdxTWRaWU5yZ28/view?resourcekey=0-FxLLVudtyliSTiSM2a_Sgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVdxTWRaWU5yZ28&resourcekey=0-FxLLVudtyliSTiSM2a_Sgg" width="240" alt="1982 - M465B - 465-04-007 - FRONT PANEL LAYOUT.jpg"></a><br><sub>1982|15 · 465-04-007 - FRONT PANEL LAYOUT · <a href="MECHANICAL/1982%20-%20M465B%20-%20465-04-007%20-%20FRONT%20PANEL%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRW80MThHWnQya00/view?resourcekey=0-O92fmmWcaC2PZJFWmfURMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRW80MThHWnQya00&resourcekey=0-O92fmmWcaC2PZJFWmfURMQ" width="240" alt="1982 - M465B - 465-02-003 - COM REVERB MODULE.jpg"></a><br><sub>1982|15 · 465-02-003 - COM REVERB MODULE · <a href="SCHEMATICS/1982%20-%20M465B%20-%20465-02-003%20-%20COM%20REVERB%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEtnRjBiZ0ZOSjg/view?resourcekey=0-wgNYzJGNQVz3gwvdtw_nCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEtnRjBiZ0ZOSjg&resourcekey=0-wgNYzJGNQVz3gwvdtw_nCA" width="240" alt="1982 - M465B - B 465-01-003 - M465B - REVERB MODULE - FUNCTIONAL.jpg"></a><br><sub>1982|15 · B 465-01-003 - M465B - REVERB MODULE - FUNCTIONAL · <a href="SCHEMATICS/1982%20-%20M465B%20-%20B%20465-01-003%20-%20M465B%20-%20REVERB%20MODULE%20-%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnpMSmU5YlYyamM/view?resourcekey=0-86-DiiLvVxmxUcNHe78IoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnpMSmU5YlYyamM&resourcekey=0-86-DiiLvVxmxUcNHe78IoQ" width="240" alt="1982 - M465B - B 465-06-002 - M465B - REVERB MODULE - COMPONENT LAYOUT.jpg"></a><br><sub>1982|15 · B 465-06-002 - M465B - REVERB MODULE - COMPONENT LAYOUT · <a href="SCHEMATICS/1982%20-%20M465B%20-%20B%20465-06-002%20-%20M465B%20-%20REVERB%20MODULE%20-%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1gTDP6KmDprYwzDE0xb_2XKETP8VkspfZ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1gTDP6KmDprYwzDE0xb_2XKETP8VkspfZ" width="240" alt="19xx - M465B - DOC - 465-02-003 - REVERB MODULE SCHEMATIC.jpg"></a><br><sub>19xx - M465B - DOC - 465-02-003 - REVERB MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M465B%20-%20DOC%20-%20465-02-003%20-%20REVERB%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LU_AbXL9kSVxO4iy_4vlDgdO1DCasTKN/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LU_AbXL9kSVxO4iy_4vlDgdO1DCasTKN" width="240" alt="19xx - M465B - DOC - 465-02-003 - REVERB MODULE SCHEMATIC.png"></a><br><sub>19xx - M465B - DOC - 465-02-003 - REVERB MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M465B%20-%20DOC%20-%20465-02-003%20-%20REVERB%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWlNVYl95dE9KdEU/view?resourcekey=0-oEYFWn81lNwpC9fw0SVMbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWlNVYl95dE9KdEU&resourcekey=0-oEYFWn81lNwpC9fw0SVMbg" width="240" alt="1982 - M465B - p1.jpg"></a><br><sub>1982|15 · p1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDJzT245NS14UUk/view?resourcekey=0-cGSwICaJ8eJhdPymz7jkjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDJzT245NS14UUk&resourcekey=0-cGSwICaJ8eJhdPymz7jkjw" width="240" alt="1982 - M465B - p2.jpg"></a><br><sub>1982|15 · p2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0N6bUNzNy1iM00/view?resourcekey=0-9shR1SNkNjnxBRh-ZKEkVA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0N6bUNzNy1iM00&resourcekey=0-9shR1SNkNjnxBRh-ZKEkVA" width="240" alt="1982 - M465B - p3.jpg"></a><br><sub>1982|15 · p3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXFXd1lnMHpEc2c/view?resourcekey=0-hthdej4rzUmdaRM0b-KsdA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXFXd1lnMHpEc2c&resourcekey=0-hthdej4rzUmdaRM0b-KsdA" width="240" alt="1982 - M465B - p4.jpg"></a><br><sub>1982|15 · p4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQy1qU0hEeFVHVEE/view?resourcekey=0-eAbRbOtcHQ7D2dV3EdzJdA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQy1qU0hEeFVHVEE&resourcekey=0-eAbRbOtcHQ7D2dV3EdzJdA" width="240" alt="1982 - M465B - p5.jpg"></a><br><sub>1982|15 · p5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVBZNC0wSlowZVU/view?resourcekey=0-k8_Scx_JJqFjgDjJ1faSnw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVBZNC0wSlowZVU&resourcekey=0-k8_Scx_JJqFjgDjJ1faSnw" width="240" alt="1982 - M465B - p6.jpg"></a><br><sub>1982|15 · p6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmttOEhCampMX00/view?resourcekey=0-1PnOR1bpjsaWVsYOWXDX2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmttOEhCampMX00&resourcekey=0-1PnOR1bpjsaWVsYOWXDX2w" width="240" alt="1982 - M465B - p7.jpg"></a><br><sub>1982|15 · p7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmxWY2NuanRzalE/view?resourcekey=0-EPWLPZAIxrROcOSj6Qx5dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmxWY2NuanRzalE&resourcekey=0-EPWLPZAIxrROcOSj6Qx5dg" width="240" alt="1982 - M465B - p8.jpg"></a><br><sub>1982|15 · p8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTFFWemw5cHdSX1k/view?resourcekey=0-ScF2jLzv3JvRoTgOMRgnxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTFFWemw5cHdSX1k&resourcekey=0-ScF2jLzv3JvRoTgOMRgnxQ" width="240" alt="1982 - M465B - p9.jpg"></a><br><sub>1982|15 · p9</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1982 - M465B - 465-02-003 - COM REVERB MODULE.kicad_sch](KICAD/1982%20-%20M465B%20-%20465-02-003%20-%20COM%20REVERB%20MODULE.kicad_sch)
- [1982 - M465B - B 465-01-003 - M465B - REVERB MODULE - FUNCTIONAL.kicad_sch](KICAD/1982%20-%20M465B%20-%20B%20465-01-003%20-%20M465B%20-%20REVERB%20MODULE%20-%20FUNCTIONAL.kicad_sch)
- [19xx - M465B - DOC - 465-02-003 - REVERB MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M465B%20-%20DOC%20-%20465-02-003%20-%20REVERB%20MODULE%20SCHEMATIC.kicad_sch)
- [M465B.kicad_sym](KICAD/M465B.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
