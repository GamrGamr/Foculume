# Foculume

Foculume is a simple Windows study timer built for focused work sessions. Set a study time, set a rest time, and let the app guide you through repeating study/rest cycles.

## Features

- Study and rest timer loop
- Optional long break every N cycles
- Cycle limit, or run until stopped
- Persistent popup when each phase ends
- Light mode and dark mode
- Notification area/tray support
- Daily statistics for the last 7 days
- Tracks study time, rest time, paused time, transition time, and completed cycles
- Saves settings automatically
- Uses a single portable `.exe`

## Download

Download `Foculume.exe` from the latest release and run it.

No installer is required.

## User Data

Foculume stores user settings and statistics in:

%APPDATA%\Foculume

This includes:

- settings.json
- statistics.json
- foculume.log

Deleting the `.exe` removes the app, but your saved settings and statistics remain in `%APPDATA%\Foculume` unless you delete that folder manually.

## Windows Security Notice

Foculume is not code-signed, so Windows SmartScreen may show a warning the first time you run it.

To open it, choose:

More info -> Run anyway

## Supported Systems

- Windows 10
- Windows 11

## Privacy

Foculume is local-only.

It does not collect data, does not use accounts, and does not connect to external services.
