# Project Throbber

Templates to create music throbbing and LED blinking wallpapers with Wallpaper Engine.

[![Project Throbber Demo 1](http://img.youtube.com/vi/kbeR71cW9qY/0.jpg)](http://www.youtube.com/watch?v=kbeR71cW9qY)

https://www.youtube.com/watch?v=kbeR71cW9qY



# Installation

Download the zip from Github and copy the two folders, `ProjectThrobberGIF` and `ProjectThrobberStatic` into your `%PathToWallpaperEngineInstall%\projects\templates` directory. Notice you place these in the TEMPLATES folder.



# Quick Usage

1) Click Wallpaper Editor
2) Click Use Template
3) Select Project Throbber Static -OR- Project Throbber GIF and give it a name.
4) Import your image in the wizard.
5) Select the colour you want windows and your LEDs to be.
6) Resize/Move the image around to fill the frame as needed.
7) Save, Apply Wallpaper.



# Tweaking Audio Response

![Tweaking Audio Response](https://i.imgur.com/B1KVOZ1.jpg)

1) Open the Wallpaper you created from the template and choose the Image Layer.

2) Click the blue gear in the Scale options for this layer.

3) Mess with the constant values in the script and hit compile.

    * GrowScale (Float, 0.001+, Default 0.025) - modify how much it can zoom on a beat.

    * Freq (Int, 0 to 31, Default 3) - select which frequency range it responds to. 0 is your must wibble wobble bass and 31 is your most tinny tickity tacks.

    * Multiplier (Float, 0.0 to 10.0, Default 2.0) - the higher this value is, the more of a curve that will be applied to the frequency. The result is that a higher value will dampen the amount of reaction when a sound is quiet and boost it when its loud. Basically, higher will generally catch beats more.

    * Here is a video where I dick with those settings. https://www.youtube.com/watch?v=c1LCBFTE_WE

4) Click the Run Scripts button to preview your changes.



# Changing the LED Colour

![LED Setting](https://i.imgur.com/uJuFFfY.jpg)

The LEDs will pulse whatever colour is set to the LEDs colour choice in the wallpaper preferences in Wallpaper Engine. IF that colour is SOLID BLACK it will then default to whatever the Scheme Colour is. (Changing the scheme colour, may need to switch to a different wallpaper and then back again to see its effect.)

# Other Neat Things

If you mess around with it you can make some neat effects. For example if you turn the LED layer set to Visible, and then its Blending Mode set to Average, you can create this colour wash on the beats then dims in quietness.

![Beat Colour Wash](https://i.imgur.com/nVr2DSm.jpg)

[![Project Throbber Demo 3](https://i.imgur.com/WwUChMs.png)](https://www.youtube.com/watch?v=sX_Qc0mc4kg)

https://www.youtube.com/watch?v=sX_Qc0mc4kg