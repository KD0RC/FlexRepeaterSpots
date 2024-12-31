# FlexRepeaterSpots
FlexRepeaterSpots is a utility for Flex 6000 and 8000 series transceivers.  It places “permanent” spots on your SmartSDR screen (these spots do not time out like DX spots).  The spots indicate the frequency and name of FM repeaters.  A table of FM options is kept for each repeater spot such that clicking on a spot applies the appropriate options (mode, offset and direction, CTCSS tone, squelch) to the active slice (i.e. the slice that just landed on the spot).

This utility is also good for spots that are not FM oriented.  I use it to mark nets, band edges and W1AW bulletin frequencies.  As of V1.08, the utility will place callsign data from a clicked spot into the callsign box in any of the N3FJP loggers.  Only DX spots will populate the callsign box.

Spot color and spot background color are now available to set both as a default and on individual spots.  The color values are here:
https://learn.microsoft.com/en-us/dotnet/api/system.windows.media.colors?view=windowsdesktop-8.0
