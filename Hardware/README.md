# OpeNGEKI
## Hardware

| Version | QR card slots | IC reader | Headphone jack | AC control panel | Simple construction |
| --- | --- | --- | --- | --- | --- |
|**Real**  | Yes | Yes | Yes | Yes | No |
|**Simple**| Yes | Yes | Yes | Yes | Yes |
|**Basic** | No | Optional | Optional | Yes | Yes |

- **Real** - arcade replica design and sizing, intended for enthusiasts making a dedicated setup
- **Simple** - same features as Real, but a simpler geometric construction with a smaller footprint
- **Basic** - no card slots, option IC reader and headphone jack, likely what most users will look for

All versions share the same arcade-accurate control panel, and the same spacing/art is used on each

## Directories

### Art - 2D
Contains Adobe Illustrator files `.ai` for the control and card panels

In addition to working with the 3D models, these are all you need to make a fully handmade controller

`/Art - 2D/Fonts` contains font files used in the Illustrator documents

In order to make revisions easier, text is not converted to outlines, so install these first

### Models - 3D

**Not yet added.**

Contains Fusion 360 archives `.f3z` of each controller variant

It's recommended to make a new folder for the project in Fusion, then simply import the file (it will dump a lot of parts)

All sub-assembiles (components/parts) will be imported, and can be individually edited or exported as needed

**Planned:** subdirectories for each variant, with BOM and clear description of the design

**Note:** Only the wall/side buttons will have pre-exported `.stl` files (for now)

For other components, you can modify/export them yourself in whatever format your tools/workshop require

## To-do

- Add Real variant Fusion archive (after verifying exported content)
- Create dust cover for lever (implement into Top Panel acrylic layer)
- Create support bracket for back wood panel (Real variant)
- Create Simple and Basic variants
- Implement alternative 3D printable lever system
- Remake headphone jack decal in vector/accurate

## Tools / Materials

Will be listed/added at a later date (probably in each variant's subdirectory)

## Known issues

- Card reader carriage incomplete (needs mounting hardware for desired reader hardware variants)
- Bottom panel has no attachment hardware (magnets?) or feet
- Side button hinge should not allow vertical movement (needs removable hinge lock, instead of open slot)
- Lever needs 3D printed paired bushing system to prevent springy travel