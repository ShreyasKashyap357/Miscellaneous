# Miscellaneous
This is a repository for any miscellaneous code that I may require.



## Rainmeter Mond Music Player - Custom `Player.ini` Skin
### What is this?
This is a **heavily customized `Player.ini` configuration file** for the [Rainmeter](https://www.rainmeter.net/) ["Mond"](https://visualskins.com/skin/mond) skin, focusing on the **music player section**.  
It displays a minimalist, centered music player interface with:
- Elapsed/total time (top left), remaining time (top right)
- Thin, centered progress bar with elapsed/remaining percentages below
- Song title and artist in the center, always readable even for long names
- Fully centered previous, play/pause, and next controls at the bottom
- Clean white/orange-on-black color scheme
- Designed for a 750×200px Rainmeter window
### What players is it for?
- **Works with MusicBee and other desktop players supported by Rainmeter's NowPlaying plugin (via CAD {CD Art Display} interface).**
- Will work with any player supported by Rainmeter NowPlaying, but was designed/tested for MusicBee.
### Why was this created?
- The default Mond player didn't show the elapsed progress, only the total duration. Also, there was no percentage progress information. The font size was smaller too.
### Installation/Use
1. Copy this `Player.ini` to your Rainmeter skin directory:
```
Documents\Rainmeter\Skins\Mond\Player\Player.ini
```
2. Reload or refresh the Mond skin in Rainmeter.
3. Open your music player (e.g., MusicBee) with CAD enabled in its settings.
4. Enjoy the improved visual layout and controls!
### How to adjust
- All key layout variables (font size, progress bar width, margins, etc.) are explained and easy to tweak inside the `.ini`.
- The skin is best viewed at 625×175px, but you can change this in `[MeterBG]`.
### Demo
![Screenshot of the custom Mond Player.ini](https://github.com/ShreyasKashyap357/Miscellaneous/blob/main/Rainmeter%20Mond%20Music%20Player%20Edited%20Look.png?raw=true)



## Rainmeter Mond Album Art – Standalone `AlbumArt.ini` Skin
### What is this?
This is a **minimal standalone album art skin** for [Rainmeter](https://www.rainmeter.net/) designed to pair visually with the ["Mond"](https://visualskins.com/skin/mond) skin or any modern setup.
**Features:**
- Displays current song's album cover art (fetched via NowPlaying/CAD from desktop music players like MusicBee)
- Song title and artist, shown in the same Aquatico font/upper case/left-aligned style as the main player skin
- No width limits by default: titles start flush left and will not cut off
- Transparent, resizable background (defaults to 200×200 album art, easy to change)
- Simple, looks clean when floating on desktop or next to your main music player widget
### What players is it for?
- **Works with MusicBee and other desktop music players that support Rainmeter's NowPlaying plugin via CAD (CD Art Display) interface.**
- Should work with any player NowPlaying-CAD supports.
### Why was this created?
- To have a **separate, always-visible album art display** matching the main Mond music player skin.
- Ideal if you want album art shown in a different spot/monitor, or want a cover display separate from player controls.
- Font, formatting, and layout are consistent with the custom Mond Music Player skin.
### Installation/Use
1. Make a new skin folder in your Rainmeter directory, e.g.:
```
Documents\Rainmeter\Skins\MondAlbumArt\AlbumArt.ini
```
2. Place this file and a default fallback image (`noart.png` recommended) in the same folder (or `@Resources` subfolder if you prefer).
3. Refresh all in Rainmeter. Load the AlbumArt skin.
4. Open your music player (e.g., MusicBee) with CAD enabled.
5. **You'll see album art and song info appear automatically!**
### How to adjust
- Edit `[Variables]` at the top of the `.ini` to change `ArtW` and `ArtH` (cover image size)
- Font size, positioning, and margin can be changed in the `[MeterSongTitle]` and `[MeterSongArtist]` meters.
- By default, both song and artist names are *left-aligned* and use the main skin font.
- Add a border, background color, or click actions as you wish!
### Demo
![Screenshot of Mond AlbumArt](https://github.com/ShreyasKashyap357/Miscellaneous/blob/main/Rainmeter%20Mond%20MondAlbumArt%20Plugin%20Look.png?raw=true)
