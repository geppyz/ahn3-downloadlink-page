# ahn3-downloadlink-page
A very basic page that generates AHN3 download links

### Info
Uses the AHN3 WFS bladindex endpoint from PDOK to search for active tiles to download.

### AHN3 WFS Capabilities
```url
https://geodata.nationaalgeoregister.nl/ahn3/wfs?service=WFS&request=GetCapabilities
```

### AHN3 WFS GetFeature JSON
```url
https://geodata.nationaalgeoregister.nl/ahn3/wfs?request=getFeature&service=WFS&typeNames=ahn3_bladindex&version=2.0.0&outputFormat=application/json
```
