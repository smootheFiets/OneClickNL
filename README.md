# OneClickNL
JOSM presets. Fork of OneClick, adapted to usage in the Netherlands.

This is my first attempt at scripting JOSM presets and has yet to be tested (as of July 2020).  Use at your own risk!

The presets corresponding to boards C1-C15 make handy additions to the JOSM toolbar; the corresponding tags follow https://wiki.openstreetmap.org/wiki/NL:The_Netherlands_roads_tagging#Borden:_geslotenverklaringen (with microcar=no added to C9).

The use_sidepath options G11 and G13 are potentially dangerous in that they delete any existing moped and (in the case of G13) mofa tags.  This is useful when, e.g., a parallel cyclepath has changed from G12a to G11 but may delete useful information in certain cases (e.g., in the presence of a C13 board, or when mofa=moped=permissive).

I plan to upload this preset file on the JOSM webpage once I've tested it.

Link to the forked preset: https://josm.openstreetmap.de/wiki/Presets/OneClick
(forked from version 2.29_2020-04-19)
