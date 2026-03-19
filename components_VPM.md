# Overview

- Source Vehicle: 2022 Rivian R1S
- Source Module: 2022 Rivian AXM 1.0
- PCB: VPM (ACM daughterboard)

# VPM - Components

Side A:
- U11 - Micron 4Gb (512MB) DDR3 SDRAM
	- 2LP47 D9SHM
	- RV86
	- Decoded Part Number: MT41K256M16TW-107 AAT:P
	- https://www.micron.com/products/memory/dram-components/ddr3-sdram/part-catalog/part-detail/mt41k256m16tw-107-aat-p
- U12 - Marvell/Infineon BRIGHTLANE 10/100/1000 Mbps Ethernet Transceiver
	- Marvell
	- 88EA1512-NNP2
	- PFX1800.28
	- 2147 B2P
	- TW
	- Despite being branded Marvell, it seems like this specific product is an Infineon product?
	- https://www.infineon.com/products/ethernet/automotive-phy/88ea1512
	- https://www.infineon.com/assets/row/public/documents/10/45/brightlane-88ea1512-10-100-1000mbs-phy-media-convertor-pb.pdf
- U13 - TI Dual FPD-Link III Deserializer Hub with MIPI CSI-2 Outputs for Cameras and RADAR
	- UB954Q
	- TI 27I
	- AVHK G4
	- www.ti.com/lit/ds/symlink/ds90ub954-q1.pdf
- U14 - NXP S32V234 Quad-Core ARM Processor
	- "S32V MPUs for Front/Surround View Camera, Computer Vision"
	- 1x ARM Cortex-M4, 4x ARM Cortex-A53
	- FS32V234COVUB
	- SBDH2221
	- 1N81U SPAKSBI
	- https://www.nxp.com/part/FS32V234CON2VUB
- U16 - Micron 4Gb (512MB) DDR3 SDRAM
	- 2LP47 D9SHM
	- RV86
	- Decoded Part Number: MT41K256M16TW-107 AAT:P
	- https://www.micron.com/products/memory/dram-components/ddr3-sdram/part-catalog/part-detail/mt41k256m16tw-107-aat-p
- U17 - Micron 64Gb (8GB) eMMC Flash Storage
	- 2OA2D JWC63
	- BBFF
	- Decoded Part Number: MTFC8GAMALBH-AAT
	- https://www.micron.com/products/storage/managed-nand/emmc/part-catalog/part-detail/mtfc8gamalbh-aat
	- https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/8719/auto-emmc-8-128gb-5-11.pdf
- U18 - TI Sink and Source DDR Memory Termination Regulator
	- PSNQ
	- TI 1AK
	- D266
	- https://www.ti.com/lit/ds/symlink/tps51200-q1.pdf
- U29 - Analog Devices 5V, 10A Synchronous Step-Down DC/DC Converter
	- LHCN
	- I860
	- v209
	- Unsure of exact model, there are at least 6 different model DC/DC converters made by Analog that are simply labeled "LHCN"
	- https://www.alldatasheet.net/view_marking.jsp?sField=4&Searchword=LHCN&list=15

Side B:
- U23 - TI Quadruple 2-Input Positive AND Gate
	- HA08Q
	- 1AK G4
	- D2KS
	- Not sure on the exact part number - something in the SN74AHC08Q family
	- https://www.ti.com/lit/ds/symlink/sn74ahc08q-q1.pdf