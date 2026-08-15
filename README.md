# GeoGIF

Static client-side photo-to-GIF site.

- Mobile/tablet browser gate
- Requires GPS latitude/longitude in EXIF
- Rejects photos without GPS EXIF
- GIF processing happens in the browser
- No photo upload backend

A website cannot guarantee that a file physically originated from a phone. The mobile gate is based on browser/device signals, while the GPS requirement is checked from the actual image metadata.
