# xkb-symbols

## What is this?
These are templates for XKB, to add Alt-Gr Umlaute to keys of US keyboards, where they would be located on DE keyboards:
* Alt-Gr + ; = ö
* Alt-Gr + : = Ö
* Alt-Gr + ' = ä
* Alt-Gr + " = Ä
* Alt-Gr + [ = ü
* Alt-Gr + ; = Ü
* Alt-Gr + - = ß
* Alt-Gr + _ = ß
* Alt-Gr + e = €
* Alt-Gr + E = €

## Instructions:
* Append content of symbols file to /usr/share/X11/xkb/symbols/us.
* Insert content of rules file into the variantList of "us" in /usr/share/X11/xkb/rules/evdev.xml.
