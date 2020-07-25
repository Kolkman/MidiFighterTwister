# Midifighter Twister 16 layout for Logic Pro X

## What is this?

The MidiFighter Twister controller his highly customisable and can be used to steer a great many of controls in LogicPro X.

Here you find two files that together form a setup for the Midifighter Twister and Logic Pro X.

The .mfs file is the configuration file used by the Midifighter Utility program and the `com.apple.logic.pro.cs` is the learned settings that accompangny these settings.



## Install

Import `Utility Settings - Logic Pro Twister.mfs`
into the MidiFighter Utility program and then load it into your twister.

Make sure that LogicPro X has been quit and then copy `com.apple.logic.pro.cs` to ` ~/Library/Preferences`. Note that this action will overwrite all customised midi learnings. I am not aware of a method to merge these settings.

If you do not know how to do this from the command line look at `Installation Guide - Logic Pro Twister.pdf`

## Disclaimer and Warning

By overwriting `com.apple.logic.pro.cs` you loose not only existing 'learned midi settings' but also overwrite you other preferences. Unfortunatelly Apple has not come up with a simple way to export, import, and manipulate the 'learned midi' settings.

The file you pull from this repository may contain specifics from my settup.


## Acknowledgements

Based on a mapping by 'Stewe' his version 0.10 from the [DJ Techtool repository](https://maps.djtechtools.com/mappings/10661) is the initial commit into this git repository.

