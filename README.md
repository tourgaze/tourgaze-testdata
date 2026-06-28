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

## ⚠️ Before you upload — privacy (read this)

Ride files contain **your GPS track** — including, usually, where you started
and finished (often your home). **Anything pushed to this repo is public and
permanent**, and that's true for *every* contributor, not just the maintainers.

**Never push a ride that reveals your home — or anything else sensitive — to
this public repo.** Once it's in the git history it cannot be truly taken back.

If your problem ride starts/ends at home or is otherwise sensitive, **send it
privately instead** — do **not** open a public PR with it:

1. Open an [issue](https://github.com/tourgaze/tourgaze/issues/new) describing the
   bug, and add the note: **"file is sensitive — needs a private channel."**
   Do **not** attach the file.
2. You'll get a private way to send it (e.g. email) so it never becomes public.

Only push a file publicly here if **all** of these hold:

- it **doesn't start or end at home** (a holiday / away ride is ideal — e.g. the
  Mallorca samples below), **or** you've trimmed the sensitive start/end, and
- you're genuinely comfortable with it being public forever.

When in doubt, send it privately.

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
