# Status Reference

This document is modeled after Klipper's
[Status Reference](https://www.klipper3d.org/Status_Reference.html)
document but only contains items pertaining to Trad Rack.

## trad_rack

The following information is available in the `trad_rack` object:
- `curr_lane`: The lane the selector is currently positioned at.
- `active_lane`: The lane currently loaded in the toolhead.
- `retry_lane`: The lane to reload before resuming (if Trad Rack has
  paused the print due to a failed load or unload).
- `next_lane`: The next lane to load in the toolhead if resuming (if
  Trad Rack has paused the print due to a failed load or unload).