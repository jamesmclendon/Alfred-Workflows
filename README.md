# [Alfred](http://alfredapp.com) Workflows

## MPlay

Play music with [MPlayer](http://www.mplayerhq.hu/), [GNU Screen](http://www.gnu.org/software/screen/), and Spotlight.

### Usage

![MPlay controls screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/MPlay-Controls.png)

- `mplay >`: access the current session in a terminal
- `mplay album`: filter albums by name
- `mplay shuffle`: shuffle all, recent, or tagged albums
- `mplay recent`: filter albums by date added
- `mplay tagged`: filter albums by a specified Finder tag
- hotkey and Alfred Remote playback controls

![MPlay config screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/MPlay-Config.png)

- `\mplay art`: toggle artwork preview with Quick Look
- `\mplay dir`: set top-level music directory
- `\mplay tag`: set tag for "Browse Tagged Albums"
- `\mplay days`: set time frame for "Browse Recent Albums"

![MPlay info screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/MPlay-Info.png)

- song information via Notification Center

Requires [mplayer](http://www.mplayerhq.hu/).

`brew install mplayer`

Add `shell -$SHELL` to `~/.screenrc` to allow screen to accept the ANSI escape sequences required for MPlayer's seek commands. 

###[Download](https://github.com/jamesmclendon/Alfred-Workflows/blob/master/MPlay.alfredworkflow?raw=true)###

## Notes

Filter files by filename or contents. Open, reveal in Finder, or preview selection with Quick Look.

- `enter`: open in the default editor
- `cmd` + `enter`: reveal in Finder
- `alt` + `enter`: preview with Quick Look

![Notes screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/Notes.png)

###[Download](https://github.com/jamesmclendon/Alfred-Workflows/blob/master/Notes.alfredworkflow?raw=true)###

## Browser

Open a URL in Safari, Chrome, Firefox, or all three browsers.

![Browser screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/Browser.png)

###[Download](https://github.com/jamesmclendon/Alfred-Workflows/blob/master/Browser.alfredworkflow?raw=true)###

## Timer

Set a timer for n minutes.

![Timer screenshot](https://raw.githubusercontent.com/jamesmclendon/Alfred-Workflows/master/Timer.png)

###[Download](https://github.com/jamesmclendon/Alfred-Workflows/blob/master/Timer.alfredworkflow?raw=true)###

## Notification Center

- `enter`: toggle Notification Center
- `cmd` + `enter`: toggle Do Not Disturb

###[Download](https://github.com/jamesmclendon/Alfred-Workflows/blob/master/Notification-Center.alfredworkflow?raw=true)###
