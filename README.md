# mpv-image-viewer
Use mpv as an image viewer.

Add the settings in `mpv.conf` to your `mpv.conf`

Put `image-input.conf` in `~/.config/mpv`

Get autoload.lua from here and save it as `~/.config/mpv/image-autoload.lua` https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua 

I have included a .desktop file to start mpv with --profile=image. Put this file in `~/.local/share/applications`, and then associate image files with it inside your file manager.

Use wasd and scroll wheel to pan and zoom images. See image-input.conf for keybinds.
