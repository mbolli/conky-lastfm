# conky-lastfm

## Usage
Put the following in your conky config file (e.g. /etc/conky/conky.conf):
```lua
Now Playing: ${execi 30 (python /path/to/now-playing)}
```
