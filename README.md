# mpv-image-viewer
Config to use mpv as an image viewer.

A set of keybinds and configuration to use mpv as an image viewer.

I have included a .desktop file to start mpv with --profile=image. Put this file in ~/.local/share/applications, and then associate image files with it inside your file manager.

You need autoload.lua in `~/.config/mpv` from here (https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua) to automatically create playlists from images in the same directory.
