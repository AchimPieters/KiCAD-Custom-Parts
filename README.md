# KiCAD-Custom-Parts
KiCAD Custom Parts

![Image of Symbol](https://raw.githubusercontent.com/AchimPieters/KiCAD-Custom-Parts/main/icns/3D.png)
![Image of Symbol](https://raw.githubusercontent.com/AchimPieters/KiCAD-Custom-Parts/main/icns/Footprint.png)
![Image of Symbol](https://raw.githubusercontent.com/AchimPieters/KiCAD-Custom-Parts/main/icns/3D.png)

### KiCad (V4 and later)
#### Import Steps for Kicad 5.1

1. In KiCad, go to <b>Tools > Edit Schematic Symbols</b>.
2. Click on <b>Preferences > Manage Symbol Libraries</b>.
3. In the Global Libraries tab, click on <b>Add existing library to table</b>, the <b>small folder icon</b> and navigate to the downloaded .lib file. Then click <b>Open</b>.
4. Use the search bar on the left pane of the window to search for the imported symbol and double-click it to open.

#### Import Footprints

1. In KiCad, go to <b>Tools > Edit PCB Footprints</b>.
2. Click on <b>Preferences > Manage Footprint Libraries</b>.
3. In the Global Libraries tab, click on <b>Add existing library to table</b>, the <b>small folder icon</b> and navigate to the downloaded folder where your <b>.kicad_mod</b> file is located. Then click <b>OK</b>.
4. Use the search bar on the left pane of the window to search for the imported footprint and double-click it to open.

### Import Steps For KiCad 5.0
#### Import Symbols

1. In KiCad, go to <b>Tools > Edit Schematic Symbols</b>.
2. Click on <b>Preferences > Manage Symbol Libraries</b>.
3. In the Global Libraries tab, click on <b>Browse Libraries</b> and navigate to the downloaded .lib file. Then <b>click Open</b>.
4. In the table, make sure that the Plugin Type is set to Legacy. Then click <b>OK</b>.
5. Use the search bar on the left pane of the window to search for the imported symbol and double-click it to open.

#### Import Footprints

1. In KiCad, go to <b>Tools > Edit PCB Footprints</b>.
2. Click on <b>Preferences > Manage Footprint Libraries</b>.
3. In the Global Libraries tab, click on <b>Browse Librarie</b>s, the small folder icon and navigate to the downloaded .mod file. Then click <b>OK</b>.
4. In the table, make sure that the Plugin Type is set to Legacy. Then click <b>OK</b>.
5. Click<b> Load footprint from library > Select by Browser</b> and navigate the footprint you imported and double-click it to open.

### KiCad (pre V4)
#### Import Steps For KiCad 4

1. Extract the content of the downloaded <b>.zip</b> file
2. In KiCad, go to <b>Tools > Open Eeschema</b>
3. Select <b>Preferences > Component Libraries</b>
4. In the <b>Component library files</b> section, click <b>Add</b>
5. Select the <b>.lib</b> library file
6. Go to <b>Tools > Open PcbNew</b>
7. Click <b>Preferences > Footprint Libraries Wizard</b>
8. Follow the steps in the wizard to select and import the footprint library (<b>.mod</b> file)

### Import Steps For Older Versions of KiCad
#### Import Symbols

1. Launch <b>Eeschema</b>.
2. Select <b>Preferences > Library</b>.
3. In the <b>from...</b> window, in the User Defined Search Path area, click <b>Add</b>.
4. In the Default Path for Libraries windows, navigate to the location where your previously extracted the ZIP contents, then click <b>Select Folder</b>.
5. In the Path type window, click <b>No</b> (unless you use project-specific libraries).
6. In the <b>from...</b> window, in the Component Library Files area, click Add.
7. In the Library files: window, select the <b>LIB</b> file, then click <b>Open</b>. The symbol now shows in the Component Library Files list.
8. In the <b>from...</b> window, click <b>OK</b>.

#### Import Footprints

1. Launch <b>Pcbnew</b>.
2. Select <b>Preferences > Library</b>.
3. In the <b>from...</b> window, in the User defined search paths area, click <b>Add</b>.
4. In the Default Path for Libraries windows, navigate to the location where your previously extracted the ZIP contents, then click <b>Select Folder</b>.
5. In the Path type window, click <b>No</b> (unless you use project-specific libraries).
6. In the <b>from...</b> window, in the Component Library Files area, click Add.
7. In the Footprint library files window, select the <b>MOD</b> file, then click <b>Open</b>. The footprint now shows in the Footprint library files list.
8. In the <b>from...</b> window, click <b>OK</b>.
