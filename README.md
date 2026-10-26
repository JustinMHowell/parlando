# Parlando

A synthesizer by Justin Howell. Something strikes, plucks or breathes into a body made of wood, string, metal or skin, and the sound comes out through a vocal tract that shapes it into vowels. There's a parameter sequencer for movement. It's a plugin (CLAP, VST3, AU) and a standalone app, for macOS and Windows.

This is a test version. Thanks for playing it.

Test versions (before 1.0) stop making sound 60 days after their release, so everyone plays the newest. The header shows how many days are left in the last two weeks. It never stops in the middle of a song, and your sound and patches are kept. A new version starts a fresh 60 days.

## Download

**[The latest version](https://github.com/JustinMHowell/parlando/releases/latest)**: under *Assets*, pick your system and format.

To hear about new versions, click **Watch** at the top of this page, then **Custom**, then tick **Releases**. GitHub will email you whenever there's a new one.

## Install

**macOS** (Apple Silicon and Intel). Unzip each download and move it into place:

| File | Goes in |
|---|---|
| `Parlando.clap` | `~/Library/Audio/Plug-Ins/CLAP` |
| `Parlando.vst3` | `~/Library/Audio/Plug-Ins/VST3` |
| `Parlando.component` (AU) | `~/Library/Audio/Plug-Ins/Components` |
| `Parlando.app` | `/Applications` |

The test versions aren't signed by Apple yet, so macOS blocks them at first. To let them run, open Terminal and paste this in:

```sh
xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/CLAP/Parlando.clap ~/Library/Audio/Plug-Ins/VST3/Parlando.vst3 ~/Library/Audio/Plug-Ins/Components/Parlando.component /Applications/Parlando.app
```

**Windows** (64-bit). Unzip, then move:

| File | Goes in |
|---|---|
| `CLAP\Parlando.clap` | `C:\Program Files\Common Files\CLAP` |
| `VST3\Parlando.vst3` | `C:\Program Files\Common Files\VST3` |
| `Standalone\Parlando.exe` | anywhere you like |

Then rescan plugins in your DAW. To update, download the new version and replace the old files. Your patches and projects carry over.

Parlando contains open-source software. Its licences are in `THIRD_PARTY_NOTICES.txt`, which comes with each download and sits inside each plugin.

## Which version am I on?

The number next to the *parlando* name in the plugin's header, for example `0.9.10 · build 57`.

## Found a problem?

[Open an issue](https://github.com/JustinMHowell/parlando/issues) and include the version from the header, your DAW and your system. If you can, say what you played and what you expected to hear.
