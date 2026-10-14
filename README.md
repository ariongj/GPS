# Lodestar GPS

Demo website for a fictional fleet-telematics company. It's a single self-contained `index.html` with no build step: open it in a browser.

## Sections

- **Operations console:** a live, simulated map of six vehicles around Prishtina.
  - Zoom, pan, layer toggles and vehicle search.
  - KPI strip, per-vehicle telemetry (GNSS, fuel, odometer, driving hours) and a fleet list.
  - An event log for geofence, speeding and harsh-braking events.
- **Industries and platform modules:** logistics, construction, cold chain, public transport, utilities and waste.
- **Route replay:** plays back a recorded delivery run, with a speed chart, numbered stops, driving flags and a trip score.
- **Hardware:** a dimension drawing and full spec sheet for the T4 tracker.
- **GNSS performance:** a live satellite sky plot and signal-strength chart.
- **Developers:** valid `$GNGGA` / `$GNRMC` NMEA 0183 sentences (with checksums) for the selected vehicle, or the same fix as REST JSON.
- **Rest of the site:** security and privacy, an interactive savings estimate, pricing, and a demo request form (it sends nothing).

Light and dark themes follow the system setting, and the nav has a switch to override it. All data is simulated.
