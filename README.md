StepMania tinted-default theme
=======================

This is a variant of the StepMania default theme (see [the `Themes/default` directory within the `stepmania` project](https://github.com/stepmania/stepmania/tree/master/Themes/default)) which has been altered into an adjustable monochrome by replacing many color settings that are defined directly in the original.

In `Scripts/02 Colors.lua`, a variable named `TintHue` defines the approximate center hue of the color scheme (in degrees). A map `ColorSchemeColors` is then populated with color values based on that hue with saturation and value guided by what they would have been in the original theme, and values from `ColorSchemeColors` are then used where the original color values previously appeared.
