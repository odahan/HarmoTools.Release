# HarmoTools

**Practical Harmony for Musicians** — a desktop workspace for scales, chords, tonal relationships, and MIDI-assisted exploration.

> 🇫🇷 Vous parlez français ? Lisez la [version française](README.FR.MD).

> Read the license before downloading! [license](LICENSE.MD)

HarmoTools is a desktop application for musicians, composers, arrangers, and teachers who need practical tools for working with musical harmony.

The goal of the project is to provide a clear interface for exploring, understanding, and working with common music theory concepts:

- chords and extensions;
- scales and modes;
- relationships between notes, degrees, and keys;
- the circle of fifths;
- keyboard visualization;
- MIDI-assisted exploration;
- tools to support harmonic analysis and composition.

## Features

- **Home** — favorite scales, chord memories, and a simple chord-sequence player.
- **Scales & Chords** — build a scale from a root and a definition; inspect its notes and chord material (triads or seventh chords).
- **Scale Finder** — identify scale candidates from a set of notes, with a recognition catalog of 48 scale definitions.
- **Scale catalog** — 52 distinct scale definitions: major modes, harmonic and melodic minor modes, pentatonic scales, and exotic collections (whole-tone, octatonic, blues, bebop, Neapolitan, Japanese…).
- **Random Sequencer** — generate, edit, play, store, and export monophonic melodies as MIDI.
- **Chords** — recognize chord candidates from keyboard or MIDI notes; **Chord Name** parses chord symbols in the other direction.
- **Circle of Fifths** — key signatures, relative keys, a movable degree window, and per-key chord memories.
- **Frequencies** — exact pitch frequencies and instrument-range comparisons.
- **Audio preview** — internal note and chord playback through bundled SoundFonts, or your own `.sf2` file.
- **MIDI input** — play chords live from a MIDI controller.
- **MIDI export** — progressions and sequences as Standard MIDI Files (type 0) you can drop straight into your DAW.

## Site

Le site HarmoTools vous montrera de nombreuses captures d'écran avec des explications, visitez-le !
Le [site HarmoTools](https://www.e-naxos.com/harmotools/)

## Downloads

Grab the latest binary from the **[Releases](https://github.com/odahan/HarmoTools.Release/releases)** page.

- Download `HarmoTools-<version>-win-x64.zip`
- Extract the archive anywhere
- Run `HarmoTools.exe`

No installation required — the application is portable.

## Requirements

- Windows 10 version 2004 (build 19041) or later, 64-bit
- No administrator rights required

## Getting started

- **Audio preview**: HarmoTools plays internal previews through a SoundFont (`.sf2`). Open `Settings`, pick a bundled preset (e.g. *Preview Piano*, or the full *GeneralUser GS* instrument set) or browse to your own SoundFont, select an output device, and test.
- **MIDI input**: in `Settings`, select your MIDI input device and listening channel. If your DAW uses the same keyboard, leave it unselected in HarmoTools so both applications can run together.
- **Startup shortcuts**:
  - Hold `Shift` while launching to center the main window on screen.
  - Hold `Alt+Shift` to reset all settings after confirmation, including the saved window position.

The full user manual is embedded in the application (`Help > User manual`, available in English and French).

## License

HarmoTools is proprietary **Donationware**. It is distributed free of charge for personal, non-commercial use; redistribution and commercial use require Olivier Dahan's prior express written permission. The full licenses are available in English and French inside the application.

Donations of any amount are optional and can be made at [buymeacoffee.com/knhsynths](https://buymeacoffee.com/knhsynths). No account or email address is required. Donors alone are eligible for support and update notifications.

The underlying [Enaxos.MusicHarmony](https://github.com/odahan/MusicHarmony) library is open source under its own license. HarmoTools itself is not open source.
