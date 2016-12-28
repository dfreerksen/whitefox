# WhiteFox

Aria keyboard with custom layout.

![Whitefox Aria](https://github.com/dfreerksen/whitefox/raw/master/img/aria.png "Whitefox Aria")

## Requirements

- [Homebrew](http://brew.sh/)

## Setup

1. Install [dfu-util](http://dfu-util.sourceforge.net/)

```
$ brew install dfu-util
```

2. Put the keyboard in programming mode.

There is a small hole on the bottom of the keyboard. The hole will light up in orange when pushed. LED lights on your keyboard will turn off.

3. Flash the keyboard using `dfu-util`

```
dfu-util -a 0 -R -D ./aria/kiibohd.dfu.bin
```

4. Start using the keyboard

The hole on the bottom of the keyboard will turn off. LED lights on your keyboard will turn on again.
