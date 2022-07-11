# .svg-Files-for-FRC-Control-System
Components for the FIRST Robotics Competition, in .svg format. Use these to make wiring diagrams. 

## Making New .svg Files
I'm sure there's a *much* simple and easier way to do this, but here's how I did it. (Kubuntu 22.04)

Required apps:
* An Onshape account - Semi-optional, although it does make life easier
* [FreeCAD](https://freecadweb.org) - Fusion (and most other CAD software) should work, but I have yet to test it.
* [Inkscape](https://inkscape.org)
* A blank .svg file (included in this GitHub repository)

1. Download the STEP files for components. I used [MKCad](https://onshape4frc.com/cad-library) for this, but downloading from [CTRE](https://github.com/CrossTheRoadElec/Device-CADs)'s, [REV](https://docs.revrobotics.com/docs/rev-ion)'s, and [VEX](https://www.vexrobotics.com/pro)'s websites also works. 
    1a. Make or download the blank .svg file
2. Open FreeCAD, select "Create new...", then select File > Import and the STEP File
    2a. Wait for the file to be imported
3. Use the cube in the top left to spin the part into the orientation you want. 
4. In the dropdown on the top center, select "TechDraw". 
5. Go to Edit > Preferences > TechDraw, and set "Default Template" to the blank .svg file
6. Apply settings, and "Insert Default Page" (![Insert Default Page](https://wiki.freecadweb.org/images/9/9a/TechDraw_PageDefault.svg))
