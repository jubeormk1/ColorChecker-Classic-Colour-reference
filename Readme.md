# ColorChecker Classic Mini Colour reference 

This is a reference that I have archive for my own reference. I happen to have one of this [ColorChecker Classic Mini](https://calibrite.com/us/product/colorchecker-classic-mini) around and it is not very useful in machine vision not knowing what are the expected levels. So I did a bit of research and put this notes togeter.

## Reference values

For those only looking at what are the reference leves in the mentioned color check chart the `Colour codes.json` file contain the rgb levels according to the reference image 'CCC-MINI_Main_Lab_codes.jpeg' found in [Securing Color Fidelity in 3D Architectural Heritage Scenarios](https://www.researchgate.net/publication/320602091_Securing_Color_Fidelity_in_3D_Architectural_Heritage_Scenarios). The levels were obtain with an online colour [converter tool](https://www.calculatormix.com/...). **Discretion is needed since I haven't verified the validity of the conversion**.

If you are not familiar with CIE Lab colour space x-rite has a simple [article](https://www.xrite.com/blog/lab-color-space) about it.

## Reference images

The file `CCC-MINI_Main_CIE_Lab_colours_rgb.png`, `CCC-MINI_Main_CIE_Lab_colours_rgb.jpg` and `CCC-MINI_Main_CIE_Lab_colours_rgb.png` are pretty close to the colour codes but there are two discrepancies in the values `CCC-MINI_Main_CIE_Lab_colours_rgb.differences.json` explains the differences.

The original file `CCC-MINI_Main_CIE_Lab_colours_stack.xcf` is the most accurate one but not straight forward to work with (to my knowledge).

