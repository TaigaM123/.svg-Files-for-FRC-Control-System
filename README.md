# .svg-Files-for-FRC-Control-System
Components for the FIRST Robotics Competition, in .svg format. Use these to make wiring diagrams. 

## How to convert .step files to .svg files
I'm sure there's a *much* simple and easier way to do this, but here's how I did it. (Kubuntu 22.04, FreeCAD 0.20.0, Inkscape 1.1.2)

Required apps:
* An Onshape account - Semi-optional, although it does make life easier
* [FreeCAD](https://freecadweb.org) - Fusion (and most other CAD software) should work, but I have yet to test it.
* [Inkscape](https://inkscape.org)
* A blank .svg file (included in this GitHub repository)

1. Download the STEP files for components. I used [MKCad](https://onshape4frc.com/cad-library) for this, but downloading from [CTRE](https://github.com/CrossTheRoadElec/Device-CADs)'s, [REV](https://docs.revrobotics.com/docs/rev-ion)'s, and [VEX](https://www.vexrobotics.com/pro)'s websites also works. 
    1. Make or download the blank .svg file
2. Open FreeCAD, select "Create new...", then select File > Import and the STEP File
    2. Wait for the file to be imported
3. Use the cube in the top left to spin the part into the orientation you want. 
4. In the dropdown on the top center, select "TechDraw". 
5. Go to Edit > Preferences > TechDraw, and set "Default Template" to the blank .svg file
6. Apply settings, and "Insert Default Page" (![Insert Default Page](https://wiki.freecadweb.org/images/9/9a/TechDraw_PageDefault.svg)). 
7. On the left-hand sidebar, select the Part you imported (it should highlight blue), and then hit "Insert View" (![Insert View](https://wiki.freecadweb.org/File:TechDraw_View.svg)). 
    1. And wait some more...
9. Head back to the TechDraw, and right-click on the work area (yes, it might be blank), and select "Export as SVG". 
10. Name your SVG and hit "Export"
    1. Depending on your OS, you might need to manually append ".svg" to the file name. 
11. Open the file in Inkscape and shrink it down so it fits into the rectangle between (0,0) and (300,150). (Drag a corner while hitting Ctrl). 
