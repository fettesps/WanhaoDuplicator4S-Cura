# WanhaoDuplicator4S-Cura

## Intro
Whoever created the profile for the Wanhao Duplicator 4S in Cura either had never seen one before or completely mixed up the files for another printer.  Most notably it did not contain the definition for a second extruder which meant you couldn't even attempt to use it in Cura.

After recently reformating my laptop and realizing I had forgot to backup my configuration for Cura I went to work getting it setup again and this time documenting it in case I lost it again.  Plus I figured someone else may find it handy some day.

## Instructions
Start off by downloading the latest version of Cura. As of the time of writing this I have tested this setup on Cura 3.6, 4.0 and 4.2.1, so you should be able to use this with any recent version of Cura.  If you already have a copy of Cura installed make sure to backup your configuration as you may corrupt it in the process.

Close Cura if it is open and then extract the contents of this repository into your Cura resources folder.  For example mine is C:\Program Files\Ultimaker Cura 4.2\resources\. Overwrite any existing files the folder. This will install a new printer definition plus two extruder definitions.  

You will need install the X3GWriter plugin by Seva Alekseyev.  To install it click on Marketplace at the top right of Cura and then scroll down unti you see the X3GWriter plugin.  Or checkout their Github at https://github.com/Ghostkeeper/X3GWriter

## Addendum
I highly recommend using OctoPrint if you have an extra Raspbery Pi lying around.  You can download it at https://octoprint.org/download/. Once again you will want to download and install the X3G plugin at https://plugins.octoprint.org/plugins/gpx/.

## References
https://reprap.org/wiki/G-code

https://github.com/makerbot/ReplicatorG/tree/master/machines/replicator
