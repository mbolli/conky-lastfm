# conky-lastfm
Queries the last.fm API to get your last played/currently playing song.

## Usage
Put the following in your conky config file (e.g. /etc/conky/conky.conf):
```lua
Now Playing: ${execi 30 (python /path/to/now-playing)}
```

## Notes
You'll need an [API key from last.fm](http://www.last.fm/api/account/create) for this script to work. 
