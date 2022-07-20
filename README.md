This is my audio shortcut in my system.
Using Ubuntu 22.04

Play/Pause
CTRL + SUPER + spacebar


Previous music
CTRL + SUPER + left arrow cursor


Next music
CTRL + SUPER + right arrow cursor


Volume Up
CTRL + SUPER + up arrow cursor


Volume Down
CTRL + SUPER + down arrow cursor


Change audio to HDMI output
pacmd set-card-profile 0 "output:hdmi-stereo-extra1+input:analog-stereo"

Change audio to analog output
pacmd set-card-profile 0 "output:analog-stereo+input:analog-stereo"


reference:
Change audio output via command line
https://askubuntu.com/a/1242344/519255

