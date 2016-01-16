# Blender Guide for Beginners

I don't use blender every day, so every time I come back I've forgotten some of the most basic commands and need to google them again and watch some lengthy videos to find out simple answers.

To save time in the future I'll collect those answers here, in a very condensed format, accompanied by screenshots when needed.


# Table of contents
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Blender Guide for Beginners](#blender-guide-for-beginners)
- [Table of contents](#table-of-contents)
	- [Interface](#interface)
		- [Change to metric units](#change-to-metric-units)
	- [View](#view)
		- [Wireframe mode](#wireframe-mode)
		- [Reset 3D cursor position](#reset-3d-cursor-position)
	- [Objects](#objects)
		- [Measure 3D object size](#measure-3d-object-size)
		- [Toggle between Edit and Object mode](#toggle-between-edit-and-object-mode)
		- [Select all and deselect all](#select-all-and-deselect-all)
		- [Select faces around](#select-faces-around)
		- [Bridge faces together](#bridge-faces-together)

<!-- /TOC -->

## Interface

### Change to metric units
In the right hand panel, under the scene tab.

<img src="images/units.png" width="300">

## View

### Wireframe mode
`Z`

### Reset 3D cursor position
`Shift-C`

## Objects
### Measure 3D object size
`N` while in object mode, you will see dimensions in the transform panel.

### Toggle between Edit and Object mode
`Tab`

### Select all and deselect all
`A`

### Select faces around
`Ctrl+Shift+Alt+F` and then adjust the "sharpness" angle.

![Select faces around "Ctrl+Shift+Alt+F"](images/select_faces_around.png)

### Bridge faces together
Select faces to bridge + `W` + "Bridge edge loops".

In the screenshot below the object was broken (there were double vertices hiding inside the shape and they were not connected, resulting in a ugly render). I selected four of those 8 vertices, pulled them away from the other 4, then selected the opposing faces, and bridged them together.

![Select faces to bridge + `W` + "Bridge edge loops"](images/bridge_edge_loops.png)
