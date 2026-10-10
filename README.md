# BetaBake_REV_1.0 — Custom i.MX 6ULL Single Board Computer

## 1. Project Overview
**BetaBake_REV_1.0** est une carte SBC (Single Board Computer) personnalisée et conçue de zéro autour du processeur d'application **NXP i.MX 6ULL**. Le projet couvre l'ensemble de la conception matérielle, depuis la capture schématique hiérarchique sous Altium Designer jusqu'au routage et à la préparation des fichiers de fabrication.

---

## 2. Arborescence du Projet (Project Directory Structure)
L'organisation des dossiers et fichiers du dépôt est structurée comme suit :

```text
BETABAKE_REV1.0/
├── .gitattributes
├── Adobe_reader_3D_BetaBake_REV_1.0.pdf
├── BetaBake_REV_1.0.pdf
├── BetaBake_REV_1.0_DRAFTSMAN.pdf
├── Images/
│   ├── 2D/
│   │   ├── BOTTOM_LAYER.png
│   │   ├── INNER_LAYER1.png
│   │   ├── INNER_LAYER_2.png
│   │   ├── PWR_LAYER.png
│   │   └── TOP_LAYER.png
│   └── 3D/
│       ├── IMAGES ALTIUM/
│       │   ├── BetaBake_REV_1.0.png
│       │   └── BetaBake_REV_1.01.png
│       └── IMAGES BLENDER/
│           ├── 1.png
│           └── 4.png
├── PCB/
│   ├── BetaBake_REV_1.0.PcbDoc
│   ├── Copy before routing of BetaBake..PcbDoc
│   └── README.txt
└── SCHEMATICS/
    ├── 01_Boot_Cfg.SchDoc
    ├── 02_DDR3L.SchDoc
    ├── 03_Boot_Memory.SchDoc
    ├── 04_Ethernet.SchDoc
    ├── 05_USB.SchDoc
    ├── 06_CAN_RS485.SchDoc
    ├── 07_Display_LCD.SchDoc
    ├── 08_Debug.SchDoc
    ├── 09_Power.SchDoc
    └── 10_CSI.SchDoc
