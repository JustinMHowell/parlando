# Parlando

A unique synthesizer by Justin Howell.

It's like a weird physical modeling synth paired with a throat simulation. It sounds like bells from another planet, talking guitars, or metallic percussion that sings to you. I've never seen a modal synth paired with a formant filter and I thought I'd go down the rabbit hole. Really, this synth is for anyone who's tired of the same subtractive synthesis we see everywhere. For someone who wants something unique and weird but also beautiful.

The sequencer is also a huge part of Parlando's sound. Entirely unnecessary to making good sounds, but can unlock things you never would've expected. Happy accidents are made here.

For newcomers, my suggestion would be to flip through a couple patches from each category to get an idea of some of the timbres of the instrument, and then just go off and start breaking stuff.

I really appreciate you taking the time to check this out. If you encounter any issues, please send them [my way](https://www.justinhowell.rocks/contact). Otherwise, I'd love to hear anything you create with this, or any ideas you have for future versions. Thanks!

Parlando is a plugin (CLAP, VST3, AU) and a standalone app, for macOS and Windows.

This is a test version. Test versions (before 1.0) stop making sound 60 days after their release, so everyone plays the newest. The header shows how many days are left in the last two weeks. It never stops in the middle of a song, and your sound and patches are kept. A new version starts a fresh 60 days.

The browser version will always be free to use. Once 1.0 is released, the plugin and the app will be paid, with a launch discount.

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
