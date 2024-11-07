# PCB

Board size: 50.0x50.0 mm (1.97x1.97 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |               |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      |                  |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |               |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.3 mm (12 mils)

- By design rules: 0.0 mm (0 mils)

Drill: 0.4 mm (16 mils)

- Vias: 0.4 mm (16 mils) [Design: 0.4 mm (16 mils)]
- Pads: 3.3 mm (130 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.6/0.3 mm (24/12 mils)

- By design rules: 0.5/0.3 mm (20/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 115 (thru: 115 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.1 mm (4 mils)

- By design rules: 1.15 mm (45 mils)

Eurocircuits class: 6C
- Using min drill 0.35 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 3/0 (SMD)
- Bottom: 20/0 (SMD)

Defined tracks:

- 0.3 mm (12 mils)
- 0.5 mm (20 mils)

Used tracks:

- 0.3 mm (12 mils) (70) defined: yes
- 0.5 mm (20 mils) (34) defined: yes

Defined vias:


Used vias:

- 0.6/0.3 mm (24/12 mils) (Count: 115, Aspect: 2.7 A) defined: no

Holes (excluding vias):

- 3.2 mm (126 mils) (4)

Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.4 mm (16 mils) (115)
- 3.3 mm (130 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Top    |              84 |      36.55 |      0.18 |
| Bottom |              53 |      70.45 |      0.35 |
| Total  |             137 |     107.01 |      0.53 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



