# 🐐 TourGaze — test data

Sample and problem ride files for **[TourGaze](https://github.com/tourgaze/tourgaze)**.

This repo exists for one thing: **if a ride won't import, imports wrong, or looks
broken in TourGaze, drop a copy of the file here** so the bug can be reproduced
and fixed. A real file that triggers the problem is worth far more than a bug
report describing it.

## A file won't import or looks wrong?

1. **Open an [issue on the main repo](https://github.com/tourgaze/tourgaze/issues/new)**
   describing what you saw (what you expected vs. what happened, which view).
2. **Add the file** — either attach it to the issue, or open a pull request here
   adding it under [`samples/`](samples/). Name it so it's clear what's special,
   e.g. `garmin-530-missing-power.fit` or `strava-export-bad-timestamps.gpx`.

Supported formats: **FIT, GPX, TCX, KMZ/KML**.

## ⚠️ Before you upload — privacy

Ride files contain **your GPS track** — including, usually, where you started
(often your home). Anything pushed here is **public and permanent**.

- Prefer a ride that **doesn't start or end at home** (a holiday or away ride).
- Or trim the start/end of the track before uploading.
- Only upload files you're comfortable sharing publicly.

If a file is sensitive but needed to reproduce a bug, say so in the issue and it
can be shared privately instead.

## Reference samples

[`samples/`](samples/) contains a couple of known-good real rides (from Mallorca,
away from anyone's home) you can use to try TourGaze or compare against:

| File | Format | Notes |
|------|--------|-------|
| [`mallorca-2025-cycling.fit`](samples/mallorca-2025-cycling.fit) | FIT  | ~53 km road ride, modern device |
| [`mallorca-2011-cycling.gpx`](samples/mallorca-2011-cycling.gpx) | GPX  | Long ride from Alcúdia, older recorder |

## License

The sample files are shared by their owners for testing TourGaze. Contributed
files are assumed to be shared under the same spirit — upload only what you have
the right to share.
