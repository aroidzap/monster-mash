# Monster Mash: New Sketch-Based Modeling and Animation Tool

This is the open-source version of Monster Mash.

Monster Mash is a new sketch-based modeling and animation tool that allows you to quickly sketch a character, inflate it into 3D, and promptly animate it. You can perform all interactions in the sketching plane. No 3D manipulation is required.

The source code and web demo (http://MonsterMash.zone) accompanies a paper **Dvorožňák et al.: Monster Mash: A Single-View Approach to Casual 3D Modeling and Animation** published in ACM Transactions on Graphics 39(6):214 and presented at SIGGRAPH Asia 2020 conference.

The source code is licensed under Apache License, Version 2.0. See the LICENSE file for more details.

Monster Mash uses the Triangle library (https://www.cs.cmu.edu/~quake/triangle.html) which is not a part of this repository. Before compiling the project, please download the source code of the library and place it in the third_party/triangle directory. Please check the license of the Triangle library before doing so.

Disclaimer: This is not an officially supported Google product.

# Keymap
F1 - show segmentation
0 - animation mode
1 - draw outline mode
2 - deform mode
3 - animate mode
4 - region swap mode
5 - region move mode
6 - region redraw mode
e - start or stop recording
space - toggle animation
n - new file
s - save to "data/mm_project.zip"
l - load from "data/mm_project.zip"
h - toggle control point visibility
j - toggle template image visibility
t - load template image from "data/template.png"
b - load background image from "data/bg.png"
o - toggle solve for z
p - toggle armpits stitching
w - write obj file to "data/mm_frame.obj"

other keys:
ctrl+c - copy
ctrl+v - paste
ctrl+a - select all
esc - deselect
+ - offset selected control point anim frames by +1
- - offset selected control point anim frames by -1
delete, backspace - remove control point or region