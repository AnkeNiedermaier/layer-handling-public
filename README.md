# PythonPart LayerHandling
The PythonPart enables the creation and editing of the ALLPLAN internal Layerfile **layerdef.dat** directly in Excel and can be used in different ways:
- **Creating** a new layer file from an external template
- **Exporting** and **Editing** an existing layer file
- **(Re)Import** of a layer file modified in Excel

The Excel file used for this has to follow the provided scema to make sure that the PythonPart can use it when executed.

## Installation
The PythonPart **LayerHandling** can be installed directly from the Plugin Manager in ALLPLAN. 

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](https://github.com/AnkeNiedermaier/layer-handling-public/releases). ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Preparation
If the PythonPart should be used to create a new layer file directly from an external template, it is necessary to fill the Excel template in advance with all necessary information. Like it is the case in the ALLPLAN layer file, the template is divided into individual columns:
- Level I (structure)
- Level II (categorie)
- Full name
- short name
- Layer number
- Pen
- Line
- Color
- Line style

Their heading and order is mandatory and should NOT be changed!\
The same applies previously exported data is edited in the Excel template prior to a re-import.
## Syntax of the Excel template
The scema of the Excel file is similar to the structure of the ALLPLAN layer file and contains a separate column for all required information that an individual layer in ALLPLAN could have:
- Structure and Categorie\
corresponding to the Layer Levels I and II inside a layer structure and can have any user-defied name

![layer_level_I](/docs/Layer_levels_excel.png)
- 
