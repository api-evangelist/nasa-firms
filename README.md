# NASA FIRMS

NASA Fire Information for Resource Management System (FIRMS) REST API providing
near-real-time satellite fire detections globally from MODIS (Terra/Aqua),
VIIRS (S-NPP, NOAA-20, NOAA-21), and LANDSAT instruments. Data is available
within 3 hours of satellite observation worldwide, with Ultra Real-Time
detections available within 60 seconds for the US and Canada.

**Human URL:** https://firms.modaps.eosdis.nasa.gov/api/

## APIs

- **Area Fire Detections** — active fire hotspots by bounding box, sensor, and day range (CSV)
- **KML Fire Footprints** — regional fire footprint polygons by time span and sensor (KMZ)
- **Data Availability** — check which dates have SP and NRT data per sensor
- **Missing Data** — identify dates lacking satellite coverage per sensor

## Authentication

Free MAP_KEY registration required for area, data availability, and missing data
endpoints. KML fire footprints are publicly accessible without a key.

Rate limit: **5,000 transactions per 10-minute interval** per MAP_KEY.

## Links

- [API Documentation](https://firms.modaps.eosdis.nasa.gov/api/)
- [Register for MAP_KEY](https://firms.modaps.eosdis.nasa.gov/api/)
- [Fire Data Academy](https://firms.modaps.eosdis.nasa.gov/academy/)
- [Contact](https://firms.modaps.eosdis.nasa.gov/contact/)
