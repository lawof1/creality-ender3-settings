# Creality Ender 3 Printer Settings
*Achieving great quality prints with the Creality Ender 3*

## Introduction
3D printing is a great way to democratize the creation of cool stuff! Once you get started, one major challenge is getting the appropriate print settings and quality right. This is a function of three things:

- The quality of your hardware.
- The quality of your printer's hardware and controller settings, including bed leveling and extrusion calibrations.
- The quality of the print settings used by your slicer to create the resulting G-code for your printer.

Of the three factors listed above, the last category here often is the most complex and potentially problematic.

**This is an unofficial guide for printing with the Creality Ender 3 using Slic3r Prusa Edition (PE) using the stock 0.4mm nozzle and PLA.** Some of the features of the configuration include:

- Proper extrusion, speed, and retraction settings resulting in high-quality prints.
- When using PLA, an algorithm to heat the print bed only for the first few millimeters, when curling/warping can be an issue. The bed temperature will decrease gradually after the first millimeter by a predictable rate.
- Moving the print bed forward after a print so you're not reaching around the back of your Ender 3 or sliding the print bed forward to access your completed prints.

## Before using the Slic3r PE configuration file

There are two things you'll want to make sure you do before using the Slic3r configuration file, bed leveling and extrusion calibration.

### Bed Leveling

I recommend a 5-point bed leveling procedure. My procedure goes like this:

1. Tighten your bed adjustment wheels to provide maximum clearance for the nozzle.
1. Auto-home the z-axis using your printer's controller.
1. Carefully using the controller, move the nozzle over the print bed to the lower left corner of the bed. Level the bed for this point by slowly loosening the adjustment wheel (the bed will move up) until you feel a slight tug with standard 20lb. printer paper.
1. Continue the other 4 points on the print bed, i.e., lower right, upper right, upper left, and center.

![5 Point Leveling](https://cdn.thingiverse.com/renders/2a/51/7d/f6/22/18c306208e1527c0a5ba9f1ea7bc6678_preview_featured.jpg "5 Point Leveling")

### Extrusion Calibration

In addition to bed leveling, extrusion calibration is extremely important for high print quality. The basic idea is that there is going inevitably going to be a difference between how much your printer thinks it's extruding versus how much it's actually extruding. The procedure is a bit in depth and requires some basic math to make the calibration a'djustment, but you'll be glad you did this step to ensure proper print quality.

Here's a great video guide someone created for calibrating the Ender 3 extruder:
https://www.youtube.com/watch?v=lWBkPIXTOlo

## Using the Slic3r PE configuration file

Once you've completed the steps above, import the provided configuration file into Slic3r PE, verify that everything looks correct, and begin your prints!

## Suggestions and Changes

This configuration file is by no means ideal in every situation, and I would love to hear from you if you think you have better settings. It would be great to hear from you how these settings work or if you have improvements to it. Feel free to contact me via GitHub!
