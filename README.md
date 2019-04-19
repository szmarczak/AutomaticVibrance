# AutomaticVibrance

> Increases saturation automatically when playing CS:GO on Linux

**Note:** NVIDIA graphics only!

## Installation

Just copy the `AutomaticVibrance` file into your home folder. Don't forget to check `Allow executing file as program`. That's all.

## Usage

To start AutomaticVibrance in background:

```
$ ./AutomaticVibrance --background
```

To force stop AutomaticVibrance:

```
$ ./AutomaticVibrance --stop
```

## What's the difference between the V1 and V2?

The V2 requires `xdotool` package - it will apply the effect **only** when the CS:GO window is active. So when you minimize it, everything goes back to normal.

## License

MIT
