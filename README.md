# Parlando

A unique synthesizer by Justin Howell.

It's like a weird physical modeling synth paired with a throat simulation. It sounds like bells from another planet, talking guitars, or metallic percussion that sings to you. I've never seen a modal synth paired with a formant filter and I thought I'd go down the rabbit hole. Really, this synth is for anyone who's tired of the same subtractive synthesis we see everywhere. For someone who wants something unique and weird but also beautiful.

The sequencer is also a huge part of Parlando's sound. Entirely unnecessary to making good sounds, but can unlock things you never would've expected. Happy accidents are made here.

For newcomers, my suggestion would be to flip through a couple patches from each category to get an idea of some of the timbres of the instrument, and then just go off and start breaking stuff.

I really appreciate you taking the time to check this out. If you encounter any issues, please send them [my way](https://www.justinhowell.rocks/contact). Otherwise, I'd love to hear anything you create with this, or any ideas you have for future versions. Thanks!

Parlando is a plugin (CLAP, VST3, AU) and a standalone app, for macOS and Windows.

The browser version is free to use, at [justinhowell.rocks/parlando](https://justinhowell.rocks/parlando). The plugin and the app are $39 ($29 through December 4, 2026).

Test versions (before 1.0) stop making sound 60 days after their release. 1.0 and later never stop.

## Download

**[Parlando on Gumroad](https://justinmhowell.gumroad.com/l/parlando)**: one purchase has the Mac installer and the Windows zip.

To hear about new versions, click **Watch** at the top of this page, then **Custom**, then tick **Releases**. GitHub will email you whenever there's a new one. The notes for each version are on this page's Releases; the downloads are on Gumroad.

## Install

**macOS** (Apple Silicon and Intel). Open `Parlando-<version>-macOS.pkg` and follow the installer. It puts the CLAP, VST3 and AU plugins in `/Library/Audio/Plug-Ins` and the app in `/Applications`.

If you played a test version, delete its copies first, or your DAW may find Parlando twice:

| Delete | From |
|---|---|
| `Parlando.clap` | `~/Library/Audio/Plug-Ins/CLAP` |
| `Parlando.vst3` | `~/Library/Audio/Plug-Ins/VST3` |
| `Parlando.component` | `~/Library/Audio/Plug-Ins/Components` |

**Windows** (64-bit). Unzip `Parlando-<version>-Windows.zip`, then move:

| File | Goes in |
|---|---|
| `CLAP\Parlando.clap` | `C:\Program Files\Common Files\CLAP` |
| `VST3\Parlando.vst3` | `C:\Program Files\Common Files\VST3` |
| `Standalone\Parlando.exe` | anywhere you like |

Then rescan plugins in your DAW. To update, download the new version from Gumroad and install it the same way. Your patches and projects carry over.

Parlando contains open-source software. Its licences are in `THIRD_PARTY_NOTICES.txt`, which comes with each download and sits inside each plugin.

## Which version am I on?

Point at the *parlando* name in the header. The line at the bottom of the panel reads the version, for example `Version: 1.0.0 · build 300`.

## Found a problem?

[Open an issue](https://github.com/JustinMHowell/parlando/issues) and include the version (point at the *parlando* name and the tip line reads it), your DAW and your system. If you can, say what you played and what you expected to hear.
