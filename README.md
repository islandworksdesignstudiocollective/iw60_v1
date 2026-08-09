iw60_v1



****************************************************************************************

i was not impressed by the features, availability or price of other gh60 pcbs with o-ring compat so i made this

****************************************************************************************

-gh60 tray mount points

-all the baka nekos o-ring cutouts on edgecuts (afaik)

-alps+mx footprints

-onboad usb c, esd, h60 jst location yada yada

-routed to use no gnd plane cuz why not (a 2-sided fill zone has been drawn with isolation for the usb-c receptabcle already, so you can choose to fill or remove it before making production files)

-duplex matrix cuz why not

-gondo reset circuit cuz why not

-bottom row is tsangan and 87u (so 7u wk/wkl or true hhkb or 87u wk with the 2 1us, as well as split space 3u) 

-does NOT support full right shift or ANSI bottom row 

-has accurately placed usb-c receptacle for gh60 standard. it is not lazily offset like most of the others i have seen, therefore i cannot confirm whether this will be well aligned with whatever pre-existing case that used a different gh60 compat pcb's 3d model to make their usb cutout

****************************************************************************************

as of right now, stm32g0b1cbt6 (and other stm mcus) seem to be in short supply, and other designers have reported issues with this mcu and qmk, so i have shelved this design. for that reason **this design has NOT been prototyped**. i don't have the energy right now to do a bom i will probably regret this in the future

the step file looks good to me. new versions of kicad are annoying to get the right thickness and not export all the holes/components etc so if somethings missing its because i didn't notice :)

if you would like files for the same pcb with a different mcu you can check out iw60_v2 whenever i finish and publish it

****************************************************************************************

this is licensed under the Creative Commons Attribution Share-Alike 4.0 license. For the license's exact terms, see the LICENSE.md file
