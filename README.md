# east-aurora-trees
An attempt at managing the tree inventory for East Aurora.
An inventory was performed over 15 years ago now, and rarely updated since. This is probably not accurate.

Some issues I'm trying to solve:
- drop owner info on properties. people get rightly nervous.
- track what's been done to properties, and when. Not only tree additions and removals:
  - Owner calls for service (running log would be nice, not just 'last contact').
  - Pruning.
  - Monitoring sickly trees.
  - Helping me track what needs to be done vs. what's been done with the DPW.
- Ease of display. I'm thinking GeoJSON as a format here would be pretty slick. I'm just very worried about that tracking stuff within GeoJSON properties... so I'm thinking a sqlite database could work well in conjunction with the GeoJSON for visualization. But, that might not be real great for using github to track changes. I'd love to be able to come in and say git diff jan-15...jan-16 and have it list it all out for me. So, maybe a single file per address? Directory per street?
