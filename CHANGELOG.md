# Changelog

## v0.2.0

- Card: Boost button (top right), with confirmation.
- Card: 24-hour chart of charge, tank sensor and heating periods (needs apexcharts-card).
- Card: animated pipes while heating, showing the water's real direction.
- Card: tank reading shown inside the tank, beside the sensor marker; the sensor's own layer
  is tinted by its reading, and the bottom layer stays the coldest.
- Card: theme font sizes; long lines wrap instead of overflowing; missing values show a dash.
- Package: the daily energy meter's unit is set explicitly (no "unit has changed" repair after
  the first heating run).
- Fixed: top-up energy and cost entity IDs (`sensor.reclaim_tank_top_up_*`).
- Default power entity is now `sensor.reclaim_v2_power`, matching the Reclaim integration.

## v0.1.0

- First release: package, shared settings file and card.
