# Lodestar GPS

A demo marketing site for a GNSS fleet-tracking product. One self-contained `index.html`, no build step.

Open `index.html` in a browser to run it.

## What's on the page

- **Live map**: six simulated vehicles drive around a contour map of Prishtina. Click a vehicle (or a row in the fleet list) to follow it. Geofences log enter/leave events and flag speeding in the 30 km/h school zone.
- **Sky plot and signal chart**: satellites from GPS, Galileo, GLONASS and BeiDou drift across the sky, with C/N₀ bars and live HDOP/PDOP.
- **Developer feed**: valid `$GNGGA` / `$GNRMC` NMEA 0183 sentences (with checksums) for the selected vehicle, or the same fix as REST JSON.
- **Route replay**: play back a recorded delivery run with a speed chart, numbered stops, harsh-braking and speeding flags, and a driver score.
- Platform features, pricing and a demo request form (the form doesn't send anything).

Light and dark themes follow the system setting, with a switch in the nav. All data is simulated.
