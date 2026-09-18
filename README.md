# Primuse album-order review images · 2026-09-18

Images supporting the multidisc issue and pull request against chenqi92/primuse. This branch contains review evidence only.

The macOS before/after images compile the real production album view at baseline `fdce61ea2389568b5892fdafe0080e8056fe65b5` and with the multidisc patch. Rendering uses in-memory service substitutes and fixed artwork. They are isolated production-view renders, not installed-app screenshots.

- `review-20260918/before-compact.png` / `after-compact.png`: five discs, the first three tracks from each disc.
- `review-20260918/before-single.png` / `after-single.png`: ordinary single-disc album, 27 tracks; the rendered images are identical.
- `review-20260918/ios-multidisc.png` / `ios-single.png`: native screenshots of the installed review app on iPhone 17 Pro / iOS 27.0 Simulator. The review app combines the independent multidisc and macOS audio patches.

Ancillary text and EXIF metadata were removed from publication copies without changing the PNG pixel data. No music files, library databases, account settings, or raw diagnostic logs are included.
