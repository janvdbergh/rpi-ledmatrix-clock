# raspberrypi-ledmatrix-clock
Clock using a Raspberry Pi displayed on a led matrix which can be controlled using the Open Sound Control (OSC) protocol.
This code requires
- rpi-rgb-led-matrix from https://github.com/hzeller/rpi-rgb-led-matrix.
- oscpack from http://www.rossbencina.com/code/oscpack

## Supported commands:
- `/time <time in seconds since Sunday 00:00>`: display a time.
- `clear`: clear the display.