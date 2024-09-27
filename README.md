# Open Ephys KiCAD Library
[KiCAD](https://www.kicad.org/) parts used in Open Ephys electronics designs.

## Structure
- ./symbols/: KiCAD symbol libaries
- ./footprints/: KiCAD footprint libaries
- ./packages3d/: KiCAD 3D model libaries
- ./packages3d-source/: Editable source for 3D models
- ./sheets/: Drawing sheet templates

## Environment Variables
Define the following path name environment variables to get things to show up correctly:

- OE_3DMODEL_DIR: ./packages3d/	
- OE_FOOTPRINT_DIR: ./footprints/
- OE_SYMBOL_DIR: ./symbols/
- OE_SHEET_DIR: ./sheets/

## Library Name
When importing symbol and footprint libraries into kicad, we use the name "open-ephys"
