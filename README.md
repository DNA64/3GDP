
*These files are being provided today "As-Is" as part of an effort on my part to archive and share projects I've worked on over the years.* 

**USE WITH CAUTION AND AT YOUR OWN RISK!**

# 3GDP
**iPhone 3G Baseband Downgrader Pro v1.3.5 for BB 02.30.03 by DNA64 (aka ATTNCK)**

*04/15/2009*

**Please keep in mind this is only for iPhone 3G's running the 2.2.1 (5H11) Firmware with the 02.30.03 BaseBand, and the 5.08 (5.8) Boot Loader.**

## About

After testing phasebanddowngrader by pH (Pedro Henrique Franceschi) and not having any success I decided to skip using his script and start fresh using the GeoHotz bspatch method which I applied to the ICE2_02.28.00.fls file, the end results were success! 

I therefore decided to write my own script, as I felt pH left out some critical features from his. I also tried "DownBB" with no success, and felt that there was not enough documentation for any of these tools. Comments by several users that tried and failed seemed to support my theory. 

I submitted 3GDP to BigBoss for hosting but he decided not to host it because it was a another command line utility and both Dustin Howett "DHowett" and w1kedZ were working on FuzzyBand, a GUI downgrader which would eventually be released. 3GDP is still to this day superior to FuzzyBand, fortunately the team took my advice and implemented some of my suggestions which fixed at least one major bug. Unfortunately, they didn't add automatic unlocking as I had done in 3GDP. 

## Instructions

**Installation:**

Run ./downgrade from the MobileTerminal application (or via SSH) and follow the on screen directions.

**Uninstalling:**

Run ./uninstall from the MobileTerminal application (or via SSH) and follow the on screen directions.
*(The uninstall script included will remove all files installed, created, or downloaded.)*

## Credits

Thanks to GeoHot and all the other iPhone Dev Team members for all their hard work,
without them and GeoHot's bspatch the downgrade would not be possible.

yellowsn0w was created by members of the iPhone Dev Team.
The unofficial version 0.98 is included with these tools,
but is not supported by the team and is provided as is.

And finally thanks to "Nik S Denin" for his Serial Number Output Script.

## Support

http://twitter.com/DNA64
