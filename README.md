# ahn3-downloadlink-page
A very basic page that generates AHN3 download links.

Live deployment can be opened here: https://geppyz.github.io/ahn3-downloadlink-page/

### Info
Uses the AHN3 WFS bladindex endpoint from PDOK to search for active tiles to download. More info about AHN3 dataset (in Dutch) here: [Dataset: Actueel Hoogtebestand Nederland (AHN3)](https://www.pdok.nl/introductie/-/article/actueel-hoogtebestand-nederland-ahn3-).

### AHN3 WFS Capabilities
```url
https://service.pdok.nl/rws/ahn3/wfs/v1_0?service=WFS&request=GetCapabilities&version=2.0.0
```

### AHN3 WFS GetFeature JSON
```url
https://service.pdok.nl/rws/ahn3/wfs/v1_0?service=WFS&request=getFeature&version=2.0.0&typeNames=ahn3_bladindex&outputFormat=application/json
```
