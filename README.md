# iconmaker

A little utility to create GNU/Linux icons from an svg file and distribute them into /usr/share/icons/hicolor/

Works with zsh (change the first line for other shells). Tested on Arch GNU/Linux

Usage:

1) create an svg in a program like Inkscape or get it from somwhere

2) cd into the directory that has your svg

3) do 'iconmaker <filename>' where <filename> is the svg filename without the '.svg'. 

You will be prompted for sudo password and there are likely to be errors and warning as not all icon sizes this script creates have the appropriate folders in the hicolor directory.


