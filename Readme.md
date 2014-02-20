*This repository is a mirror of the [component](http://component.io) module [timoxley/color-convert](http://github.com/timoxley/color-convert). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/timoxley-color-convert`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# color-convert

  Convert between rgb, hsl and hsv.

## Installation

    $ component install timoxley/color-convert

## API

### RGBtoHSL()

  Converts an RGB color value to HSL. Conversion formula
  adapted from http://en.wikipedia.org/wiki/HSL_color_space.
  Assumes r, g, and b are contained in the set [0, 255] and
  returns h, s, and l in the set [0, 1].

### HSLtoRGB()

  Converts an HSL color value to RGB. Conversion formula
  adapted from http://en.wikipedia.org/wiki/HSL_color_space.
  Assumes h, s, and l are contained in the set [0, 1] and
  returns r, g, and b in the set [0, 255].

### RGBtoHSV()

  Converts an RGB color value to HSV. Conversion formula
  adapted from http://en.wikipedia.org/wiki/HSV_color_space.
  Assumes r, g, and b are contained in the set [0, 255] and
  returns h, s, and v in the set [0, 1].

### HSVtoRGB()

  Converts an HSV color value to RGB. Conversion formula
  adapted from http://en.wikipedia.org/wiki/HSV_color_space.
  Assumes h, s, and v are contained in the set [0, 1] and
  returns r, g, and b in the set [0, 255].

## Credit

  [Michael Jackson](http://mjijackson.com/2008/02/rgb-to-hsl-and-rgb-to-hsv-color-model-conversion-algorithms-in-javascript)

## License

  MIT
