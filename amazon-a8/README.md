
# Amazon air purifier A8

## Power supply: Kingdrive KDP24W-04A

* Manufacturer: Dongguan Kingdrive
  * www.kingdrive.net
* 12VDC, 2000mA

### Primärseite

* F1
* CX1: X-Kondensator, 220nF
* LF1: Filter-Drossel
* MOV1 (n.b.)
* U1: Schaltregler, SPT SP6659P
  * https://www.mouser.com/datasheet/2/146/sp6659-1664285.pdf
  * https://www1.futureelectronics.com/doc/EXAR/SP6659EK1-L.pdf
* BD1: Gleichrichter, Sy ABS210
  * https://www.digikey.de/de/products/detail/smc-diode-solutions/ABS210/7244766
  * https://www.smc-diodes.com/propdf/ABS22%20THRU%20ABS210%20N1924%20REV.A.pdf
  * https://www.diodes.com/datasheet/download/ABS210.pdf
* RA1, RA2: "205", 
* EC2
* EC3
* C1: Folienkondensator
* CY1, CY2: Y-Kondensatoren
* CY3 (n.b.)
* 

### Sekundärseite

* T2
* U2: Optokoppler, ORPC 817C
  * Dongguan You Feng Wei Electronics
* LF2: Filter-Drossel
* C3: "102 1kV"
* EC4, EC5: 16V, 1000uF
* D3: XS MBR10100CT, Schottky Rectifier, 100V, 10A
  * https://goodarksemi.com/docs/datasheets/schottky_rectifiers/MBR10100CT-MBRF10100CT.pdf
  * https://www.diodes.com/datasheet/download/MBR10100CT.pdf
* D4: n.b.
* U3: CY T431A, SOT23-3, Spannungsregler
  * https://cdn.badcaps-static.com/pdfs/96894af383be84906219609172a6d6c3.pdf
  * http://www.secosgmbh.com/datasheet/products/Shunt_Regulator/SOT-23/TL431A.pdf
  * https://www.ti.com/lit/ds/symlink/tl431.pdf



