# XRadio Leo

XRadio Leo is a radio-automation application based on the Radit free-software codebase. This repository is a development fork; it is not yet a packaged or verified release.

## Features inherited from the base project

- Crossfade between audio tracks
- MP2, MP3, WAV, WMA, OGG and FLAC support (depending on the available audio libraries)
- Random folder playback
- Automated events and broadcast log
- One main player and two auxiliary players
- Time, temperature and humidity announcements
- Entry/exit jingles and advertising or music blocks
- Internet radio connections

## Current XRadio Leo work

- Rebranded main-window title, application icon and toolbar logo
- Rebranded About dialog and launcher metadata
- Initial light/dark theme toggle work in progress

**Status:** A successful build and playback test have not yet been verified. Do not treat this branch as a finished installer.

## Build notes

The original project used Qt and external audio/tagging libraries. The exact build steps depend on the Qt version and dependencies installed on the target system. The original upstream project is available at [jfperini/radit](https://github.com/jfperini/radit).

## License

This fork is based on the upstream Radit project. Retain the applicable open-source license and copyright notices when redistributing the code.
