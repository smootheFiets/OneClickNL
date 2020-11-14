# OneClickNL
Quick JOSM presets that work with a single click. Fork of OneClick, adapted to usage in the Netherlands.

This preset is designed to speed up the tagging of "highways" in the Netherlands by providing shortcuts for frequently-used tag combinations, most notably a collection of Dutch traffic signs and combinations of *=use_sidepath to be used next to Dutch cycleways G11, G12a, G13.  Numerous generic tag combinations are included unchanged from the original OneClick (e.g., one-click bridge, one-click tunnel) so OneClickNL can be used as a drop-in replacement of OneClick.

This preset is _not_ designed to handle complex situations: it can't be used to handle, e.g., :forward/backward suffixes, neither does it support tagging more than a single traffic sign (semicolon-separated lists of traffic_signs are not supported).

For the tagging of Dutch cycleways and NL-specific oneway tags, refer to "NL-fiets" (https://forum.openstreetmap.org/viewtopic.php?pid=660657#p660657).

The traffic signs NL:C1-NL:C15 make handy additions to the JOSM toolbar; the corresponding tags follow https://wiki.openstreetmap.org/wiki/NL:The_Netherlands_roads_tagging#Borden:_geslotenverklaringen (with microcar=no added to sign C9).

The use_sidepath options G11, G12a, and G13 add "foot=use_sidepath" because, by Dutch law, pedestrians aren't allowed on the main road if there's a parallel cyclepath (even G13 paths that aren't compulsory for cyclists are still compulsory for pedestrians).  There may be, however, a separate pedestrian sidewalk and it may be mapped as a tag of the main road (e.g., because it's on the other side of the road).  In that case, foot=use_sidepath should be deleted; consider adding a sidewalk tag on the main road.
Furthermore, use_sidepath G11 and G13 delete any existing moped and (in the case of G13) bicycle+mofa tags.  This is desired behaviour when, e.g., a parallel cyclepath has changed from G12a to G11 but will delete useful information in certain cases (e.g., in the presence of a C13 board, or when mofa=moped=permissive).  Please make sure to check, and manually restore any tags that shouldn't have been deleted!

As of Nov 2020, this preset has yet to undergo public testing, although the author has used it heavily since July.  Also, while I've attempted to stick to non-controversial tags, some discussion within the NL OSM community is clearly in order before any further distribution of this file can be contemplated.  Use at your own risk and peril!
 

Link to the forked preset: https://josm.openstreetmap.de/wiki/Presets/OneClick (forked from version 2.29_2020-04-19)


## Version history
* 0.1, July 2020: first test version, not on Github
* 0.2_2020-08-25: upload on Github, add microcar=no to C9
* 0.3_2020-08-25: rewrite README, add preset "footway G7"
* 0.4_2020-08-25: add several traffic_calming shortcuts: table, choker, double-dip, hump, bump
* 0.5_2020-08-27: add one-click cattle-grid and bollard (without attributes)
* 0.6_2020-09-03: adapt side-path G13: delete bicycle tag (was: bicycle=yes), set cycleway=separate
* 0.7_2020-09-11: add one-click traffic_calming=chicane/island
* 0.8_2020-09-27: add "Water tap"
* 0.9_2020-11-14: add "OV fiets self-service"
