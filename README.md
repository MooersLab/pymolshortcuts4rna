![Version](https://img.shields.io/static/v1?label=pymolshortcuts4rna&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# pymolshortcuts4rna

This is the repository for ***pymolschortucts4rna.py***.
The shortcuts are several letters mapped to a Python function that executes one to many lines of code.
They function like bash aliases or the 

Above is the PDF of the slides from my presentation at the [**2019 CornBelt Regional RNA Symposium**](https://rna-cornbelt-regional-meeting.webnode.com) at the University of Missouri, Columbia, MO. 
Many thanks go to Professors Brenda Peculis and Frank Schmidt for organizing and hosting this fantastic meeting. 
The poster session was one of the most enjoyable that I have ever experienced.
A paper about this project is in the works.

## Examples

The shortcut is listed on the top.
Two shortcuts are combined by using a semicolon.
The U8 shortcut retrieves and orients the biological unit of PDB entry 3nd3.


### U8;CR: filled rings colored by sequence. 

The internal GUI to the right does not have presets for nucleic acids under the **A** pulldown.
The CR shortcut provides a ribbon cartoon with filled rings. 
The nucleotides are colored by base sequence.

![U8CR](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/guiU8CR.png?raw=true "CR")


### FR: filled rings colored by element and BW: black and white cartoon for grayscale figures

The FR shortcut generates filled rings colored by atomic elements.
The BW shortcut renders a black-and-white cartoon, which is useful when using color would be expensive or when used with a colored ligand to emphasize the ligand.

![U8FRBW](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/U8FRBW.png?raw=true "FR BW")


### Ambient occlusion variants. 

![AOAOBWAOD](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/AOAOBWAOD.png?raw=true "AO BW AOD")


### Shortcuts for generating arrays of unit cells filled with symmetry mates.

Crystal packing diagrams are particularly relevant to the stacking of double helices, which can stack end-on-end.

![xtalPacking](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/xtalPacking.png?raw=true "xtalPacking")


#### Example of a stacking figure. Use the code revealed with *help BST* as a template.

![BST](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/BSTcrop.png?raw=true "BST")


#### Example of a coordinated metal. Use the pearl effect with the radius of the opaque sphere set to 0.25. Use the code revealed with *help NAL* as a template.

![NaNape25](https://github.com/MooersLab/pymolshortcuts4RNA/blob/master/images/NaNape25.png?raw=true "naNape25")


## Related repositories

- [easypymol](https://github.com/MooersLab/EasyPyMOL/edit/master/README.md)
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts)
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips)
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips)
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips)
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips)
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips)
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips)
- [PyMOLwallhangings](https://github.com/MooersLab/PyMOLwallhangings)

## Update history

|Version      | Changes                                                                                                                                                                         | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |   Added badges, funding, and update table.                                                                                                                  | 2024 May 25        |

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)

