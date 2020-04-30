# ahn3-downloadlink-page
A very basic page that generates AHN3 download links.
Live deployment can be opened here: https://geppyz.github.io/ahn3-downloadlink-page/

### Info
Uses the AHN3 WFS bladindex endpoint from PDOK to search for active tiles to download.

### AHN3 WFS Capabilities
```url
https://geodata.nationaalgeoregister.nl/ahn3/wfs?service=WFS&request=GetCapabilities&version=2.0.0
```

### AHN3 WFS GetFeature JSON
```url
https://geodata.nationaalgeoregister.nl/ahn3/wfs?service=WFS&request=getFeature&version=2.0.0&typeNames=ahn3_bladindex&outputFormat=application/json
```
