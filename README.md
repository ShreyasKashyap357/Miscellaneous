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
- Designed for a 750-×200px Rainmeter window
### What players is it for?
- **Works with MusicBee and other desktop players supported by Rainmeter's NowPlaying plugin (via CAD {CD Art Display} interface).**
- Will work with any player supported by Rainmeter NowPlaying, but was designed/tested for MusicBee.
### Why was this created?
- The default Mond player didn't show the elapsed progress, only the total duration. Also, there was no percentage progress information. The font size was smaller too.
### Installation / Use
1. Copy this `Player.ini` to your Rainmeter skin directory:
```
Documents\Rainmeter\Skins\Mond@Resources\Player.ini
```
2. Reload or refresh the Mond skin in Rainmeter.
3. Open your music player (e.g., MusicBee) with CAD enabled in its settings.
4. Enjoy the improved visual layout and controls!
### How to adjust
- All key layout variables (font size, progress bar width, margins, etc.) are explained and easy to tweak inside the `.ini`.
- The skin is best viewed at 625×175px, but you can change this in `[MeterBG]`.
### Demo
![Screenshot of the custom Mond Player.ini](https://github.com/ShreyasKashyap357/Miscellaneous/blob/main/Rainmeter%20Mond%20Music%20Player%20Edited%20Look.png?raw=true)
