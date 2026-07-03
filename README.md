# Foculume

Foculume is a local Windows study timer for focused work sessions. Set study and rest durations, run repeating cycles, take optional long breaks, and review your last 7 days of study statistics.

Foculume is local-only. It has no accounts, no telemetry, no external services, and no installer.

## Features

- Custom study, rest, and long-break durations
- Optional long break every N study cycles
- Optional cycle limit, or run until stopped
- Persistent phase-finished popup
- Optional auto-start of the next phase after a 7-second live countdown
- Compact always-on-top timer mode with pause/resume and reset
- Light and dark themes
- Notification area/tray support
- Opening Foculume again brings the existing window forward
- Last 7 days of statistics
- Tracks study time, rest time, paused time, transition time, total time, and completed study cycles
- Settings and statistics saved automatically

## Download

Download `Foculume.exe` from the latest GitHub release and run it.

No installer is required.

## User Data

Foculume stores user data in:

%APPDATA%\Foculume

This includes:

- settings.json
- statistics.json
- foculume.log

Deleting `Foculume.exe` removes the app, but saved settings and statistics remain in `%APPDATA%\Foculume` unless you delete that folder manually.

## Windows Security Notice

Foculume is not code-signed, so Windows SmartScreen may show a warning the first time you run it.

If you trust the download source, choose:

More info -> Run anyway

## Supported Systems

- Windows 10
- Windows 11

## Privacy

Foculume is local-only.

It does not collect data, does not use accounts, and does not connect to external services.
