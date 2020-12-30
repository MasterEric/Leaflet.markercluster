Leaflet.markercluster
=====================

# This is a fork.

Changes adapted for general use from the fork used for https://yuanshen.site

[Click here for the main project](https://github.com/Leaflet/Leaflet.markercluster).

## Improvements made (separated into branches for easy PRs):

- `fast-forward-leaflet`: Update Leaflet peer dependency to the latest version (1.7.1).
- `spiderfy-on-every-zoom`: New parameter: Spiderfy on every zoom.
- `refresh-on-unspiderfy`: Refresh clusters when unspiderfying. Think this fixes a bug.
- `pass-markers-to-spiderfy`: The spiderfyShapePositions function now receives `childMarkers` as a third argument, allowing full customization of spiderfy positions.