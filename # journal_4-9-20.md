# 4-9-20

##Things I Learned Today

### Including and Altering a Walden MS Image

https://cdm16003.contentdm.oclc.org/digital/iiif/p16003coll16/64/full/pct:10/0/default.jpg

*Changing ...full/full/0... in the image url to ...full/pct:10/0... allows the image to be displayed at 10% the original size*

*In that same segment, changing the 0 at the end allows the image to be rotated*

https://cdm16003.contentdm.oclc.org/digital/iiif/p16003coll16/64/full/pct:10/90/default.jpg

*{scheme}://{server}{/prefix}/{identifier}/{region}/{size}/{rotation}/{quality}.{format}*

- {scheme} = https
- {server} = cdm16003.contentdm.oclc.org
- {/prefix} = /digital/iiif
- {region} = full
- {size} = full (first URI) or pct:10 (second URI)
- {rotation} = 0
- {quality} = default
- {format} = jpg