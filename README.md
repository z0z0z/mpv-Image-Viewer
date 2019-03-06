# mpv-Image-Viewer
mpv Image Viewer config

A set of keybinds and configuration to use mpv as an image viewer. Check input-image.conf to understand the keybind usage.

I have included a .desktop file to start mpv with --profile=image. Put this file in ~/.local/share/applications, and then associate image files with it inside your file manager.

You need autoload.lua from here (https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua) to automatically create playlists from images in the same directory.

I have also included Nautilus (AKA Gnome files) shell scripts to form playlists from mpv by selecting files inside Nautilus, which I find very useful. Put these in ~/.local/share/nautilus/scripts, and a context menu will appear in Nautilus to open files with these scripts.
