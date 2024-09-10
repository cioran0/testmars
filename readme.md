OSD implementation of the sepia tint. Expansion of https://github.com/cioran0/sepia__tint_demo for OSD

Description from that:
----
Have a black and white photo/image needing a tint? I got you covered!

This is just to show a simple tint with hue-rotate on the color wheel from sepia to replicate an existing tint, in this case sand color. You can't rotate greyscale due to the lack of color information so you convert to CSS sepia(100%) first for color information then rotate color from there. Hue-rotate confuses a lot of people because it's kind of confusing. It confused me! Basically look at a color wheel. Pick the spot you're at. Pick the spot you want to go to. Add or subtract. So sepia is 30degrees, wanted something a little redder (red is 0deg) so I subtract 10 off the 30 to go in that direction. Bear in mind you'll have to adjust brightness, saturation and contrast after too. So it's not really an exact science.

And read this: https://www.quackit.com/css/functions/css_hue-rotate_function.cfm

Screenshots of mars images off fdelhoume Mars tile image pyramid page.
