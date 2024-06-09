Executable | Description | Requirements
-|-|-
`c` | Opens `$1` in VS Code | VS Code
`feh` | Wraps `feh` to run with a default theme | `feh` must be installed, and a default theme must be set in `~/.config/feh/themes`  for example `default -Z -.`
`header-create` | Creates a new C++ header guarded with a UUID at `%1` | `uuidgen`, `sed`
`img` | Shows the images in `$1` fullscreen in a random order | `feh`
`shuffle` | Plays a random album | `mpv` must be installed, and the path `/mnt/192.168.1.2/RO Music` must exist and contain directories each containing one album, with all tracks at the root
`that-music` | Plays music as downloaded by [Archivist](https://github.com/Asday/archivist) | `mpv` must be installed, and the path `/mnt/192.168.1.2/Web Series/That Music/` must contain some video files
`update-archive` | Iterates through currently archiving directories and archives anything new | [Archivist](https://github.com/Asday/archivist)
`vid` | Shows the videos in `$1` looping in a random order | `mpv`
