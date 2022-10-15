Program uses Exaprom PDF 2.0 library fo generating PDF reports. This is not native LabVIEW library and it must be added manually to LabVIEW.
To add this library to LabVIEW, unpack file Exaprom PDF2.0 (LV2013).zip and move contents:

"Exaprom PDF" folder to "C:\Program Files\National Instruments\<LabVIEW Version>\vi.lib\
"exaprompdf.mnu" file to "C:\Program Files\National Instruments\<LabVIEW Version>\menus\Categories\Programming\

After this, Exaprom PDF library should appear in the Programming palette, and LabVIEW should find needed functions and be able to compile.

Note 1: <LabVIEW Version> is your LabVIEW version name (for example "LabVIEW 2014"), not literal folder name
Note 2: On polish operating system you may have to look not in "Program Files" folder, but in "Pliki programow (x86)" folder, or similar.