# Blender Guide for Beginners

I don't use blender every day, so every time I come back I've forgotten some of the most basic commands and need to google them again and watch some lengthy videos to find out simple answers.

To save time in the future I'll collect those answers here, in a very condensed format, accompanied by screenshots when needed.

## Interface

### Change to metric units
In the right hand panel, under the scene tab.

<img src="https://raw.githubusercontent.com/ssamuli/BlenderGuide/master/images/units.png" width="300">

## View

### Wireframe mode
`Z`

### Reset 3D cursor position
`Shift-C`

## Objects
### Measure 3D object size
`N` while in object mode, you will see dimensions in the transform panel.

### Toggle Edit / Object mode
`Tab`

### Select all / deselect all
`A`

### Select faces around
`Ctrl+Shift+Alt+F` and then adjust the "sharpness" angle.

![Select faces around "Ctrl+Shift+Alt+F"](https://raw.githubusercontent.com/ssamuli/BlenderGuide/master/images/select_faces_around.png)

### Bridge faces together
Select faces to bridge + `W` + "Bridge edge loops".

In the screenshot below the object was broken (there were double vertices hiding inside the shape and they were not connected, resulting in a ugly render). I selected four of those 8 vertices, pulled them away from the other 4, then selected the opposing faces, and bridged them together.

![Select faces to bridge + `W` + "Bridge edge loops"](https://raw.githubusercontent.com/ssamuli/BlenderGuide/master/images/bridge_edge_loops.png)
