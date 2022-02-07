
# DBus Player Status

```
usage: dbus-player-status [-h] [--bus-name BUS_NAME]
                          [--player-name PLAYER_NAME] [--path PATH]
                          [--interface-property INTERFACE_PROPERTY]
                          [--interface-player INTERFACE_PLAYER]
```

A tool for extracting media player status from DBus

By default it is configured to use Spotify:

```
    --bus-name=org.mpris.MediaPlayer2.spotify
    --player-name=Spotify
    --path=/org/mpris/MediaPlayer2
    --interface-property=org.freedesktop.DBus.Properties
    --interface-player=org.mpris.MediaPlayer2.Player
```

but it may work with other players that also expose information in the same
way via DBus.

optional arguments:
  
* `-h`, `--help`            show this help message and exit
* `--bus-name` `BUS_NAME`
* `--player-name` `PLAYER_NAME`
* `--path` `PATH`
* `--interface-property` `INTERFACE_PROPERTY`
* `--interface-player` `INTERFACE_PLAYER`
