<p align="center">
  <img src="docs/icon.png" width="96" alt="Sonora icon">
</p>

<h1 align="center">Sonora</h1>

<p align="center">
  A music player for the songs you own, with synced lyrics, a cinema mode and a look you can make entirely your own.
</p>

<p align="center">
  <a href="https://github.com/Amariless/Sonora-releases/releases/latest/download/Sonora-Windows-Setup.exe"><img src="https://img.shields.io/badge/Windows-Installer_.exe-17161c?style=for-the-badge&labelColor=e8a33d&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDMuNCA5LjggMnY5LjRIMHpNMTEgMS44IDI0IDB2MTEuM0gxMXpNMCAxMi42aDkuOFYyMkwwIDIwLjZ6TTExIDEyLjZoMTNWMjRsLTEzLTEuOHoiLz48L3N2Zz4=" alt="Download for Windows"></a>
  <a href="https://github.com/Amariless/Sonora-releases/releases/latest/download/Sonora-Linux-x86_64.AppImage"><img src="https://img.shields.io/badge/Linux-AppImage-17161c?style=for-the-badge&labelColor=e8a33d&logo=linux&logoColor=white" alt="Download for Linux"></a>
</p>

<p align="center">
  <img src="docs/screenshot.png" width="880" alt="Sonora browsing a music library by artist">
</p>

## What it is

Point Sonora at your music folder and it builds your library by itself: artists, albums, genres and covers. It's fast, needs no account and works offline. It's made for people who keep their music as files and want to enjoy it properly.

On the first run a short setup walks you through your music folders, the look, where playlists live and how lyrics are found, in about a minute.

<table>
  <tr>
    <td width="62%"><img src="docs/cinema.png" alt="Sonora cinema mode with a full-screen visualizer and lyrics"></td>
    <td width="38%">
      <h3>Cinema mode</h3>
      <p>Turn the whole screen into a light show. Hundreds of MilkDrop visualizations react to the music, with the lyrics floating on top.</p>
      <p>It can change the visualization with every song or every few seconds, and you can keep your favorites and hide the ones you don't like.</p>
    </td>
  </tr>
  <tr>
    <td width="62%">
      <h3>Lyrics that follow the song</h3>
      <p>Sonora shows synced lyrics line by line, from <code>.lrc</code> files next to your songs, from the tags inside them, or by looking them up for you as <i>artist - title</i> (LRCLIB and NetEase). Lookups are optional and can be turned off.</p>
      <p>Lyrics that only exist as plain text are spread over the song automatically, so they still scroll along.</p>
    </td>
    <td width="38%" align="center"><img src="docs/lyrics.png" width="260" alt="The now playing panel with synced lyrics"></td>
  </tr>
  <tr>
    <td width="62%"><img src="docs/sync.png" alt="The lyrics sync editor with the waveform and a marker on every line"></td>
    <td width="38%">
      <h3>Sync them yourself</h3>
      <p>No synced lyrics for a song? Play it and tap a key on every line, with the waveform to guide you. Zoom into the waveform, drag the markers to fine-tune them and mark instrumental parts.</p>
    </td>
  </tr>
  <tr>
    <td width="62%">
      <h3>Make it look like yours</h3>
      <p>Pick a theme for the main window and another for the mini player, light or dark, and customize its colors.</p>
      <p>Change fonts, spacing, corners, the seek bar and which buttons show up. Scale the whole interface from 100% to 150%. Or load a classic Winamp skin (<code>.wsz</code>).</p>
    </td>
    <td width="38%"><img src="docs/themes.png" alt="Sonora theme settings"></td>
  </tr>
  <tr>
    <td width="62%"><img src="docs/unwrapped.png" alt="Sonora Unwrapped showing the song of the year"></td>
    <td width="38%">
      <h3>Your year in music</h3>
      <p><b>Unwrapped</b> turns what you played into a full-screen story: minutes listened, your song, artist and genre of the year, your best days and streaks. Songs play as you tap through it, and you can pick a color palette.</p>
      <p>Everything is computed on your computer, and you can export it as an image, PDF or data file.</p>
    </td>
  </tr>
</table>

## Features

- **Smart playlists** that fill themselves from rules, plus ready-made lists for your most played songs, recent additions and songs you haven't heard in a while.
- **Smart shuffle** that favors songs you rate higher or play less, and avoids playing the same artist twice in a row.
- **An animated, comfortable interface** with smooth transitions, ratings and columns you can arrange the way you like.
- **Fast**, even with thousands of songs. The library updates itself when you add or remove music.
- **Great sound**: an equalizer with profiles for your headphone model, volume normalization and crossfade between songs. On Windows it can also send audio straight to your sound card, untouched (bit-perfect).
- **Your playlists, as they are**: open and save `.m3u8` and `.pls` playlists, and import the ones from MusicBee.
- **Cut a song** to the part you like. MP3 files are cut without re-encoding, so nothing is lost.
- **A mini player** for when you just want the controls.
- **Your language**: English and Spanish are built in, and you can add your own by dropping a translation file in a folder.
- **Private by default**: no account and no tracking. The only things that use the internet are optional: lyrics lookups, the birthplace of your artists in Unwrapped, and the update check.

## Download

| System | Download | Notes |
|---|---|---|
| **Windows** | [Installer (.exe)](https://github.com/Amariless/Sonora-releases/releases/latest/download/Sonora-Windows-Setup.exe) | Windows 10 or 11. If SmartScreen shows up, choose *More info → Run anyway*. The installer isn't signed with a paid certificate. |
| **Linux** | [AppImage](https://github.com/Amariless/Sonora-releases/releases/latest/download/Sonora-Linux-x86_64.AppImage) | Any distribution. Make it executable (`chmod +x`) and open it. |
| **Debian, Ubuntu, Mint** | [Package (.deb)](https://github.com/Amariless/Sonora-releases/releases/latest/download/Sonora-Linux-amd64.deb) | Double-click it or install it with `sudo apt install ./Sonora-Linux-amd64.deb`. |

There's no macOS version yet. Older versions and release notes are on the [Releases](https://github.com/Amariless/Sonora-releases/releases) page.

To update, go to *Settings → Updates → Check for updates*. Updates are signed, so the app only accepts files published here. On Linux, automatic updates work with the AppImage.

## Feedback

Found a bug, have an idea or just want to say something? Each button opens a short form.

<p>
  <a href="https://github.com/Amariless/Sonora-releases/issues/new?template=bug.yml"><img src="https://img.shields.io/badge/Report_a_bug-e8a33d?style=for-the-badge" alt="Report a bug"></a>
  <a href="https://github.com/Amariless/Sonora-releases/issues/new?template=idea.yml"><img src="https://img.shields.io/badge/Suggest_an_idea-e8a33d?style=for-the-badge" alt="Suggest an idea"></a>
  <a href="https://github.com/Amariless/Sonora-releases/issues/new?template=comment.yml"><img src="https://img.shields.io/badge/Leave_a_comment-e8a33d?style=for-the-badge" alt="Leave a comment"></a>
</p>

---

<sub>This repository only hosts the installers; the source code is private.</sub>
