# Cube configurator

FreeCAD model to configure a two-sided rack from 2020 extrusions. Open with FreeCAD 1.0 or later and enter preferences in the spreadsheet.

![Edit preferences](images/prefs.png)

The model will update to reflect the preferences:

| 256mm cube with caps                                                   | Cube with blind brackets                            | Rounded pillars                                          |
| ---------------------------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------------- |
| ![256mm cube with caps](images/valid-cap.png)                          | ![Cube with blind brackets](images/valid-blind.png) | ![Rounded pillars](images/valid-rounded-pillar.png)      |
| XL for MicroATX motherboard                                            | Rounded top frame                                   | 2U motherboard case                                      |
| ![Extra large for a MicroATX motherboard](images/valid-rounded-xl.png) | ![Rounded top frame](images/valid-2rounded-xl.png)  | ![2U motherboard case](images/valid-2u-full-rounded.png) |

Spot invalid combinations like rounded pillars with non-rounded caps:

| Mismatched corner cubes                                          | Rounded corners with square caps                                            |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------- |
| ![Rounded corner cubes](images/invalid-rounded-cubes.png)        | ![Rounded corners with square caps](images/invalid-rounded-caps.png)        |
| Rounded top-frame with caps                                      | Rounded top-frame with blind brackets                                       |
| ![Rounded top-frame with caps](images/invalid-2rounded-caps.png) | ![Rounded top-frame with blind brackets](images/invalid-2rounded-blind.png) |

The BOM generator shows warnings for some invalid combinations:

![Warnings in BOM](images/warnings.png)

And finally, it also has purchase links with estimated costs (with prices as of 2025-10-15):

![BOM generator](images/bom.png)
