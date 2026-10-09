# STR-500 enclosure design 

This folder has the files I use for drilling and etching the enclosure for the STR-500. 

The enclosure I use is a Hammond 1590V. 

The Gametrak string mechanism I'm using is a particular size and shape, which means the enclosure needs to be a certain height and width. I wanted something that I could buy off the shelf (rather than 3D print or build from scratch), and I really like metal enclosures. The Hammond 1590V fulfills all of these requirements - just! It's a very tight fit in there and the holes need to be drilled just right. The only issue is that it's a relatively unusual model, so I can't use the standard drill/paint services that most effects and instrument companies use. 

Instead, the process is: 
• buy the bare metal enclosures
• use a little jig I laser cut to drill all the holes in the enclosure - these have to be pretty accurate because the PCB needs to mount underneath the lid
• get them powder coated blue at an industrial painting place
• put the lids into a laser cutter and etch the powder coating away in the design I want
• fill the etching with a wax crayon, wipe the excess with rubbing alcohol
• light spraypaint for texture

The painting and etching is, of course, totally optional. You can definitely make your own design or just leave it bare metal and unlabeled. 

If you want to follow my own process, the files are all here for you to laser cut your own drill guide. You may find some other useful method for drilling the holes. 

Drilling the holes accurately is challenging! I would recommend first drilling small holes (2-3mm) and then using a stepped bit to get them up to size. The large hole for the Gametrak string is particularly hard to get just right. I usually end up needing to adjust the exact horizontal placement of the Gametrak string using washers on the M5 bolts holding it in place.

Software-wise, the vectors files for the hole locations are made in Affinity, and the laser cutting files are for Lightburn. 