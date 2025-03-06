# swoop-zmk-config
[ZMK firmware](https://github.com/zmkfirmware/zmk/) config for the [Swoop MX](https://github.com/jimmerricks/swoop).

## Features
- [Miryoku](https://github.com/manna-harbour/miryoku) keyboard layout
- [urob's timeless homerow mods](https://github.com/urob/zmk-config#timeless-homerow-mods)

## How to Flash
1. Download `swoop_left-nice_nano_v2-zmk.uf2` and `swoop_right-nice_nano_v2-zmk.uf2` from the [latest release](https://github.com/snicklepickles/swoop-zmk-config/releases).
2. For each half:
    - Enter bootloader mode on the nice!nano by:
       - Double-tapping the reset button, or
       - Quickly shorting the RST and GND pins twice
    - Connect nice!nano via USB to computer
       - It should appear as a USB storage device named "NICENANO"
       - If not, try a different USB cable or port, ensuring both support data transfer
     - Drag and drop corresponding `.uf2` file onto the "NICENANO" device

## Todo
- Add mouse emulation layer
- Add numword
- Add support for rotary encoders

![20230708_142433~3](https://github.com/snicklepickles/zmk-config/assets/95944530/c672fa21-72d3-48e2-bc9e-026236ef4fc6)
