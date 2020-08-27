# OneClickNL
Quick JOSM presets designed to work with a single click. Fork of OneClick, adapted to usage in the Netherlands.

This preset is designed to speed up the tagging of "highways" in the Netherlands by providing shortcuts for frequently-used tag combinations, most notably a collection of Dutch traffic signs and combinations of *=use_sidepath to be used next to Dutch cycleways.  This preset is _not_ designed to handle complex situations: it can't be used to handle, e.g., :forward/backward suffixes nor a list of explicitly tagged traffic signs.

For the tagging of Dutch cycleways and NL-specific oneway tags, refer to "NL-fiets" (https://forum.openstreetmap.org/viewtopic.php?pid=660657#p660657).

The traffic signs NL:C1-NL:C15 make handy additions to the JOSM toolbar; the corresponding tags follow https://wiki.openstreetmap.org/wiki/NL:The_Netherlands_roads_tagging#Borden:_geslotenverklaringen (with microcar=no added to sign C9).

The use_sidepath options G11 and G13 are potentially dangerous in that they delete any existing moped and (in the case of G13) mofa tags.  This is desired behaviour when, e.g., a parallel cyclepath has changed from G12a to G11 but may delete useful information in certain cases (e.g., in the presence of a C13 board, or when mofa=moped=permissive).

As of Aug 2020, this preset has yet to undergo serious testing (although it's been working for me since July).  Also, while I've attempted to stick to non-controversial tags, some discussion within the NL OSM community is clearly in order before any further distribution of this file can be contemplated.  Use at your own risk and peril!
 

Link to the forked preset: https://josm.openstreetmap.de/wiki/Presets/OneClick (forked from version 2.29_2020-04-19)


## Version history
* 0.1, July 2020: first test version, not on Github
* 0.2_2020-08-25: upload on Github, add microcar=no to C9
* 0.3_2020-08-25: rewrote README, added preset "footway G7"
* 0.4_2020-08-25: added several traffic_calming shortcuts: table, choker, double-dip, hump, bump
* 0.5_2020-08-27: added one-click cattle-grid and bollard (without attributes)

